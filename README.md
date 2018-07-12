## Feed reader app

Web-based application that reads RSS feeds.

## Table of Contents

* [Instructions](#instructions)
* [Installation](#installation)
* [Jasmine](#jasmine)

## Instructions

When you open the index.html file you will be presented with your first RSS feed.
You have the ability to browse trough other feeds by clicking the menu icon
on your top left corner of the page.

There are 4 different RSS feeds to choose from:
- Udacity Blog
- Css Tricks
- HTML5 Rocks
- Liner Digressions

## Installation

Clone the current repository using: git clone https://github.com/virgilseo/feedreader-project.git.

Open the index.html file in your browser and start checking out RSS feeds.

It is highly recommended to use Chrome as your go to browser.

## Jasmine

Some key features of the app were tested using Jasmine, a development framework for testing
Java Script code.

The process is comprised of four different test suites:

##### RSS Feeds

In this test we are making sure that the RSS feeds are defined and they
contain a name and a URL.

##### The Menu

Ensuring the menu is hidden by default and that it changes visibility when the
icon is clicked.

##### Initial Entries

Ensuring the first RSS feed loads when we start the app.

##### New feed Selection

Ensuring the content actually changes when the user selects a new feed.
