# PromptHub

PromptHub is a web application that allows users to register, share, and discover prompts. Built with Next.js and MongoDB, it offers Google authentication for a seamless user experience.

## Features

- User registration and authentication (including Google Sign-In)
- Create, read, update, and delete prompts
- Discover prompts shared by other users
- Responsive design for desktop and mobile devices

## Technologies Used

- [Next.js](https://nextjs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Google OAuth](https://developers.google.com/identity/protocols/oauth2)

### Installation
1. Clone the repository:
```
git clone https://github.com/aldinash/prompthub.git
cd prompthub
```
2. Install dependencies
```
npm install
```
3. Create a `.env.local` file in the root directory and add the following variables:
```
MONGODB_URI=your_mongodb_connection_string
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
```
4. Run the server
```
npm run dev
```
