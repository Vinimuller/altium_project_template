# Altium Project Template
This repo suggest a way to organize Altium's files and folders to make easier to use it with Git.

## Organization

- **project**
    - Place here your .SchDoc .PcbDoc .PrjDoc .OutJob files.
- **finals**
    - Place here your Gerber files, BOM, SCH and PCB PDF's, and any other output generated.
- **libraries**
    - Place here the libraries that you use on your project. (I recommend use libs as submodules).
- **scripts**
    - Place here your scripts.

.gitignore file is set to keep track of .SchDoc, .PcbDoc, .PrjDoc, .OutJob files, finals fodler, libraries and scripts.

Feel free to improve this ;)