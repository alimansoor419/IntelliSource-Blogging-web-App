# IntelliSource-Blogging-web-App
It is a Blogging website with an integrated Recommender system which recommend users with blogs of their interests.  It has attractive, Responsive and User-friendly interface.
Certainly! Below is a comprehensive README file template for your IntelliSource project, including setup instructions:
##Features
- **Recommender System**: Utilizes Python, pandas, scikit-learn, and scipy to recommend personalized content to users.
- **Backend**: Developed using Node.js, Express.js, MongoDB, Mongoose, and hosted on MongoDB Atlas.
- **APIs**: RESTful APIs implemented with Flask for the recommender system and Node.js for the backend.
- **Frontend**: Built with React.js to provide a responsive and dynamic user interface.

## Technologies Used

- **Python Libraries**: pandas, scikit-learn, scipy
- **Backend Technologies**: Node.js, Express.js, MongoDB, Mongoose
- **API Development**: Flask (Python), Express.js (Node.js)
- **Frontend Framework**: React.js

## Setup Instructions

To run IntelliSource locally, follow these steps:

### Prerequisites

- Node.js and npm installed globally on your machine.
- Python 3.x installed with pip package manager.
- MongoDB installed locally or access to MongoDB Atlas account.

### Backend Setup

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd intellisource-backend
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory of `intellisource-backend` and add the following:

   ```plaintext
   PORT=3000
   MONGODB_URI=<your-mongodb-uri>
   ```

   Replace `<your-mongodb-uri>` with your MongoDB connection string.

4. **Run the server**:

   ```bash
   npm start
   ```

   This will start the backend server at `http://localhost:3000`.

### Frontend Setup

1. **Navigate to the frontend directory**:

   ```bash
   cd intellisource-frontend
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Run the frontend**:

   ```bash
   npm start
   ```

   This will start the React development server at `http://localhost:3000`.

### Running the Recommender System API

1. **Navigate to the recommender system directory**:

   ```bash
   cd intellisource-recommender
   ```

2. **Install Python dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask server**:

   ```bash
   python app.py
   ```

   This will start the recommender system API at `http://localhost:5000`.

## Usage

- Access the IntelliSource frontend at `http://localhost:3000` in your web browser.
