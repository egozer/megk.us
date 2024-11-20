# Firebase-Based Messaging System with User Authentication

This project is a simple messaging system built with Firebase, where users can log in with a username and PIN to view their messages. Users can send messages without logging in, but only logged-in users can view their own messages. 

## Features

- **User Authentication**: Users log in with a username and a 4-digit PIN.
- **Personalized Messages**: Messages are only visible to the logged-in user.
- **Anonymous Messaging**: Users can send messages without logging in.
- **Firebase Integration**: Uses Firebase Realtime Database for message storage and authentication.

## Demo

### Login Page
- Users enter their username and PIN to log in. 
- Only valid users can access their personalized messages. Invalid credentials will show an error.

### Messaging Page
- Logged-in users can view their personal messages.
- A message input form is available for sending new messages to any user.

## Installation and Setup

### Prerequisites
- [Firebase Account](https://firebase.google.com/)
- Basic understanding of HTML, JavaScript, and Firebase.

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/firebase-messaging-system.git
   cd firebase-messaging-system
