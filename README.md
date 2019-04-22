# MongoDB Community Slack

## Guidance for Building Community with Slack (mongo-db.slack.com) 

The MongoDB Community is as hu**mongo**us as the database itself. There are over 13,000+ customers in more than 100 countries around the world. We experience over 30,000 downloads of the software each and every day. We have over 45,000 MongoDB User Group Members in 20 Countries around the world. Online channels for engaging with the community include [Meetups](https://www.meetup.com/pro/mongodb), Social Media such as [Twitter](http://twitter.com/mongodb), [Instagram](http://instagram.com/mongodb), and [Facebook](http://facebook.com/mongodb) and more recently, the [community Slack workspace](http://mongo-db.slack.com).

This Slack instance is now populated by approximately 3,000 community members. While not all of these members are active, they represent a significant number of potential developers and community members.


## How do I join? Who can join?

The Community Slack instance for MongoDB is online at [http://mongo-db.slack.com](http://mongo-db.slack.com). To register, visit [http://launchpass.com/mongo-db](http://launchpass.com/mongo-db).  Anyone can join this community Slack instance.


## How do I get involved?

*   Join the Slack instance. 
    *   Visit [http://launchpass.com/mongo-db](http://launchpass.com/mongo-db). Once you register, you’ll receive an email with instructions for logging in.
*   Visit the **#intros** channel and introduce yourself. 
    *   _Hi, my name is Michael and I’m a Developer Advocate for MongoDB. I’m looking forward to interacting with you all!_
*   Update your profile.  Be sure to fill in “What I do” and add a profile photo.
*   Review the list of channels. There are channels specific to topics such as Meetup groups and product-specific channels such as #stitch, #atlas, #compass, etc.
*   Look for opportunities to interact with the other community members. Ask, and answer questions.
    *   Visit the **#questions** channel and help to answer community members’ questions. 
    *   Visit the product-aligned channels such as #atlas, #stitch, #mongodb-mobile, and #compass.


## Can I use the Slack workspace to get official MongoDB support?

No. The Slack instance belongs to the community. It is not an official support channel. The MongoDB Developer Relations team are stewards of the Slack instance and help to welcome and guide users, but the instance is not an official support mechanism.  That said, there are MongoDB employees that frequently visit the channels and answer questions. This should not be confused with a formal support option, however.

## Using Slack Best Practice

As the number of community members grows, the importance of maintaining good Slack practice also grows. Use these tips to ensure effective use of the workspace.

### Find the right channel for your message or question

To ask a question of the community, first decide whether the question is specific to a product or would be best served in a single channel related to a product. When asking about MongoDB Atlas, for example, place the question in #atlas. Stitch questions should go in #stitch, for example.

### Use Threads

When responding to a community member’s question or comment, **start a thread** rather than a new message. Threads let you respond directly to a message in a channel, keeping the replies, images, and other files organized neatly in a single, threaded conversation. Threaded replies and their files stay connected to the original message, and only those who have contributed to or are following the thread will be notified. Threads enable you to:

*   Tie your thoughts and feedback to a specific message or file.
*   Encourage open discussion without distracting others.
*   Organize conversations and preserve a meaningful context.


### Avoid Cross-Posting

Cross-posting is the practice of posting a question or a topic in multiple channels at once. This can frustrate users that belong to multiple channels. Find the best, most suitable channel for your question or topic and place it there. If you don’t get a response, consider searching the [MongoDB User Discussion Forum](https://groups.google.com/forum/#!forum/mongodb-user) or other support outlets.


### Search Before You Post

A limitation of the free version of Slack we have in place is that only the last 10,000 messages are available. That said, if you have a question, you may find that it’s been recently asked and you may find an answer right away using the search feature.

### Wrap Code Examples in Backticks

Wrapping your code in backticks (\`) will ensure that it is presented as a code sample. This makes it easier to read and enables people to copy/paste.  Enclosing text in backticks causes the text to be presented in the slack message as a code block.

#### Here's an example
```
exports = function(payload) {
  const mongodb = context.services.get("mongodb-atlas");
  const mycollection = mongodb.db("hackathon").collection("contacts");
  return mycollection.find({}).toArray();
};
```

## Code of Conduct

Please keep our community code of conduct in mind when responding to or engaging with any community member in Slack or in any social channel.  See [https://www.mongodb.com/community-code-of-conduct](https://www.mongodb.com/community-code-of-conduct) for more information.  The Developer Advocacy team members have administrative privileges on the Slack instance. If you should encounter a community member acting in conflict with our Code of Conduct (see CoC section of this document), please notify community-conduct@mongodb.com. 
