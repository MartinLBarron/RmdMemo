# RmdMemo

One Paragraph of project description goes here

## Getting Started

This package includes a single template to create a pdf memo using R Markdown.  After installation, Rstudio will show a new template under File -> New File -> R Markdown -> From Template entitled "Memo." 

### Prerequisites

This template requires RMarkdown and Knitr to work.  If you are not familiar with either, you probably aren't interested in this package.  It assumes that you ar working in Rstudio but doesn't require it.   

### Installing

Use devtools to install

```
devtools::install_github("MartinLBarron/RmdMemo")
```
Open a new rmd file in Rstudio: File -> New File -> R Markdown -> From Template -> Memo.

Change the Header of your document to reflect your document. You can replace the placeholder memo with your own memo, just name it "Logo" and place it in the same folder as the template.  You can exclude the memo by setting "IncludeLogo: false".  Change the document properties as desired (you can change the papersize, fontsize, margins, and adjust the vertical location of the logo.

## Acknowledgment

The base latex template is built off of [https://github.com/dr-harper/example-rmd-templates]Mike Harper's example template.  Inspiration for the latex memo format came from [https://www.latextemplates.com/template/memo]this template originaly created by Rob Oakes.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. (It basically says: do what you want with this but don't blame me if it doesn't work.)


