# Insta_Clone

Inta_Clone

## Author's Name

mary atieno

## Table of Content

[Description](#Description)

[Installation](#Installation)

[userstory](#userstory)

[RunningProject](#RunningProject)

[TechnologiesUsed](#TechnologiesUsed)

[Licence](#Licence)

## Description

A clone website for instagram where you can post ,comment, like ,message and many more

## Installation

To view the app.Visit -> Insta_Clone

Clone this repo: git clone <https://github.com/Mary-Atieno/Insta_Clone.git>

The repo comes in a zipped or compressed format. Extract to your prefered location and open it.

open your terminal and navigate to gallery then create a virtual environment.For detailed guide refer here

To run the app, you'll have to run the following commands in your terminal

pip install -r requirements.txt

On your terminal,Create database gallery using the command below.

CREATE DATABASE instaclone:

**if you opt to use your own database name, replace instagram your preferred name, then also update settings.py variable DATABASES > NAME
Migrate the database using the command below

python manage.py migrate

Then serve the app, so that the app will be available on localhost:8000, to do this run the command below:

python manage.py runserver

Use the navigation bar to navigate and explore the app.

## user story

Users need to Sign in to the application to start using.

Users can view different photos.

Users can click on a single photo to view it and also view details of the photo.

Users can search for different photos.

Users can Upload their pictures to the application.

Users can see their profile with all their picture.

Users can view a picture and leave a comment on it.

## Running Project

Use the command given below to run automated tests.

    python manage.py test insta

## Technologies Used

Django - web framework used
CSS
HTML
JavaScript

## MIT License

Copyright (c) [2022] [Mary Atieno]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
