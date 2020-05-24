## Revisions and the Cloud
Changes made to GitHub repositories do not have to be made directly on GitHub. I can make a copy of the repository to my computer, make changes, and push those changes back to GitHub when I'm finished.

### Steps to make changes on a local computer:
1. Open the GitHub repository, click the green "Clone or download" button and click the copy icon.
2. Open the terminal application on my computer. Type `cd ~/your/file/path` to point to a directory made specifically for this class.
3. Type `git clone https://github.com/mlhaus/learning-journal.git` to make a copy of this repository.
4. Type `cd learning-journal` to move into my repo directory.
5. Type `code .` to open the files in VS Code.
6. Use VS Code to organize and edit files according to the directions. 
7. After every meaningful change, perform the following commands.
   - `git status` to see the changes made to my repository.
   - `git add .` to add all changes to a stage.
   - `git commit -m 'Short message'` to explain the changes.
   - `git push origin master` to send the changes to GitHub.
8. Refresh the GitHub repository and see the changes.
9. Repeat steps 6-8.

## Site Navigation
- [Home](README.md)
- [Growth Mindset](GROWTH_MINDSET.md)
- [Learning Markdown](LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Revisions and the Cloud](REVISIONS_AND_THE_CLOUD.md)
- [Structure Webpages With HTML](STRUCTURE_WEBPAGES_WITH_HTML.md)
- [Design Webpages With CSS](DESIGN_WEBPAGES_WITH_CSS.md)
- [Dynamic Webpages with JavaScript](DYNAMIC_WEBPAGES_WITH_JAVASCRIPT.md)
- [Computer Architecture and Logic](COMPUTER_ARCHITECTURE_AND_LOGIC.md)
- [Programming with JavaScript](PROGRAMMING_WITH_JAVASCRIPT.md)