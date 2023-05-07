# Welcome to Isomer Pages!

## Why Markdown and YAML?

Traditionally, in order to edit a website, one had to write in pure HTML. This is challenging for website administrators who had limited experience with HTML as it is not immediately readable or intuitive to non-experienced users. 

Our team decided to go with Markdown (.md) – more human readable syntax – so as to empower non-technical website administrators.

While Markdown is appropriate for writing long segments of text, it alone does not allow users to edit small details of the website (e.g. change the hero-banner image) without diving into the HTML.

We therefore chose to supplement the Markdown syntax with YAML (.yml) – yet another human readable syntax.

## YRSG User Guide (May 2023)
- Most of the edits can and should be done via the Isomer CMS
    - The Isomer CMS would create the respective codes in this repository. For example, when we create a page "test" with some text, a corresponding .md file is created       here.
    - You can locate the file within the repository to insert html code, if necessary.
- For edits which require code changes, please take note of the following main files:
  - _config.yml : a file to edit the primary and secondary colors (more on this at custom.scss file) of the website
  - index.md : a file which contains the layout of the home page. Changes are automatically done for you if you have made them via the Isomer CMS. However, if custom code is required, then you would have to use this file.
  - custom.scss file in the "misc" folder : the file that governs the color and styling of the website. Here, you can make limited changes to the colors, such as     background of the page, text colors etc. However, please note how the different elements affect each other. Changing some of them might result in unintended changes in other parts of the website. For example, there are two main colors of text: (1) primary, and (2) secondary. In the web site, a particular heading or phrase would be assigned to the primary color (has-text-primary) or secondary color (has-text-secondary), depending on the class (as per the parenthesis). There seems to be no way to change the assigned class. One way would be to manually insert a html to effect a new color, but this may make the code untidy.
 - Jobs are classified according to the industry that the company tagged them to in MCF. There is a mapping table for this. 
   - I have tried adding search, sort and filter functions to the job pages. However, this is not possible at this point in time.
