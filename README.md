# DNA

#### _Epicodus Drupal Independent Project Number Four, 16 December 2016_

#### By _**HK Kahng**_

## Description

Project Requirements: Your independent project has two parts today. First of all, some Ajax, then a small logic problem to make sure you know how to write functional and unit tests. Remember to read all instructions first, and write your unit tests before writing your module logic.

### Ajax View:

* Create a View to display inside of a block on your front page
* Make the View display an unformatted list of linked titles for your choice of content: articles, or your site's custom content type.
* Ajax enable the links in your view.
* Create a block with a wrapper div in it to display whichever title you've clicked on in your view using ajax.
* Create a custom module to handle the ajax calls and load the content into the div.

### DNA

* Create a custom module which presents a form where the user can enter in one half of their DNA helix. Your module should generate the other half and print both sides on the browser. There is no need to use Ajax on this part of the project.
* Start with writing unit tests before writing your module logic, and start with simple input output pairs. Then write the module and include a functional test to make sure the whole interface works.
* Remember to validate the input. You should only allow your user to type in the letters A, T, C, G.

#### Specifications

* A DNA molecule of A returns T as its pair.
* A DNA molecule of T returns A as its pair.
* A DNA molecule of C returns G as its pair.
* A DNA molecule of G returns C as its pair.
* An input of space is returned as-is.
* An input of ATCG returns TAGC.
* An input of A T C G returns T A G C.
* An input of A c TC G b returns T AG C .

## Prerequisites

You will need MAMP/WAMP properly installed on your computer.

## Installation

* `git clone <repository-url>` this repository
* Import the `dna.sql.zip` file into MySQL
* Create a database account (`dna`, password: `dna`) in MySQL and grant it full access to the database
* Set MAMP/WAMP's web server directory to the project folder
* Navigate to localhost:8888 (or whatever local server settings you have for MAMP/WAMP)
* Site maintenance user: `dna`, password: `dna`

## Known Bugs

There are no known bugs in this application.

## Support and contact details

Contact me via GitHub!

## Technologies Used

This app uses the following bits of Human ingenuity: Drupal 7, MySQL, and PHP.

### License

Published under the MIT License.

Copyright (c) 2016 **_HK Kahng_**
