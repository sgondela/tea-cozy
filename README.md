# Excursion

> A web page made with flexbox layout for an imaginary store called Tea Cozy.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Project Status](#project-status)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)


## General Information

- The goal of this project is to replicate the design of a website's design spec with HTML and CSS, with the latter incorporating flexbox. You can see the design and redline specs under `resources/spec` in this repository.
- This project is intended as a demonstration of working understanding of flexbox properties of CSS3 in a local dev environment.


## Technologies Used

- HTML5
- CSS3
- Git - version 2.24.3


## Setup

To clone and run this application, you'll need Git and a web browser installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/sgondela/tea-cozy.git
```
Then, open the `index.html` file in your web browser.

## Project Status

Project is: _in progress_


## Acknowledgements

This project is an assignment given by Codecademy in the Full-Stack Engineer PRO Path.

I troubleshooted using [this video](https://www.youtube.com/watch?v=fJc18fT4T3s) by Nenad Dabic on Youtube. The video helped me realize that in order to maintain `space-between` to be equal in the `justify-content` attribute in all rows with a wrapped flexbox with a short last row, my `width` property had to be set to `max-width`, so the width would adjust to the shorter last row automatically.

My 