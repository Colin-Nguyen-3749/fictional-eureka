# DCGA Website Prototype

This repo contains the code that I'm going to be using to make a website to help make DCGA meetings go by a bit more smoothly. Here are the things that I want to implement into this website:
1. Attendance Features
- I want people to be able to log into this website so that we can take attendance
- I want to be able to import an Excel spreadsheet that contains all the senators' names to check attendance against
    - Maybe use n8n?
      
2. Voting Features
- Speaker can press a button that displays a vote with the options 'yes', 'no', and 'abstain'
- Each user, once logged in, can vote on their own devices
  
3. Discussions
- Each user can click on a button to raise their hand to make a point
- If multiple people raise their hand, they will be placed in a queue based on the order in which they raised their hand
- When the speaker calls on a person, they will click a button that displays a message on screen that says '<name> is speaking! Please pay attention.' along with a timer indicating how much time the senator has left to speak
- The message will be displayed on everyone's screen except for the speaker
- If people want to respond directly to the senator that just spoke, then they can hit a button to respond
    - If other people are in the queue to speak, the senator who wants to respond to the point that was just made will get priority
    - If multiple people have a response, then just form another queue
- Senators can also react to each other's points in the forms of emojis

  
