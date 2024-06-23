<div align="center">

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Prisma-black?style=for-the-badge&logoColor=white&logo=Prisma&color=2D3748" alt="prisma" />
    <img src="https://img.shields.io/badge/-MySQL-black?style=for-the-badge&logoColor=white&logo=mysql&color=4479A1" alt="mysql" />
    <img src="https://img.shields.io/badge/-Zod-black?style=for-the-badge&logoColor=white&logo=Zod&color=3068b7" alt="zod" />
    <img src="https://img.shields.io/badge/-Clerk-black?style=for-the-badge&logoColor=white&logo=Clerk&color=000000" alt="clerk" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=007ACC" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Cloudinary-black?style=for-the-badge&logoColor=white&logo=cloudinary&color=3448C5" alt="cloudinary" />
  </div>

  <h3 align="center">Social Media App</h3>

  <h4><a href="https://snapnexus.vercel.app/" target="_blank">Deployed Live Website</a></h4>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🌐 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🚀 [Quick Start](#quick-start)

## <a name="introduction">🌐 Introduction</a>

This Social Media app is built with Next.js and MySQL, using Prisma ORM for database interactions. It provides a robust platform for users to connect, share content, and interact with each other seamlessly.

## <a name="tech-stack">⚙️ Tech Stack</a>

-   Next.js
-   Prisma
-   MySQL
-   Zod
-   Clerk
-   TypeScript
-   Tailwind CSS
-   Cloudinary

## <a name="features">🔋 Features</a>

👉 **User Authentication**: Secure login and registration using social sign-on or traditional email and password methods with Clerk.

👉 **User Profiles**: Create and manage user profiles with customizable avatars and bios.

👉 **Post Creation**: Share updates, images, and videos with the community.

👉 **Commenting and Liking**: Engage with posts through comments and likes.

👉 **Real-time Notifications**: Receive instant notifications for likes, comments, and new followers.

👉 **Media Management**: Upload and manage media files through Cloudinary.

👉 **Responsive Design**: Ensures optimal user experience across devices with a responsive and adaptive design.

👉 **Secure and Scalable**: Built with best practices for security and scalability in mind, ensuring data integrity and privacy.

## <a name="quick-start">🚀 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

-   [Git](https://git-scm.com/)
-   [Node.js](https://nodejs.org/en)
-   [npm](https://npm.io/) (Preferred Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Agamya-Samuel/SnapNexus-SocialMediaApp-NextJS
cd SnapNexus-SocialMediaApp-NextJS
```

**Installation**

Install the project dependencies using npm:

```bash

npm install
```

**Set Up Environment Variables**

Create a new file named .env in the root of your project and add the following content:

```env

# Database
DATABASE_URL="mysql://user:password@localhost:3306/database"

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY=YOUR_CLERK_SECRET_KEY
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_CLOUD_NAME
CLOUDINARY_API_SECRET=YOUR_CLOUDINARY_API_SECRET
CLOUDINARY_UPLOAD_PRESET=YOUR_CLOUDINARY_UPLOAD_PRESET

# Add other necessary environment variables
```

Replace the placeholder values with your actual MySQL, Cloudinary, and Clerk credentials.

**Running the Project**

```bash

npm run dev
```

Open http://localhost:3000 in your browser to view the project.

**Building for Production**

```bash

npm run build
npm start
```

This will start the production server.

**Contributing**

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

**License**

This project is licensed under the MIT License. See the LICENSE file for more information.

```css

Feel free to customize any section further based on the specific details of your project.
```
