# Vartalap — Real-Time Chat Application 

**Vartalap** is a full-stack, real-time chat application built with the **MERN stack** (MongoDB, Express, React, Node.js) and powered by **Socket.IO** for seamless, bi-directional communication.  
It combines a **dynamic multi-theme interface** with modern technologies like **Tailwind CSS** and **DaisyUI**, offering users a fast, responsive, and customizable chatting experience.

---

## Features

- **Real-Time Messaging:**  
  Experience instant message delivery and live updates between users through **Socket.IO**.

- **User Authentication:**  
  Secure login and registration flow using **JWT (JSON Web Tokens)** for robust session management.

- **Dynamic Themes:**  
  The app’s standout feature — users can **instantly switch between multiple vibrant color themes**, transforming the entire UI's appearance in real time.  
  Built using **Tailwind CSS** and **DaisyUI**, this functionality allows everyone to personalize their chat interface according to their mood or style.

- **Private & Group Chats:**  
  Create personal one-on-one conversations or group discussions for teams and communities.

- **Responsive Design:**  
  Fully mobile-friendly and adaptive interface, ensuring an optimal experience across devices and screen sizes.

- **Cloud Integration:**  
  Images and other media files are uploaded and served through **Cloudinary**, ensuring fast and reliable content delivery.

---

## Technologies Used

### **Frontend**
- **React.js** — For dynamic and component-driven UI  
- **Tailwind CSS** — For a sleek, responsive, and utility-first design  
- **DaisyUI** — For elegant, pre-styled, and easily themeable components  
- **React Hooks** — For efficient state and lifecycle management  

### **Backend**
- **Node.js & Express.js** — For API handling and server-side logic  
- **Socket.IO** — For real-time, event-based communication  
- **MongoDB** — For storing users, messages, and chat history  
- **Cloudinary** — For image and file storage  

### **Authentication**
- **JWT (JSON Web Tokens)** — For secure authentication and authorization

### **Deployment**
- Hosted on [Render](https://render.com/)

---

##  Setup Instructions

### **1. Configure Environment Variables**
Create a `.env` file in the project root and add the following values:

```bash
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```
**2. Build the App**
```bash
npm run build
```

**3. Start the Server**
```bash
npm run dev
```

### live Demo - >
Vartalap[https://vartalap-fullsatck-chat-app.onrender.com/login]
