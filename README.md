# LICENSE
You are free to:
* Share — copy and redistribute the material in any medium or format
*  Adapt — remix, transform, and build upon the material for any purpose, even commercially. 

Under the following terms:
* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use. 
* ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

[![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

# How it works
The site runs entirely from static content. It uses [D3JS](https://d3js.org/) to render all the nodes. [ShowdownJS](https://github.com/showdownjs/showdown) is used to render the Markdown files.

# How to add data?
The website follows a few simple rules:
* It's all static content
* Data is stored in a `json` file named `treeData.json`
* It's possible to add a minimalistic documentation for each node

## Objects
* `name`: This is the name of your node
* `color`: Assign a color family to your path based on `colorbrewer.js`
* `docurl`: (optional) if present, path to Markdown file
* `children`: (optional) defines sub node(s) using the structure just above.

# Contribution
If you feel you can improve the dataset or improve the site usability, send you pull requests. I'll add you to the list of contributors.

# Contributors
(in order of contribution)
* Aurelien Requiem
