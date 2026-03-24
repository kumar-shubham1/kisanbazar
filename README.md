# 🌾 KisanBazar (Customized Version)

KisanBazar is a full-stack web application that connects farmers directly with consumers, eliminating middlemen and enabling fair trade.

This project is a **customized and enhanced version** built for learning and development purposes, with additional improvements and personal modifications.

---

## 💡 Problem Statement

Farmers face several challenges:

- Limited digital presence  
- Dependence on intermediaries  
- Low profit margins  
- Lack of direct consumer trust  

---

## 🚀 My Solution

This platform provides:

- 🌾 Farmer product listings  
- 🛒 Consumer browsing system  
- 💬 Messaging system  
- 📦 Order requests  
- 🔐 Secure authentication  

---

## 🛠️ Tech Stack

- Frontend: React.js, Tailwind CSS, Redux  
- Backend: Node.js, Express.js  
- Database: MongoDB  
- Auth: JWT  

---

## ⚙️ Features

- Farmer Dashboard  
- Consumer Dashboard  
- Product Management  
- Messaging System  
- Role-based Authentication  

---

## 🧑‍💻 My Contributions

- Modified UI/UX  
- Improved backend structure  
- Added/optimized features  
- Configured deployment  
- Fixed bugs and errors  

---

### 🚀 Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/kumar-shubham1/kisanbazar.git
   ```

   `Unzip the File`

2. **Open with VS Code**

   Open the project directory with VS Code or your preferred code editor.

3. **Install Dependencies**

    **Frontend:**

    - Navigate to the frontend directory:

    ```bash
    cd client
    ```

    - Create a `.env` file in the backend directory and add the following environment variables:

    ```env
    VITE_BACKEND_URL = your_backend_url (http://localhost:5000)
    ```

    - Install the dependencies:

    ```bash
    npm install
    ```

    - Run the development server:

    ```bash
    npm run dev
    ```

    **Backend:**

    - Navigate to the backend directory:

    ```bash
    cd api
    ```

    - Create a `.env` file in the client directory and add the following environment variables:

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    JWT_EXPIRE=90d
    ```

    - Install the dependencies:

    ```bash
    npm install
    ```

    - Start the server:

    ```bash
    npm run dev
    ```

4. **Update API URLs**

    Ensure that the API URLs in your frontend code are correctly pointing to your local backend server. Update the `VITE_BACKEND_URL` in the `.env` file (as mentioned in the previous step).

5. **Access the Application**

    After everything is set up:
    - Open your browser and navigate to [http://localhost:5173](http://localhost:5173) to view the application.
    - Ensure the frontend loads correctly and communicates with the backend server.

---

## Live Links

- **Live Web:** 
- **GitHub Repo:** [github.com/kumar-shubham1/kisanbazar](https://github.com/kumar-shubham1/kisanbazar) (Give it a Star!)

## Contact

For any questions, feedback, or collaboration opportunities, feel free to contact me at [shubhamvermaa045@gmail.com](mailto:shubhamvermaa045@gmail.com).


## 📌 Disclaimer

This project is inspired by an existing open-source project and has been significantly modified, improved, and customized for educational and development purposes.


> Built with ❤️ by Shubham 


---