# Professional README Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)


## Description

This project is a command line application that automatically generates a professional README markdown file for a repository based on answers from the user. When the application runs, it presents a series of prompts to the user to fill in sections in the README. Then the README markdown file with the user information is saved inside the output folder.

## User Story

```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```

### Demonstration

View a complete video demonstration of the application: [Professional README Generator Demo](https://drive.google.com/file/d/1wAcySaMLWmoXP33HXYN5y4IsOgkt1SdA/view?usp=sharing)

![out-readme-screen](./Develop/video/demo.gif "Output README file")

### Output Readme
![out-readme-screen](./Develop/screenshots/Output-README.jpg "Output README file")

## Table of Contents

* [Description](#description)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## Technologies

* [Node.js](https://nodejs.org/)
* [Inquirer.js](https://www.npmjs.com/package/inquirer)

## Installation

To install dependencies, run the following:

```
npm install
```

## Usage

After installing the dependencies, run the application with

```
node index.js
```

## License

[MIT license](./LICENSE).


## Questions

Questions about this repository? Please contact me at [gharduim@gmail.com](mailto:gharduim@gmail.com). View more of my work in GitHub at [Gustavo Harduim](https://github.com/gharduim) 
