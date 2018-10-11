# Hej
Interactive question and answers webapplication to ease the start of digital media bremens study program.

## How to collaborate on Hej

If you want to fix a bug or add functionality to hej, these are the steps to follow.

### install locally (Mac OSX)

You need to have npm installed. if not do `brew install npm`. If you dont have brew installed [have a look here](https://docs.brew.sh/Installation.html)

then do:
```
git clone https://github.com/digitalmediabremen/hej.git
npm install
npm start
```

This should install and start a local development server accessible at [localhost:3000](http://localhost:3000)

### deploy to live server

After you have checked for errors in your local environment do `npm run deploy` to push the latest code to the server.
Be aware that you will be asked for credentials and therefore need to have a surge.sh account with rights to publish to hej.digital. contact hi@leonat.de to get access.

## How to use Hej

move over to the issues tab in this github project. 
the web app fetches all questions with the designated label and creates new ones.

### tags

tags are important to structure content but in our case also to attach meta information. 
tags starting with a dot eg `.public` are meta tags, all other tags actually structure content visible to the user

there are two static labels, `master` and `bachelor`. as we are adressing questions in two languages we decided to split content in half. so also attach either one of those tags.

other meta tags are `.pinned` which pins a post to the top and tags starting with `.slug-` which makes a direct link in our tool possible. eg. `.slug-schedule` maps to `hej.digital/schedule`. please only use this meta-tag on special occasions and really important posts.


