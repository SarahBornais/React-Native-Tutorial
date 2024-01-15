# React Native Tutorial

## Step 1. Installing Tools

### VS Code

Visual Studio Code is a free and open-source code editor created by Microsoft. It is flexible, extensible, and works on many different platforms. We'll use it to work on our React Native application. To install it:

- **Windows:** Download the app from here: https://code.visualstudio.com
- **Chromebook:** Follow the "Download VS Code" step of the tutorial here: https://medium.com/@jacoboakley/web-development-with-a-chromebook-react-environment-setup-46173b1dc375

### Node

Node.js is a tool that lets programmers use JavaScript to build fast and efficient servers for websites and applications. It has two particularly helpful features:

1. The `npm` and `npx` command-line tools that will help us install many tools we'll need quickly and easily
2. A _runtime_, which will run the code we write on our computers. To install it:

- **Windows:** Go to this website: https://nodejs.org/en/download/ and click the "Windows Installer" button
- **Chromebook:** Follow the "Install Node.js" step of the tutorial here: https://medium.com/@jacoboakley/web-development-with-a-chromebook-react-environment-setup-46173b1dc375

## Step 2. Creating the App

Run `npx create-expo-app [APP NAME]` (e.g., `npx create-expo-app demo-app`) to create an empty React Native application.

## Step 3. Running the App

In the terminal, navigate to the `demo-app` folder in this repository (e.g., `cd demo-app`).

Run `npm-install` in the `demo-app` folder to ensure all the libraries the app is using are up-to-date.

Run the app using one of the following commands:

- To run the web version: `npm run web`
- To run the iOS version: `npm run ios`
- To run the Android version: `npm run android`

## Step 4. Editing the App

Git is a tool that helps software developers work together on projects by keeping track of changes to the code (kind of like you use Google Docs to work together on documents). It's a command-line application, so we need to install it before we can use it:

- **Windows:** install Git by downloading the appropriate installer here: https://git-scm.com/download/win
- **Chromebook:** git should be automatically installed when you install Linux (check out this tutorial for more details https://www.geeksforgeeks.org/how-to-install-git-on-chrome-os/)

### Pushing Changes

Let's say you made a change to one of the app files locally, to "publish" your changes so that the rest of the team can see them, you need to run a couple of commands:

1. `git add -a`: tells git that you want to publish all of the changes you made
2. `git commit -m "[A SHORT DESCRIPTION OF THE CHANGES]"`: describes the changes you made so that the rest of the team knows why you made them
3. `git push origin main`: actually publishes (or pushes) your changes to GitHub where the rest of the team can see them

### Pulling Changes

Let's say one of your teammates changed some files and pushed them using the steps above, and now you want to download them to your computer. To do so, simply run `git pull origin main`. This will "pull" all of the files on GitHub to your local computer.
