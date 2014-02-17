# Learn All The Nodes Episode 14

## Creating User Accounts

[View the episode](http://www.learnallthenodes.com/episodes/14-creating-user-accounts)

We created users by asking them just for an email address.  So, if you knew your friends' email addresses, you could log in, sell their loot at the auction house, and leave them stranded in an unfriendly location.  Perhaps you wouldn't do that to your friends.

Well, apps are serious business, and so we're going to add password protection to the accounts.  The first rule of storing passwords is that you don't store passwords-- you store hashes of those passwords. 

In this episode we show how to use `bcrypt` and tie into Mongoose's middleware stack to slickly handle hashing user passwords.

### Notes

[How to safely store a password](http://codahale.com/how-to-safely-store-a-password/)

[Mongoose statics](http://mongoosejs.com/docs/guide.html#statics)

[bcrypt in Node.js](https://github.com/ncb000gt/node.bcrypt.js/)

[The rule of 3](http://en.wikipedia.org/wiki/Rule_of_three_(computer_programming))
