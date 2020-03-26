# Rental-Website

## Part 1

### Website Description
This entails a tutorial using Ember.js for a website for renting apartments. HTML/CSS and JavaScript are used.

### Website Walk-though
"http://g.recordit.co/oT7bK2FyWf.gif"

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

#### While building these pages, you learn about:

<ul>
  <li>
Defining routes<li>
Using route templates<li>
Customizing URLs<li>
Linking pages with the <LinkTo> component<li>
Passing arguments and attributes to components
  </ul>
  
#### In the process, you will learn about:

<ul>
  <li>
The purpose of automated testing <li>
Writing acceptance tests <li>
Using generators in Ember CLI <li>
Testing with the QUnit test framework <li>
Working with Ember's test helpers <li>
Practicing the testing workflow
  </ul>

#### In doing so, you will learn about:

<ul>
  <li>
Extracting markup into components <li>
Invoking components <li>
Passing content to components <li>
Yielding content with the {{yield}} keyword <li>
Refactoring existing code <li>
Writing component tests <li>
Using the application template and {{outlet}}s
  </ul>
  
#### While building this list of rental properties, you will learn about:

<ul>
  <li>
Generating components <li>
Organizing code with namespaced components <li>
Forwarding HTML attributes with ...attributes <li>
Determining the appropriate amount of test coverage
  </ul>
  
#### While doing so, you will learn about:

<ul>
  <li>
Adding behavior to components with classes <li>
Accessing instance states from templates <li>
Managing state with tracked properties <li>
Using conditionals syntaxes in templates <li>
Responding to user interaction with actions <li>
Invoking element modifiers <li>
Testing user interactions
</ul>

#### While adding the map, you will learn about:

<ul>
  <li>
Managing application-level configurations <li>
Parameterizing components with arguments <li>
Accessing component arguments <li>
Interpolating values in templates <li>
Overriding HTML attributes in ...attributes <li>
Refactoring with getters and auto-track <li>
Getting JavaScript values into the test context
  </ul>
  
  
#### In this chapter, you will learn about:
<ul>
  <li>
Working with route files <li>
Returning local data from the model hook <li>
Accessing route models from templates <li>
Mocking server data with static JSON files <li>
Fetching remote data from the model hook <li>
Adapting server data <li>
Loops and local variables in templates with {{#each}}
</ul>
