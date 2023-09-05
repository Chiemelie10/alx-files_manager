# Files Manager

This project is a compilation of back-end concepts: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files with:

1) User authentication via a token
2) Listing of all files
3) Uploading a new file
4) Changing permissions of a file
5) Viewing a file
6) Generating thumbnails for images

## Core technologies

|                                                                                                         |                                                                                      |                                                                                              |
| ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| ![Redis](https://upload.wikimedia.org/wikipedia/en/thumb/6/6b/Redis_Logo.svg/1000px-Redis_Logo.svg.png) | ![MongoDB](https://webassets.mongodb.com/_com_assets/cms/mongodb_logo1-76twgcu2dm.png) | ![NodeJS](https://d2eip9sf3oo6c2.cloudfront.net/tags/images/000/000/256/full/nodejslogo.png) |

## Testing and Jobs

A queueing job mechanism for creating thumbnails of photos uploaded to the application is included in the project. When a new user is created, it also leverages this feature to generate a welcome message. Bull is used in all of this. 
![Bull & NodeJS](https://raw.githubusercontent.com/OptimalBits/bull/master/support/logo%402x.png)

Mocha is used in combination with Chai for testing the app.

![Mocha & Chai](https://miro.medium.com/max/499/0*WpXBkrfgR2g9dw2T.png)

## Authors
Eze Taslim Chiemelie: chiemelieeze@yahoo.com <br>
PaschalMark Okafor: pasmac018@gmail.com
