# Droply - File Storage Application 📁🚀

Droply is a simple file storage application built with **Next.js**, **Clerk**, **Neon**, **Drizzle**, and **HeroUI**. It allows users to authenticate, upload files, manage files with actions like starring ⭐ and trashing 🗑️, and enjoy a responsive user interface.

## Features 🌟

- **User Authentication:** Secure user authentication managed by **Clerk** 🔑.
- **File Uploads:** Upload images 📸 and other files with **ImageKit**.
- **File Management:** Users can star ⭐ and trash 🗑️ files for easy management.
- **Responsive UI:** Built using **HeroUI** for a modern and responsive interface 📱💻.

## Tech Stack 🛠️

- **Frontend:** Next.js, HeroUI
- **Authentication:** Clerk 🔑
- **Database:** Neon (PostgreSQL) 🗃️
- **ORM:** Drizzle 🌊
- **File Storage:** ImageKit 🖼️

## Screenshots 📸

<img width="941" alt="Droply" src="https://github.com/user-attachments/assets/1ef19253-2675-4d8b-a82b-3d272801f70a" />


## Demo Video 🎥

You can watch a demo of the application here:

[Droply video.zip](https://github.com/user-attachments/files/20106390/Droply.video.zip)
[Droply video 2.zip](https://github.com/user-attachments/files/20106395/Droply.video.2.zip)

*Click the image above to watch the demo video.*

## Getting Started 🚀

### Prerequisites 📋

To run this project locally, you need the following:

- **Node.js 18+** ⚙️
- **npm** (Node Package Manager) 📦
- A **Clerk account** (for user authentication) 🔑
- A **Neon PostgreSQL database** (for data storage) 🗃️
- An **ImageKit account** (for file storage) 🖼️

### Installation 🛠️

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/droply.git
   cd droply

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the root of the project and add the following:

   ```bash
   NEXT_PUBLIC_CLERK_FRONTEND_API=<Your Clerk Frontend API>
   CLERK_API_KEY=<Your Clerk API Key>
   DATABASE_URL=<Your Neon PostgreSQL Database URL>
   IMAGEKIT_PUBLIC_KEY=<Your ImageKit Public Key>
   IMAGEKIT_PRIVATE_KEY=<Your ImageKit Private Key>
   IMAGEKIT_URL_ENDPOINT=<Your ImageKit URL Endpoint>
   ```

4. Run the application locally:

   ```bash
   npm run dev
   ```

   The app will be available at [http://localhost:3000](http://localhost:3000).

## Usage 🧑‍💻

### Authentication 🔑

* Users can **sign up** or **log in** using **Clerk**. The authentication flow is simple and secure.

### File Uploads 📸

* Users can **upload files** through the file upload interface powered by **ImageKit**. Uploading is seamless and efficient.

### File Management 📂

* Users can **star** ⭐ and **trash** 🗑️ files for easy organization and management.

## File Storage and Database Setup 🗄️

1. **Neon (PostgreSQL)** is used to manage and store metadata about files uploaded.
2. **ImageKit** handles the file storage, allowing fast, scalable access to files in the cloud.


## Acknowledgments 

* [Clerk](https://clerk.dev/) for user authentication 🔑
* [ImageKit](https://imagekit.io/) for file storage 🖼️
* [Neon](https://neon.tech/) for PostgreSQL database 🗃️
* [Drizzle](https://drizzle.team/) for ORM 🌊
* [HeroUI](https://heroicons.com/) for UI components 💡

---


