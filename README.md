React + Appwrite Blog Platform<br/>
A modern, full-stack blog application built with React for the frontend and Appwrite as the backend-as-a-service. This project supports user authentication, rich text blog post creation, image uploads, and robust CRUD functionality—all wrapped in a clean, responsive UI.
<br/><br/>
🚀 Features<br/>
User Authentication<br/>
Sign up, log in, and log out securely with Appwrite Auth. Authentication state is managed globally using Redux Toolkit.<br/>

Blog Post Management (CRUD)<br/>

Create: Authenticated users can compose posts with titles, rich text content, and featured images.<br/>

Read: All users can browse published posts and view post details.<br/>

Update: Authors can edit their own posts, including updating images.<br/>

Delete: Authors can delete their posts and associated images.<br/>

Rich Text Editing<br/>
Compose posts with formatting and media using TinyMCE.<br/>

Image Uploads<br/>
Upload and preview featured images for posts. Images are managed via Appwrite Storage.<br/>

Protected Routes<br/>
Only authenticated users can access post creation and editing pages.<br/>

Responsive, Component-Based UI<br/>
Built with reusable React components for maintainability.<br/>

🛠️ Tech Stack<br/>

React -	Frontend UI and component logic<br/>
Redux Toolkit -	Global state management (auth, user data)<br/>
React Router -	Client-side routing<br/>
Appwrite -	Authentication, database, storage backend<br/>
TinyMCE - Rich text editing for blog content<br/>
react-hook-form	 - Form handling and validation<br/>
CSS Modules	- Component-scoped styling<br/><br/><br/>

⚙️ Setup & Installation<br/><br/>
Clone the repository<br/>

bash<br/>
git clone https://github.com/yourusername/react-appwrite-blog.git<br/>
cd react-appwrite-blog<br/>
Install dependencies<br/>
<br/><br/>
bash<br/>
npm install<br/>
Configure Appwrite<br/><br/>
<br/><br/>
Create a .env file in the root directory and set:<br/>
<br/>
text
VITE_APPWRITE_URL=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
Set up Appwrite with a Project, Database, Collection, and Storage Bucket.
<br/><br/>
Run the development server
<br/><br/>
bash<br/>
npm run dev<br/><br/><br/>
🧑‍💻 Usage<br/>
Sign Up / Log In:<br/>
Create an account or log in to access post creation features.<br/>
<br/>
Create a Post:<br/>
Use the "Add Post" page to write and publish a new blog post with rich text and an image.<br/>
<br/>
Edit/Delete Posts:<br/>
As the author, you can edit or delete your own posts from the post detail page.<br/>
<br/>
Browse Posts:<br/>
All users can view published posts on the homepage or the "All Posts" page.<br/>
<br/><br/>
🛡️ Authentication & Protected Routes<br/>
Authentication state is checked on app load and stored in Redux.<br/>
<br/>
Protected routes redirect unauthenticated users to the login page.<br/>
<br/>
Only authors can edit or delete their own posts.<br/>
<br/><br/>
📦 Main Components<br/>
Header & Footer: Navigation and branding.<br/>
<br/>
PostCard: Displays post previews.
<br/>
PostForm: Handles post creation and editing.
<br/>
RTE: Rich Text Editor (TinyMCE integration).
<br/>
AuthLayout: Protects routes based on authentication status.
<br/><br/><br/>
📝 Contributing<br/>
Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.<br/><br/>
<br/><br/><br/>
📄 License<br/>
This project is licensed under the MIT License.<br/>
<br/><br/>
