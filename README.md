CSS Preprocessors: SASS/SCSS for Efficient Styling
 Novice
 Weight: 1
 Project will start Jul 7, 2025 12:00 AM, must end by Jul 14, 2025 12:00 AM
 Checker was released at Jul 7, 2025 12:00 AM
 Manual QA review must be done (request it when you are done with the project)
 An auto review will be launched at the deadline
Quiz questions
Great! You've completed the quiz successfully! Keep going! (Show quiz)
Tasks
0. Project Set up
mandatory
Objective: install and set up SASS

Instructions:

Inside the alx-intermediate-frontend repository, create a new directory called 0x03-sass_scss
Linux installation (Optional)
In your ubuntu terminal install node version 20.16 as follows:
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
Exit the terminal using the exit command then reopen it.
Installation Anywhere (Optional)
Install SASS by using the following command if you have node installed:
npm install sass -v 3.7.4
Create an empty file 0-installation-script.

Inside it write the steps you took to install SASS

Repo:

GitHub repository: alx-intermediate-frontend
Directory: 0x03-sass_scss
File: 0-installation-script
1. Creating a Sass File to Output Debug Message 'Hello World
mandatory
Instruction:

Write a Sass file that prints Hello world in the debug output.
guillaume@ubuntu:~/$ sass 0-debug_log.scss | head -n 0
0-debug_log.scss:2 DEBUG: Hello world

guillaume@ubuntu:~/$ 
Repo:

GitHub repository: alx-intermediate-frontend
Directory: 0x03-sass_scss
File: 0-debug_log.scss
2. Using Sass Variables to Assign Text Color to Body and Paragraph Tags
mandatory
Objective: color tag

Instructions:

Write a Sass file that assigns the text color #3D3D3D to the HTML tags body and p.
You must use a Sass variable
guillaume@ubuntu:~/$ sass 1-color_variable.scss | tail -n +2

body {
  color: #3D3D3D; 
}

p {
  color: #3D3D3D;
}

guillaume@ubuntu:~/$ 
Repo:

GitHub repository: alx-intermediate-frontend
Directory: 0x03-sass_scss
File: 1-color_variable.scss
3. Nesting
mandatory
Instructions:

Write a Sass file that assigns:

No margin or padding in body tags

Margin 10px to all of the p tags inside body tags

You must use nested declarations

guillaume@ubuntu:~/$ sass 3-nested_tag.scss | tail -n +2

body {
  margin: 0px;
  padding: 0px; 
}

body p {
  margin: 10px; 
}

guillaume@ubuntu:~/$
Repo:

GitHub repository: alx-intermediate-frontend
Directory: 0x03-sass_scss
File: 2-nested_tag.scss
4. Margin mixins
mandatory
instructions

Write a Sass file that assigns:

Margin left and right at 10px to body tags

Margin left and right at 15px to div tags

You must use a mixin

guillaume@ubuntu:~/$ sass 8-mixin_margins.scss | tail -n +2
body {
  margin-left: 10px;
  margin-right: 10px; }

div {
  margin-left: 15px;
  margin-right: 15px; }
guillaume@ubuntu:~/$
Repo:

GitHub repository: alx-intermediate-frontend
Directory: 0x03-sass_scss
File: 3-mixin_margins.scss
