Blogify - Full-Stack Blog Website
Blogify is a feature-rich full-stack blog website that allows users to create, read, update, like, comment and delete blog posts. With a responsive design and robust authentication and authorization functionalities, Blogify provides an excellent platform for bloggers to share their thoughts and ideas with the world. The website also incorporates a categorization feature, enabling users to easily search and filter blog posts based on different categories.
Introduction
Blogify is designed to provide an intuitive and user-friendly platform for bloggers to create, manage, and share their posts. The website is built using Node.js, Express, and MongoDB for the backend infrastructure, while the frontend is developed with Bootstrap and EJS templates for a responsive and interactive user interface. Robust authentication and authorization functionalities are implemented using Passport, ensuring secure access to user-specific features.
Demo
Check out the live demo of Blogify here - https://blogify-eiqv.onrender.com/.
Features
CRUD Operations: Blogify supports all essential CRUD operations (Create, Read, Update, Delete) for blog posts, allowing users to create new posts, view existing ones, update content, and delete unwanted posts.
Categorization: Users can assign categories to their blog posts, making it easier for readers to search and filter posts based on specific interests.
Responsive Design: The website is designed with a responsive layout, ensuring a seamless user experience across various devices.
Authentication and Authorization: Passport is used for multi-user authentication, ensuring that only authorized users can create, update, and delete their own blog posts.
Tech Stack
The following technologies were used to develop Blogify:
  Frontend: Bootstrap, EJS (Embedded JavaScript)
  Backend: Node.js, Express.js, MongoDB
  Authentication: Passport
RESTful APIs
Blogify exposes the following RESTful APIs:
  GET /posts: Get a list of all blog posts.
  GET /posts/:id: Get a specific blog post by ID.
  POST /posts: Create a new blog post.
  PUT /posts/:id: Update an existing blog post by ID.
  DELETE /posts/:id: Delete a blog post by ID.
Authentication and Authorization
Blogify implements user authentication using Passport. Users can sign up for new accounts or log in with their existing credentials. Only authenticated users are authorized to perform CRUD operations on their own blog posts.
Contact
If you have any questions or suggestions, feel free to reach out to our team at Snehanadanwar@gmail.com

Thank you for using Blogify! We hope this platform enhances your blogging experience and facilitates your creative expressions. Happy blogging!
