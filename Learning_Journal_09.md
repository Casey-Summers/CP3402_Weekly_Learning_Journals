# Week 9 - Sass Practical Learning Journal

## Learning Activities & Resources
> Guiding statements/questions: :bulb:
> - If you learned from something, link it!
> - Compare why you chose to learn one thing over the other.
> - Format: `topic` | `Purpose` | `Link`

#### Desired learning outcomes & identified gaps in knowledge:
- [x] Practise Sass fundamentals: variables, nesting, mixins, and extend/inheritance.
- [x] Research how Gulp can be used to automate SCSS -> CSS workflow
- [x] Set up and automate a Sass-to-CSS workflow using Gulp.
- [x] Understand and troubleshoot common errors (npm not installed, other issues).
 - [x] Install node.js to a Root Path, so npm could be called
- [x] Organise project file structure to mimic industry standards
- [x] Add simple content to the site and integrate a basic JavaScript button for interactivity.
- [ ] Polish the website to have more meaningful content and additional pages

#### Learning Resources:
1. `Sass Official Docs` | `Comprehensive guide to Sass features` | [Sass Documentation](https://sass-lang.com/documentation)
2. `Gulp Documentation` | `Setting up automated workflows` | [Gulp Docs](https://gulpjs.com/docs/en/getting-started/quick-start)
3. `MDN Web Docs` | `Understanding CSS and JavaScript integration` | [MDN Web Docs](https://developer.mozilla.org/en-US/)
4. `Stack Overflow` | `Troubleshooting npm and gulp errors` | [Stack Overflow](https://stackoverflow.com/questions/33827249/cannot-install-and-run-gulp-via-npm)
5. `Node.js Install` | `Installation Wizard and guide for Node` | [Node Installer Page](https://nodejs.org/en)
6. `File Structure` | `Suggested Industry layout for files and folders` | [Sass Guidelines](https://sass-guidelin.es/#architecture)
7. `YouTube Tutorial` | `Practical Sass and Gulp setup` | [YouTube Video](https://www.youtube.com/watch?v=QgMQeLymAdU)

## Estimated Hours
#### This week, I spent `5` hours working through the Sass practical, setting up Gulp, and troubleshooting errors.

## Content Insights
Working on the Sass practical was an extremely informative experience that answered a common concern I have had with .css files for a long time: Why is there so much disorder, strict hierarchy, and general messiness? Learning SCSS reinforced the importance of structured project organisation, and Gulp brought it all together with an automated workflow. I learned how Sass features such as variables, nesting, mixins, and extend/inheritance not only make the code cleaner but also easier to maintain. For instance, using a placeholder `%btn-base` or `%centered-text` enabled me to centralise styling, and extending it across different elements kept my CSS DRY (Don’t Repeat Yourself).

Setting up the Gulp workflow was initially challenging, as I was struggling to wrap my head around all of the different places/files that needed to be referenced the same. This led me to look into industry standards for the best file layout to keep naming conventions simple and short. Hence, I created the `css` and `scss` folders, which were correctly referenced and saved a lot of confusion. Otherwise, this experience underscored the importance of verifying file paths and understanding how glob patterns work.

I also faced an npm installation issue early on, which highlighted the importance of ensuring that Node.js is properly installed and available on the system PATH before troubleshooting gulp configuration, styles, or references. Once npm was correctly set up, running `npm start` allowed me to automate the Sass-to-CSS compilation seamlessly, and I was very impressed that Gulp could automatically compile the SCSS file into CSS to effectively.

Additionally, adding a simple JavaScript alert to the "Click Me" button taught me how even minor interactive features can enhance user experience without overcomplicating the project. This small integration reinforced the concept of front-end interactivity and how different technologies can work together.

## Career/Employability/Learning Insights
**Career Insights:**  
Practicing Sass and automating workflows with Gulp is essential in modern front-end development. These skills may be quite specific, but even if not used exactly, they have taught me general lessons and best-habits that are highly valued in the industry (as they lead to more efficient and maintainable projects). My experience in troubleshooting and configuring these tools will help me tackle similar challenges in professional settings.

**Employability Insights:**  
Employers look for developers who can set up complex build processes and write clean, scalable code. Most importantly, find workflows that are logical and automated, which was practiced today. Otherwise, the ability to quickly diagnose and fix issues like glob errors or npm configuration problems demonstrates practical problem-solving skills.

**Personal Learning Insights:**  
This practical taught me that I shouldn't just put up with solutions that feel inefficient or cluncky; I should instead look for modern alternatives, as most likely, someone has had the same issue and developed a smart solution. Additionally, Initial setbacks, such as the file path issues and npm errors, were frustrating but ultimately provided valuable lessons. I learned that thorough configuration is key to building a reliable and efficient development setup.

---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Original work of ***Casey Summers***
