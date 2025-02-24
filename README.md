# Wanderlust - Hotel Listing Platform


## 📌 About the Project
Wanderlust is a **full-stack hotel listing platform** that allows users to **browse, add, update, and manage hotels** with an interactive and user-friendly interface. The platform ensures a seamless experience with **secure authentication, image uploads, and dynamic rendering**.

## 🚀 Features

- 🔐 **User Authentication**: Secure login, sign-up, and logout using **Passport.js**
- 🏨 **Hotel Management**: Users can **add, update, and delete** hotels
- 📷 **Image Uploads**: Integrated **Cloudinary** for secure storage
- 🔍 **Search & Filter**: Easily find hotels based on different criteria
- 🎨 **Dynamic UI**: Built using **EJS & Bootstrap** for an interactive experience

## 🛠️ Tech Stack

- **Frontend:** EJS (Embedded JavaScript), Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Passport.js (Session-based)
- **File Storage:** Cloudinary
- **Deployment:** Render (for backend)

## 🏗️ Installation & Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/MohdAahil01/Major_Project.git
   cd Major_Project
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Set up environment variables**
   - Create a `.env` file in the root directory and add the following:
     ```env
     PORT=3000
     MONGO_URI=your_mongodb_connection_string
     CLOUDINARY_CLOUD_NAME=your_cloudinary_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     SESSION_SECRET=your_secret_key
     ```

4. **Run the application**
   ```sh
   npm start
   ```

5. **Open the app in your browser**
   ```
   http://localhost:3000
   ```

## 📸 Screenshots
_(Add screenshots of your project here to showcase UI & features)_

## 🌍 Live Demo
https://major-project-duug.onrender.com/listings

## 🤝 Contributing
Contributions are welcome! Feel free to **fork**, make improvements, and submit a PR.

## 📜 License
This project is licensed under the **MIT License**.

---
🚀 **Developed by [Mohd Aahil](https://github.com/MohdAahil01)**
