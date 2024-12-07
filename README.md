# FOOD_ORDER_WEBSITE

A comprehensive **Food Ordering Platform** built using the **MERN Stack**. This project offers an interactive and dynamic user interface, secure authentication, and seamless integration with payment gateways to provide a smooth online food ordering experience.  

## Features  

- **Dynamic User Interface**:  
  Built with **React** to create a responsive, user-friendly, and interactive interface.  

- **Database Management**:  
  **MongoDB** stores data for:  
  - Restaurants  
  - Menus for each restaurant  
  - User details and orders  

- **Backend Services**:  
  - **Node.js** and **Express.js** handle server-side operations.  
  - Routes and APIs enable data retrieval and management efficiently.  

- **Authentication**:  
  - Login and Signup functionality.  
  - Password recovery system using **Mailtrap**, with email sending handled securely through environment variables.  

- **Payment Gateway Integration**:  
  - Implemented using **Stripe** for seamless and secure transactions.  

- **Multi-Page Navigation**:  
  - **Home**  
  - **Sign In**  
  - **Cart**  
  - **My Orders**  

## Installation and Setup  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
2. **Install Dependencies:**
  Navigate to the root, backend, and frontend directories to install dependencies:
  npm install
  cd client
  npm install
3. **Set Up Environment Variables:**
 Create an .env file in the backend directory with the following variables:
 MONGO_URI=your-mongodb-connection-string
 MAILTRAP_USERNAME=your-mailtrap-username
 MAILTRAP_PASSWORD=your-mailtrap-password
 STRIPE_KEY=your-stripe-api-key

4. **Run the Application:**
 Start both frontend and backend servers:
 npm start
 cd client
 npm start

5.**Access the Application:**
  Open http://localhost:3000 in your browser.
