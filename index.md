<img src="doc/index-front-image.PNG" alt="front image">

## Table of contents

* [Overview](#overview)
* [Github Organization Link](https://github.com/manoa-club-hunt)
* [Galaxy Deployment Link](http://manoa-club-hunt.meteorapp.com/)
* [Milestone 1 Link](https://github.com/manoa-club-hunt/manoa-club-hunt/projects/1)
* [Milestone 2 Link](https://github.com/manoa-club-hunt/manoa-club-hunt/projects/2)
* [Milestone 3 Link](https://github.com/manoa-club-hunt/manoa-club-hunt/projects/3)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Team Members](#team-members)

## Overview
_The problem:_ UH Mānoa has hundreds of active clubs. However, it can be difficult for new students to find information about potential clubs they want to join. 

_The solution:_ Mānoa Club Hunt will provide students with a directory of clubs containing club information, club meeting location and times, club website links, and club contact information. 
Users will be able to join clubs and receive notifications about the club.
Clubs will be able to send out notifications to their club members through Mānoa Club Hunt. 

## User Guide

### Landing Page:

The [Landing Page](http://manoa-club-hunt.meteorapp.com/#/) is the first page presented to users and gives a brief description of our application.

<img src="doc/landing-page.JPG" alt="landing page">

### Login Page:

Clicking on "Login" in the top right corner of the page and then "Sign In" brings up the [Login Page](http://manoa-club-hunt.meteorapp.com/#/signin). Login if you are already a registered user.

<img src="doc/login-page.JPG" alt="login page">

### Register Page:

Clicking on "Login" in the top right corner of the page and then "Sign Up" brings up the [Register Page](http://manoa-club-hunt.meteorapp.com/#/signup). Sign up if you are a new user.

<img src="doc/register.PNG" alt="register page">

### Landing (after Login) page

Once you log in (either to an existing account or by creating a new one), the navbar changes as follows:

<img src="" alt="new landing page">

### User Home Page:

After logging in, click on "Home" to be directed to the [User Home Page](http://manoa-club-hunt.meteorapp.com/#/userprofile).

<img src="doc/user-home-page.JPG" alt="user home page">

### User Profile Page:

After logging in, click on the user icon in the top right of the navbar then click on "Your Profile". You will go to the [User Profile Page](http://manoa-club-hunt.meteorapp.com/#/userprofile) that shows all of the data associated with your profile.

<img src="doc/user-profile-page.PNG" alt="user profile page">

### Edit User Profile Page:

After logging in, and going to your profile page click on the "Edit Profile" button to go to the [Edit User Profile Page](http://manoa-club-hunt.meteorapp.com/#/edituserprofile). This page allows you to edit your user profile.

<img src="doc/edit-user-profile.png" alt="edit user profile page">

### List Clubs Page:

The [List Clubs Page](http://manoa-club-hunt.meteorapp.com/#/list) shows all of the clubs currently in the system sorted alphabetically. Each club has a website link and club profile link.

<img src="doc/club-directory.JPG" alt="club directory">

### Club Profile Page:

Clicking on the "View Profile" link for a club takes you to the club's profile page that displays information about the club. For example, here is [AAUW-UHM's Club Profile](http://manoa-clubhunt.meteorapp.com/#/clubPage/85fq9K3x9YXqoJgTQ).

<img src="doc/club-profile.PNG" alt="club profile page">

### Edit Club Page:

While logged in, you can click on "Edit Club" on the club profile page to go to the edit club page. This page allows you to edit the data associated with the club. For example, here is the [Edit Club Page for AAUW-UHM](http://manoa-club-hunt.meteorapp.com/#/edit/85fq9K3x9YXqoJgTQ).

<img src="doc/edit-club-page.JPG" alt="edit club page">

### Add Club Page:

While logged in, you can click on "Add Club" to go to the [Add Club Page](http://manoa-club-hunt.meteorapp.com/#/add) that allows you to add a club to the system.

<img src="doc/add-club-page.JPG" alt="add club page">

## Developer Guide

First, [install Meteor](https://www.meteor.com/install).

Second, go to [https://github.com/manoa-club-hunt/manoa-club-hunt](https://github.com/manoa-club-hunt/manoa-club-hunt), and click the "Clone or download" button to download the GitHub repo to your local file system. Using [GitHub Desktop](https://desktop.github.com/) is the preferred method if you use MacOS or Windows.

Third, cd into the app/ directory of your local copy of the repo, and install third party libraries with:

```
$ meteor npm install

$ npm install react-slideshow-image -S
```

### Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/manoa-club-hunt/manoa-club-hunt/blob/master/app/package.json):

```
$ meteor npm run start
```

The first time you run the application, it will create some default users and club data. Here is the output:

```
make slider with code
```

### Note regarding the "bcrypt warning":

You will also get the following message when you run this application:

```
```

On some operating systems (particularly Windows), installing bcrypt is much more difficult than implied by the above message. Bcrypt is only used in Meteor for password checking, so the performance implications are negligible until your site has very high traffic. You can safely ignore this warning without any problems during initial stages of development.

### Viewing the running app

If all goes well, the Manoa Club Hunt application will appear at [http://localhost:3000](http://localhost:3000). You can login using the credentials in [settings.development.json](https://github.com/manoa-club-hunt/manoa-club-hunt/blob/master/config/settings.development.json), or else register a new account.

## Team Members:
* [Konapiliahi Canaday](https://k-canaday.github.io/), Computer Engineering
* [Xandrew Julian](https://xandrewuh.github.io/), Computer Engineering
* [Ioane Omerod](https://ioaneomerod.github.io/), Computer Science
* [Sun Young Kim](https://sunyoungk.github.io/), Computer Science
