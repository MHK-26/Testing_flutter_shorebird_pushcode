# Flutter Shorebird Feature Test

## Overview

This Flutter project serves as a testbed for the Shorebird feature, specifically exploring how to push code in Flutter apps. Shorebird is a powerful tool for enhancing the development workflow in Flutter applications.

## Features

- **Shorebird Integration**: Explore the integration of Shorebird for efficient code pushing in Flutter apps.

### Shorebird: Install and Use

- Create an account on [Shorebird](http://shorebird.dev).

- To install Shorebird on MacOS, use the following command:
    ```bash
    curl --proto '=https' --tlsv1.2 https://raw.githubusercontent.com/shorebirdtech/install/main/install.sh -sSf | bash
    ```

- Login to your account using:
    ```bash
    shorebird login
    ```

- Initialize Shorebird in your project directory:
    ```bash
    shorebird init
    ```

- Create a release APK and submit your app to Shorebird using:
    ```bash
    shorebird release android
    ```

- When you change your code and want to push your code to the released app, use:
    ```bash
    shorebird patch android
    ```
