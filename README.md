# Visual Analytics Projects
# Summary

- [Node.js](#installing-nodejs): Install Node.js using the appropriate installer for your operating system.
    - [NPM](#npm): Node Package Manager
- [Vue.js](#installing-vuejs-and-initializing-a-project): Install Vue.js with `npm` and initialize a new project using `vue init`.
- [Git](#installing-git): Install Git using the appropriate installer for your operating system. Use basic Git commands like `add`, `commit`, and `push` to manage code changes.
    - [Usage](#using-git): Some git commands

## Installing Node.js

Node.js is required for many web development tools and frameworks. Here's how to install it:

1. Go to [https://nodejs.org/en/download/](https://nodejs.org/en/download/).
2. Download the appropriate version for your operating system.
3. Run the installer and follow the prompts.

### NPM
Once you've installed Node.js, you can use `npm` to manage packages and dependencies for your project. Here are some of the main `npm` commands you'll use:

- `npm install`: Install all dependencies listed in `package.json`.
- `npm install <package>`: Install a specific package and save it to `package.json`.
- `npm install --save-dev <package>`: Install a development-only package and save it to `package.json`.
- `npm start`: Start the project using the `start` script defined in `package.json`.
- `npm run <script>`: Run a custom script defined in `package.json`.

Here's an example of how to use these commands:
```
$ npm install
$ npm install vue
$ npm install --save-dev eslint
$ npm start
$ npm run build
```

The npm install command installs all dependencies listed in the dependencies and devDependencies sections of package.json. The npm install <package> command installs a specific package and saves it to package.json. The npm install --save-dev <package> command does the same, but for development-only packages.

The npm start command runs the start script defined in package.json, which is typically used to start the project. The npm run <script> command runs a custom script defined in package.json. For example, npm run build might run a script to build the project for production.

## Installing Vue.js and Initializing a Project

Vue.js is a popular JavaScript framework for building user interfaces. Here's how to install it and create a new project:

1. Open a terminal or command prompt.
2. Install Vue.js by running: `npm install -g vue-cli`
3. Navigate to the directory where you want to create your project.
4. Create a new Vue.js project by running: `vue init webpack my-project`
5. Follow the prompts to configure your project.

## Installing Git

Git is a version control system that allows you to track changes to your code. Here's how to install it:

1. Go to [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Download the appropriate version for your operating system.
3. Run the installer and follow the prompts.

### Using Git

Once you've installed Git, you can use it to manage your code changes with these basic commands:

- `git init`: Initialize a new Git repository in the current directory.
- `git add <file>`: Add a specific file to your Git repository.
- `git add .`: Add all files in the current directory to your Git repository.
- `git commit -m "<commit message>"`: Commit your changes with a descriptive message.
- `git push <remote(optional)> <branch(optional)>`: Push your changes to a remote repository, such as GitHub.

Here's an example of how to use these commands:

```
$ git init 
$ git add .
$ git commit -m "Added new feature"
$ git push origin master
```

>**Note**: The `git init` command initializes a new Git repository in the current directory, which sets up the repository to track changes to your code. You only need to run this command once per project.
## Course Projects

### [Vega Test](./vega_test/)
### [Vue Init](./vue_init/vue-project/) 
