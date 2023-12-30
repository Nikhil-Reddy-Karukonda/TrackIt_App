## 🚀 TrackIt_App

Instructions for setting up the project locally.

### 📋 Prerequisites

- **Node.js** - [Download & Install Node.js](https://nodejs.org/en/download/)

### 🛠 Installation

Follow these step-by-step instructions to set up your development environment:

1. **Clone the Repository**
    ```bash
    git clone git@github.com:Nikhil-Reddy-Karukonda/TrackIt_App.git
    ```

2. **Navigate to the Backend Directory**
    ```bash
    cd TrackIt_App/trackIt-app-backend
    ```

3. **Install NPM Packages**
    ```bash
    npm install
    ```

4. **Set Up Environment Variables**
    - Create a `.env` file in the `trackIt-app-backend` directory.
    - Add the following environment variables:
        ```plaintext
        PORT=your_port_number
        CORS_ENABLED_ORIGIN=your_cors_enabled_origin
        MONGO_URL=your_mongo_db_url
        JWT_SECRET=your_jwt_secret
        TEST_EMAIL=your_test_email
        USER_EMAIL=your_user_email
        USER_PASSWORD=your_user_password
        OTP_SECRET_KEY=your_otp_secret_key
        ```

### ▶️ Running the Application

To start the application, run the following command in the `trackIt-app-backend` directory:

```bash
npm start
