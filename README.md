# School Test Creator

A Python program that makes creating test documents easier for school teachers. The program currently supports creating a document of true/false, fill in the blank, and multiple choice questions inputted by the user. These questions will be formatted appropriately and added to a Microsoft Word .docx file.

## Motivation

I discovered that making tests for many teachers takes up a significant amount of time when having to deal with formatting on document files. I realized that using Python can potentially take out the extra work behind formatting out of the equation and let teacher focus on coming up with the questions and answers for their tests. Currently, the program only supports three types of questions but teachers can input any other types of questions manually after the program is done. The point of the program is to cut down as much time for teachers as possible.

## Technology Used

- [Python-docx](https://python-docx.readthedocs.io/en/latest/#): python library that can be used to create docx files with formatting

## Usage

Usage simply requires running the terminal program. The user will be prompted for inputs depending on what types of questions and answers they want to add. The user can select the type of question they want to add and will then be prompted to enter the questions themselves. The program will take care of adding and formatting the question to add onto the document. The file will create a .docx file in the same directory as the program.

## Future Plans

While the program currently runs on a .py script, a better, more user friendly version of the app will be created in the future that can be easily used on multiple platforms without installing Python. This is to make the program easier to use and more accessible to those that are not familiar with running Python programs.
This means turning this terminal program into something with a user friendly GUI. The current plan is to build a React web app.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.