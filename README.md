# MERN AI Content Generator 🚀🤖

A full-stack AI content generator application built with the MERN stack (MongoDB, Express, React, Node.js) and integrated with Stripe for secure payment management. The app uses OpenAI's GPT model to generate new content based on user inputs.

## Features ✨
- **Content Generation**: Users can generate new content using OpenAI's GPT model.
- **Stripe Integration**: Secure payment processing and subscription management.
- **User Authentication & Authorization**: Secure user login and account management.
- **Responsive UI**: Built with React to ensure a seamless experience across devices.
- **MVC Architecture**: Organized backend structure for scalability and maintainability.

## Tech Stack ⚙️
- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express, OpenAI's GPT
- **Database**: MongoDB
- **Payment Processing**: Stripe API
- **Authentication**: JWT (JSON Web Tokens)


### Installation 🛠️

1. Clone the repository:
    ```bash
    git clone https://github.com/vatsal-30/openai-content-generator-mern.git
    ```

2. Install dependencies for both frontend and backend:

    **For the backend**:
    ```bash
    cd backend
    npm install
    ```

    **For the frontend**:
    ```bash
    cd frontend
    npm install
    ```

3. Configure your environment variables for both frontend and backend:

    - Backend (`.env`):
      ```env
      PORT=5000
      MONGO_URI=<your_mongo_database_uri>
      STRIPE_SECRET_KEY=<your_stripe_secret_key>
      JWT_SECRET=<your_jwt_secret_key>
      ```

    - Frontend (`.env`):
      ```env
      REACT_APP_API_URL=http://localhost:5000
      ```

4. Start the backend:
    ```bash
    cd backend
    npm start
    ```

5. Start the frontend:
    ```bash
    cd frontend
    npm start
    ```

6. Open the application in your browser at `http://localhost:3000`.

## Usage 🔧
- Sign up or log in to your account. 📝
- Generate new content by providing a prompt to the GPT-powered backend. ✍️
- Manage subscriptions and payments via the Stripe integration. 💳
