# Contributing to Web-Ifc-three

Thanks for checking out the IFCjs web-ifc-three project! We're excited to hear and learn from you. We love your input! We want to make contributing to this project as easy and transparent as possible.

We've put together the following guidelines to help you figure out where you can best be helpful.

# Table of Contents

1. Setting up your environment
2. How to Contribute
3. Issues to get started with

# 🖥️ Setting up your Environment

1. Fork the [web-ifc-three](https://github.com/IFCjs/web-ifc-three) github repository.
2. Now, lets setup this repo on our local machine!

   - Clone the forked repository. To clone it, first copy the HTTPS url of your forked repository.
    <p align="center">
    <img src = "https://user-images.githubusercontent.com/77961530/183715093-b6d4d6c0-d2c8-4633-afa8-d13a8c7e8acc.png" width="600"/>
    </p>

   - Now, lets setup the repository on our local machine.
     ```shell
     git clone https://github.com/YOUR_USERNAME/web-ifc-three.git
     ```
   
   - Now, lets add an upstream connection!
      ```shell
      cd web-ifc-three

      git remote add upstream https://github.com/IFCjs/web-ifc-three.git
      ```

3. Installing libraries - Before you start making any code related contributions, you need to install some libraries required for web-ifc-three. These libraries are as follows:

   - Install IFC.js:
    ```shell
    npm i web-ifc-three
    ```
   - Install three.js:
    ```shell
    npm i three
    ```

   - Install a bundler:
    ```shell
    npm i rollup --save-dev
    npm i @rollup/plugin-node-resolve --save-dev
    ```


