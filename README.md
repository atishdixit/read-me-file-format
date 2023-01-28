# Project name
***
Short description of the project.
# Headline H1
## Headline H2
### Headline H3
#### Headline H4 
##### Headline H5
###### Headline H6

***

## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)


***
## Table of Contents
<a name="general-info"></a>
### General Info

***
## General Info
***
Write down general information about your project. It is a good idea to always put a project status in the readme file. This is where you can add it. 
### Screenshot
![Image text](/path/to/the/screenshot.png)

***
## Technologies
***
A list of technologies used within the project:
* [Technology name](https://example.com): Version 12.3 
* [Technology name](https://example.com): Version 2.34
* [Library name](https://example.com): Version 1234

***
## Installation( source text in the document : The code can be formatted with “```” at the beginning and end.)
***
A little intro about the installation. 
```
$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start
```
Note: To use the application in a special environment use ```lorem ipsum``` to start.

## Collaboration (A “>” at the start of the line will change the text into a quote.)
***
Provide instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> Should it encompass several lines?
> This is how you do it.

***
## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer to the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question, we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer to the third question with *italic words*.
4. **Fourth question in bold**
| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |

***
## For more information [Here](https://www.ionos.com/digitalguide/websites/web-development/readme-file/)  

## What is "pom" packaging in maven?
* <packaging>pom</packaging>
* <packaging>jar</packaging>
* <packaging>war</packaging>
> “pom” packaging is nothing but the container, which contains other packages/modules like jar, war, and ear. if you perform any operation on outer package/container.  > like mvn clean compile install. then inner packages/modules also get clean compile install. no need to perform a separate operation for each package/module.