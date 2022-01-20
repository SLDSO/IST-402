Question 1: Open package.json and look at the scripts devDependencies and dependencies sections. What do you think each section does here? What commands can you run? 
Answer 1: I believe the devdependencies section reads the developer dependencies and what version they are running (open-wc,zsh, etc). The dependencies section shows what version of lit I am running. I used cd hello-world to get into the directory then used cat package.json to view what was in the file.

Question 2: The "demo" for your hello-world element is found in index.html. Reading this code, what does it do and how does it work? What HTML is making your script load to show a demo? How is this file rendering HTML via JavaScript?
Answer 2: The code displays the style and characters of the output "Hello World". It also displays the script type and that it is imported from lit. the div id = demo is making the script load to show a demo. The file is rendering HTML via JavaScript through the hello-world.js file.

Question 3: The Definition of your element is in your-element-name.js, while the class JS object is found in src/YourElementName.js. Why do you think they put these in two separate files? What do you think each code block is doing in the class'ed object? Leaving comments either in the source via // or in your
Answer 3: It makes sense to separate these two files to help prevent clutter or possibly size (granted these aren't the most massive files). The code blocks in the class file display the color as well as the increment counter of the output. 

Question 4: Try to explain what Lit is providing to the repo. What's so special about what Lit is providing that I'd be so bold to say it changes how the web is developed, forever? 
Answer 4: Lit provides various components that could be used over and over again. It is special because this is something that can be used to help developers gain components from anyone for any use that they see fit. 
