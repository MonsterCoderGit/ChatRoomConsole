# 🎉 FUNCODE  
**Freedom, Unleashing, Network, Chat. Online, Domain, Encrypted**

FUNCODE is a **fully-featured, encrypted chat system** that runs directly in the browser console — no installations, no bloat. Designed for portability, security, and creativity, it supports real-time messaging, moderation tools, drawing sharing, and rich content like GIFs and Markdown. All backed by a robust client-server model using PeerJS and native browser technologies.

---

## 🚀 Features

### 🧠 Core Chat Functionality
- **Invite-Only Access** via room codes and passwords
- **Encrypted Peer-to-Peer Messaging** using [PeerJS](https://peerjs.com/)
- **Inline Markdown and GIFs**  
- **Persistent Private Messaging** with `/private`
- **Portable** — copy and paste into the browser console to run

### 🛠 Command Suite
| Command                  | Description                                   |
|--------------------------|-----------------------------------------------|
| `/kick <nickname>`       | Kicks a user from the chatroom                |
| `/mute <nickname>`       | Mutes a user                                  |
| `/unmute <nickname>`     | Unmutes a previously muted user               |
| `/list`                  | Lists all current users                       |
| `/clear`                 | Clears your chat view                         |
| `/help`                  | Displays help message                         |
| `/promote <nickname>`    | Grants moderator privileges                   |
| `/demote <nickname>`     | Removes moderator privileges                  |
| `/private <nickname>`    | Sends a private message to a specific user    |
| `/sendDrawing`           | Sends your current drawing to the chatroom    |
| `/changePassword`        | Changes the room's access password            |

---

## 🎨 Drawing Support

FUNCODE includes a built-in **pixel drawing tool** that allows users to sketch and share drawings in chat:

- Choose your color from a palette
- Use the erase tool to undo mistakes
- Save or load drawings as JSON text
- Send drawings with `/sendDrawing`
- Automatically renders shared drawings in connected clients

---

## 🧰 Technologies Used

- **HTML, CSS, JavaScript**
- **[PeerJS](https://peerjs.com/)** — P2P networking
- **[jsDelivr](https://www.jsdelivr.com/)** — CDN for fast client-side loading

---

## 🔐 Access & Hosting

FUNCODE is **invite-only**. To join a room:

1. **Receive the client code** from a trusted source
2. **Paste it into the browser console**
3. **Enter the room code and password**

Server code should be run locally or privately by a trusted host.

---

## 📦 Portability

FUNCODE runs **100% in the browser** — simply copy the client script and paste it into the dev tools console. No installations, extensions, or external setup needed.

---

## 🧑‍💻 Usage Example

```js
// Paste this into your browser's DevTools console to get started:
(async () => {
  // Load FUNCODE from a CDN or local script
  const script = document.createElement('script');
  script.src = 'https://your-hosted-client.js';
  document.body.append(script);
})();
```

## 📎 Notes

- **Admin and moderator powers** are session-based and enforced client-side.
- This project is under **active development** — expect improvements!

---

## 🎉 Special Thanks

Shoutout to everyone experimenting with **decentralized** and **browser-native** tools.  
Keep building fun stuff.
