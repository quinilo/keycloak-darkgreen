<p align="center">
    <i>🚀 A custom theme for keycloak creted with keycloakify 🚀</i>
    <br/>
    <br/>
</p>

<div style="display: flex; justify-content: center; width: 350px; margin: 0 auto;">

![image](https://raw.githubusercontent.com/quinilo/keycloak-darkgreen/refs/heads/master/img/img.png)

</div>

[Keycloakify Documentation](https://docs.keycloakify.dev/)

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
