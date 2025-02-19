
# RestSphere
🚀 RestSphere - A Full-Stack Web Application


## 🌐 Project Overview
RestSphere is a feature-rich full-stack web application developed using the **MERN** stack (MongoDB, Express.js, Node.js). It allows users to list, review, and manage rental properties, incorporating interactive maps and secure authentication mechanisms.
## 🖼️ Sample Screenshot
![RestSphere UI](https://github.com/user-attachments/assets/b00c1da5-d599-4f77-8f42-3c385b642fd0)


## 🛠️ Technologies & Packages Used
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB (Mongoose for Object Modeling)
  - Passport.js (Authentication)
  - Dotenv (Environment Variables)
  - Express Session (Session Management)
  - Connect Flash (Flash Messages)
  - Connect Mongo (Session Storage)
  - Cookie Parser (Cookie Handling)
  - Joi (Data Validation)

- **Frontend:**
  - EJS (Template Rendering)
  - Bootstrap (Styling)

- **Additional Tools:**
  - Multer (File Uploads)
  - Cloudinary (Image Storage)
  - Mapbox (Interactive Maps)
  - Passport Local & Passport Local Mongoose (User Authentication)



## 🌟 Key Features
- **User Authentication:**
  - Secure login/logout system
  - User profile management
- **CRUD Operations:**
  - Add, edit, and delete property listings
- **Review System:**
  - Users can add and delete reviews
- **Account Management:**
  - Update account details & change passwords
- **Data Security:**
  - Password hashing and encryption for user data
- **Interactive Maps:**
  - Mapbox integration for location visualization



## 🛠 Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB (local or cloud-based like MongoDB Atlas)

### Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/h4rshgithub/RestSphere.git
   cd RestSphere
   ```
2. **Install Dependencies**
   ```sh
   npm install
   ```
3. **Set Up Environment Variables**
   - Create a `.env` file in the root directory
   - Add the following variables:
     ```env
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     MAPBOX_TOKEN=your_mapbox_token
     SESSION_SECRET=your_secret_key
     ```
4. **Start the Development Server**
   ```sh
   node app.js
   ```
5. **Visit the Application**
   Open [http://localhost:8080](http://localhost:8080) in your browser.
    ## 📂 Project Structure
```
RestSphere/
│── models/          # Mongoose schemas
│── public/          # Static assets (CSS, JS, Images)
│── routes/          # Express.js routes
│── views/           # EJS templates
│── app.js           # Main application file
│── package.json     # Project dependencies
│── .env             # Environment variables
```
## 🚧 Challenges & Solutions
1. **Data Handling Issues:**
   - Implemented structured API endpoints and efficient query handling.
2. **Scalability Concerns:**
   - Designed a well-architected backend for future scalability.
3. **Image Storage Optimization:**
   - Used Cloudinary for optimized cloud-based image storage.
4. **Session & Authentication Handling:**
   - Integrated Passport.js with Express Session and Connect Mongo.

## 💡 Future Enhancements
- Implement booking functionality
- Add payment gateway integration
- Improve UI/UX with React frontend
- Add an admin panel for property approvals
## 📩 Contact
For any inquiries or feedback, reach out at:

📧 Email: 7shivamjeethakur@gmail.com

🔗 GitHub: [shivamThakur-12](https://github.com/shivamThakur-12)
