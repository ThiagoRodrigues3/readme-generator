# README Generator
A node.js program that shows a user a series of inquirer-driven questions and creates a professional README.md output. The README.md is generated and found in the 'written' folder.

## Built With 🧰

- [x] Markdown
- [x] Node.js
- [x] Inquirer
- [x] Util

## Installation & Usage

To use, run the following command at the root of your project:

```
node index.js
```

Then, complete the question series.

Check under "written" for your new README.md file output.

### Demo
Large file, so reference in the assets file. Also, checkout the OUTPUT folder to see an example of the README after the generator is run!
    
### User Story 📖

> AS A developer       
> I WANT a README generator       
> SO THAT I can quickly create a professional README for a new project       

### Acceptance Criteria ✅

> GIVEN a command-line application that accepts user input       
> WHEN I am prompted for information about my application repository       
> THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions       
> WHEN I enter my project title       
> THEN this is displayed as the title of the README       
> WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions       
> THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests       
> WHEN I choose a license for my application from a list of options       
> THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under       
> WHEN I enter my GitHub username       
> THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile       
> WHEN I enter my email address       
> THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions       
> WHEN I click on the links in the Table of Contents       
> THEN I am taken to the corresponding section of the README          

## Acknowledgement, & Resources 🤝

### Information and Resources Used

- [Official README.md Guide](https://github.com/coding-boot-camp/potential-enigma/blob/master/readme-guide.md)
- [Inquirer Package](https://www.npmjs.com/package/inquirer) 
- [From callbacks to fs/promises to handle the file system in Node.js](https://dev.to/mrm8488/from-callbacks-to-fspromises-to-handle-the-file-system-in-nodejs-56p2)   
- [Utils - Fast, generic JavaScript/node.js utility functions.](https://www.npmjs.com/package/utils)