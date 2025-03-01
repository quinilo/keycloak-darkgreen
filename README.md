<p align="center">
    <i>🚀 <a href="https://keycloakify.dev">Svelte + Vite Keycloakify</a> v11 starter 🚀</i>
    <br/>
    <br/>
</p>

This starter is based on Vite and Svelte.

# Quick start

```bash
git clone https://github.com/keycloakify/keycloakify-starter-svelte
cd keycloakify-starter-svelte
yarn install # Or use an other package manager, just be sure to delete the yarn.lock if you use another package manager.
```

# Testing the theme locally

[Documentation](https://docs.keycloakify.dev/testing-your-theme)

# How to customize the theme

[Documentation](https://docs.keycloakify.dev/customization-strategies)

# Building the theme

You need to have [Maven](https://maven.apache.org/) installed to build the theme (Maven >= 3.1.1, Java >= 7).  
The `mvn` command must be in the $PATH.

- On macOS: `brew install maven`
- On Debian/Ubuntu: `sudo apt-get install maven`
- On Windows: `choco install openjdk` and `choco install maven` (Or download from [here](https://maven.apache.org/download.cgi))

```bash
yarn run build-keycloak-theme
```

Note that by default Keycloakify generates multiple .jar files for different versions of Keycloak.  
You can customize this behavior, see documentation [here](https://docs.keycloakify.dev/targeting-specific-keycloak-versions).

# Initializing the account theme

```bash
yarn keycloakify initialize-account-theme
```

# Initializing the email theme

```bash
yarn keycloakify initialize-email-theme
```

# Ejecting pages

```bash
yarn keycloakify eject-page
```

# Adding storybook stories

```bash
yarn keycloakify add-story
```
