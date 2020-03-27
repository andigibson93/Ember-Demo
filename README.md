<img src= https://guides.emberjs.com/images/service/style-super-rentals-maps.png width=800><br>

# Rental-Website

## Part 1

### Website Description
This entails a tutorial using Ember.js for a website for renting apartments. HTML/CSS and JavaScript are used.

### Website Walk-though
http://g.recordit.co/oT7bK2FyWf.gif

# Installing Ember CLI

You can install the latest version of Ember CLI by running the following command. If you've already done this by following the Quick Start guide, feel free to skip ahead!

```
$ npm install -g ember-cli
```

To verify that your installation was successful, run:

```
$ ember --version
ember-cli: 3.16.0
node: 12.16.0
os: linux x64
```

# Creating a New Ember App with Ember CLI

We can create a new project using Ember CLI's ```new``` command. It follows the pattern ```ember new <project-name>.``` In our case, the project name would be ```super-rentals:```


```
$ ember new super-rentals
installing app
Ember CLI v3.16.0

Creating a new Ember app in /home/runner/work/super-rentals-tutorial/super-rentals-tutorial/dist/code/super-rentals:
  create .editorconfig
  create .ember-cli
  create .eslintignore
  create .eslintrc.js
  create .template-lintrc.js
  create .travis.yml
  create .watchmanconfig
  create README.md
  create app/app.js
  create app/components/.gitkeep
  create app/controllers/.gitkeep
  create app/helpers/.gitkeep
  create app/index.html
  create app/models/.gitkeep
  create app/router.js
  create app/routes/.gitkeep
  create app/styles/app.css
  create app/templates/application.hbs
  create config/environment.js
  create config/optional-features.json
  create config/targets.js
  create ember-cli-build.js
  create .gitignore
  create package.json
  create public/robots.txt
  create testem.js
  create tests/helpers/.gitkeep
  create tests/index.html
  create tests/integration/.gitkeep
  create tests/test-helper.js
  create tests/unit/.gitkeep
  create vendor/.gitkeep

Installing packages... This might take a couple of minutes.
npm: Installing dependencies ...
npm: Installed dependencies

Initializing git repository.
Git: successfully initialized.

Successfully created project super-rentals.
Get started by typing:

  $ cd super-rentals
  $ npm start

Happy coding!
```

This should have created a new folder for us called ```super-rentals.``` We can navigate into it using the ```cd ``` command.

```$ cd super-rentals```

For the rest of the tutorial, all commands should be run within the ```super-rentals``` folder. This folder has the following structure:
```
super-rentals
├── app
│   ├── components
│   │   └── .gitkeep
│   ├── controllers
│   │   └── .gitkeep
│   ├── helpers
│   │   └── .gitkeep
│   ├── models
│   │   └── .gitkeep
│   ├── routes
│   │   └── .gitkeep
│   ├── styles
│   │   └── app.css
│   ├── templates
│   │   └── application.hbs
│   ├── app.js
│   ├── index.html
│   └── router.js
├── config
│   ├── environment.js
│   ├── optional-features.json
│   └── targets.js
├── public
│   └── robots.txt
├── tests
│   ├── helpers
│   │   └── .gitkeep
│   ├── integration
│   │   └── .gitkeep
│   ├── unit
│   │   └── .gitkeep
│   ├── index.html
│   └── test-helper.js
├── vendor
│   └── .gitkeep
├── .editorconfig
├── .ember-cli
├── .eslintignore
├── .eslintrc.js
├── .gitignore
├── .template-lintrc.js
├── .travis.yml
├── .watchmanconfig
├── README.md
├── ember-cli-build.js
├── package.json
├── package-lock.json
└── testem.js

15 directories, 32 files
```

We'll learn about the purposes of these files and folders as we go. For now, just know that we'll spend most of our time working within the ```app``` folder.

# Starting and Stopping the Development Server
Ember CLI comes with a lot of different commands for a variety of development tasks, such as the ```ember new``` command that we saw earlier. It also comes with a development server, which we can launch with the ```ember server``` command:

```
$ ember server
building...

Build successful (9761ms) – Serving on http://localhost:4200/
```

The development server is responsible for compiling our app and serving it to the browsers. It may take a while to boot up. Once it's up and running, open your favorite browser and head to http://localhost:4200.

<ul>
  <li>
Installing Ember CLI <li>
Creating a new Ember app with Ember CLI <li>
Starting and stopping the development server <li>
Editing files and live reload <li>
Working with HTML, CSS and assets in an Ember app </ul>

## While building these pages, you learn about:

```
Defining routes

Using route templates                            Customizing URLs                    Linking pages with the <LinkTo> component

Passing arguments and attributes to components   The purpose of automated testing    Writing acceptance tests

Using generators in Ember CLI.                   Testing QUnit test framework        Working with Ember's test helpers

Practicing the testing workflow                  Extracting markup into components   Invoking components

Passing content to components.                   Yielding content with the {{yield}} Refactoring existing code 

Writing component tests                          Using {{outlet}}s                   Generating components

Organizing code with namespaced components       Forwarding HTML attributes          Determining amount of test coverage

Adding behavior to components with classes       Accessing instance templates        Managing state with tracked properties

Using conditionals syntaxes in templates         User interaction with actions       Invoking element modifiers

Testing user interactions.                       Managing application-level configs  Parameterizing components with arguments 

Accessing component arguments                    Interpolating values in templates   Overriding HTML attributes 

Refactoring with getters and auto-track          JavaScript values into test context  Working with route files

Returning local data from the model hook         Accessing route models               Mocking server data with static JSON  

Fetching remote data from the model hook         Adapting server data                 Loops and local variables with {{#each}}

```
