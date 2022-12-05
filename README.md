# Unibo thesis template (English 🇺🇸)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)   
Write your __bachelor/master thesis__ in English using a valid __LaTeX template__ for __University of Bologna__ (__Unibo__).

Check [this document](https://github.com/Tale152/master-thesis/releases/latest) to see an example of the final result.

## Table of contents
- [Template description](#template-description)
- [Tutorial](#tutorial)
- [Compile the Document on VSCode](#compile-the-document-on-vscode)
    - [Install the recommended dependencies](#install-the-recommended-dependencies)
    - [Install required software (Windows)](#install-required-software-windows)
- [Releasing the PDF document](#releasing-the-pdf-document)

## Template description
Using this template, you will be able to easily write and build your LaTeX thesis locally using __VSCode__.  
The template contains a series of __additional commands__ that can help you create an even greater looking thesis!  
Finally, through automation, you can __easily make your thesis document available online__ so that you will always have an easy-to-access way to get your compiled document from anywhere.

## Tutorial
By clicking on ➡️ [this link](https://github.com/TemplatesHub/unibo-thesis-template-english/releases/latest) ⬅️ (or by going in the "__Releases__" section of this repository), you will get the latest draft of the document produced by this template.  
The document, other than showing the final result, contains a tutorial explaining how to use this template.

## Compile the Document on VSCode
### Install the recommended dependencies
Upon opening the project VSCode will ask you if you want to install the required dependencies; proceed to install them.  

Alternatively, recommended dependencies can be found under the extensions tab typing _@recommended_ in the search bar.

### Install required software (Windows)
Follow [this](https://www.youtube.com/watch?v=4lyHIQl4VM8) tutorial to install the required software on Windows (if you installed the recommended dependencies you will already have LaTeX Workshop on VSCode).

## Releasing the PDF document
Despite being able to compile your document locally, you may want to release it in your repository; in order to do that, you can simply create a new release and this will automatically trigger a workflow. Said workflow will generate your PDF document, making it available as an attachment in your latest repository's release.  

Once the workflow is over, you will find your compiled document attached in the latest release of your repository.

To customize the name of the final PDF file, see [this link](https://github.com/marketplace/actions/latex-build-and-release).
