# Sample-Chat

Create a basic chatroom app using Meteor.

---

## What to do:
If you're new to Meteor, you may want to get started with the first few steps of the official [Meteor Tutorial](https://www.meteor.com/tutorials/blaze/creating-an-app)

Useful resources:
- The official [Meteor Tutorial](https://www.meteor.com/tutorials/blaze/creating-an-app)
- The [Meteor Docs](http://docs.meteor.com/#/full/)
- The [Meteor Guide](http://guide.meteor.com/) (This is new, and a work in progress)
- Examples of this project from [around the internets](https://www.google.com/search?hl=en&safe=off&tbo=d&sclient=psy-ab&q=meteor+chat+app)

Goals:
- Display a form with an input
- On submit, insert the contents of the input (the message) as a document into a [Collection](http://docs.meteor.com/#/full/mongo_collection)
- Display a list of the messages stored in the database
- Add the [accounts-password](https://atmospherejs.com/meteor/accounts-password) and [accounts-ui](https://atmospherejs.com/meteor/accounts-ui) packages to your project to allow users to create accounts
- When submitting a message, save the username of the currently logged in user user along with the message
- Display associated username next to each message in the message list
- Deploy your app to `<appnamegoeshere>.meteor.com` using `meteor deploy <appnamegoeshere>`

Stretch goals:
- Remove the `autopublish` and `insecure` packages, and get your app working again
- Add multiple chat rooms (try using a router like `kadira:flow-router`)
- Use the `check` package to validate input [docs](http://docs.meteor.com/#/full/check)

---

## Issues Trackable Here
https://huboard.com/MeteorBurlington/Sample-Chat/
