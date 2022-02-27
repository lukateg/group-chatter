# Group chatter

Group chatter is an application made for exchanging messages between two or more persons.

Hosted on - https://group-chatter.netlify.app/

### Usage

For testing the application you can log in with test accounts :

**First account**

*username*: Marco

*password*: 123456


**Seccond account**

*username*: Monica

*password*: 123456

I've decided not to add the sign up button because Chat Engine restricts you with the number of users if you are using the free version, and it could crash the project if each person visiting a website would try to sign up.

After you've had logged in you can:

_-create your group chat_

_-add other users to your chat_

_-delete chats you created_

_-see who is online_

_-chat with people_

_-send images as well as text messages_

_-find sent images in each group_

_-browse chats_

_-log out, and log in as a different user_

## About project

I've had no experience building real-time chat applications, or similar projects, so I've decided that this project could be most interesting for me. Since I had no experience, after googling best ways and practices for this type of project I decided that Chat Engine would suit me better than Firebase setup(those were the two most understandable methods for me).

I've chosen Chat Engine because they are developer friendly, they have plenty of tutorials and demos on their official website, and the documentation is easy for understanding.

### Technology

This project is done using **React**. For the icons, I was using **Ant design** and for styling, it was just **CSS**. **Chat Engine** provided component that can be fully customized, so the main chat is built custom on top of their basic component. For working with data and API I was using **Axios**.
