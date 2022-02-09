# Chatty React Application

Build an application using sockets (socket.io) and events.

&nbsp;

## Requirements

- Implement React hooks to handle events
- Scroll to the bottom of the messages list when sending/receiving a message
- Show the initial Chatty message by default
- Build private chats for each account
- Integrate with emojis 3rd
- Attachments can be uploaded by user
- Build the UI components by styled-components
- Use **sockets** to:
  - Send the user's message to Chatty
  - Show a typing message when Chatty is typing
  - Handle incoming Chatty messages and display them

&nbsp;

# Chatty Socket Events

- `bot-typing`: Emitted by Chatty when they are typing in response to a user message.
- `bot-message`: Emitted by Chatty with a message payload in response to a user message.
- `user-message`: Emitted by you/the client with a message payload

&nbsp;

# Message Classes

We've provided `Message` components and classes. Here's some information about the classes.

- `.message--last`: The last message in a group
- `.message--typing`: The message the user sees when the recipient is typing
- `.message--me`: Denotes a user message

&nbsp;

## References

- Socket configuration with the [botty.alexgurr.com](https://botty.alexgurr.com) in config.js
- Chat room [image](./chat-room.jpg)
