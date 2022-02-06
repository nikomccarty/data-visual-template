# Data Visualization Template: From collecting to creating

## Overview
This repository sets out the skeleton of an organizational structure used for data visualization projects. In my own work, I use this to create a chart, each week, using data that I collect (scraping), clean (Python) and chart (D3.js, Illustrator, others). It's a loose template for projects of this structure.

## How to Use
To use this template for your research, fork this repository, change the name
to something descriptive for your project, and adjust the licensing as you
see fit.

To use this repository for your own research, simply clone the repo using the following:

```
git clone https://github.com/nikomccarty/data-visual-template your_repo_title
```

> :warning: :warning: :warning: I wouldn't advise forking this repository. A given repository can only be forked once, and so there is little utility in forking this repo if you hope to use it again in your future projects :warning: :warning: :warning:

## Layout

The repository is split into five folders. This structure has been designed to be easily navigable by humans and computers alike, allowing for rapid location of specific files and instructions. This structure may not be perfect for your intended us and may need to be modified. Each section is briefly described below. 


 * **`1_collecting`**: Any code used to collect data. This is often a collection of .py or .ipynb files. It could also be R code, though.
 * **`2_cleaning`**: Any code used to *transform* the data into another type. For me, this is typically Python and the Pandas library.
 * **`3_creating`**: Any code to create charts or graphics. For me, this is a blend of Python and JavaScript.
 * **`figures`**: A folder to hold any figures created from the data. This is typically only static figures, as D3.js code lives in `3_creating`.
 * **`datasets`**: Any datasets collected from `1_collecting`, or imported from other sources. Typically this is .csv or .json. 
 * **`tests`**: All test suites for your code. *Any custom code you've written should be thoroughly and adequately tested to make sure you know how it is working.*

### Required Files
There are some files which I consider to be mandatory for any project.

1. **`LICENSE`**: A legal protection of your work. *It is important to think deeply about the licensing of your work, and is not a decision to be made lightly. See [this useful site](https://choosealicense.com/) for more information about licensing and choosing the correct license for your project.*

2. **`README.md`**: A descriptive yet succinct description of your research project and information regarding the structure outlined below.

# License Information

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="github.com/nikomccarty/data-visual-template">
    <span property="dct:title">Niko McCarty</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">A template for data visual projects, from collecting to charting</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="github.com/nikomccarty/data-visual-template">
  United States</span>.
</p>
