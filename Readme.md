
```markdown
# Project Overview 

#### To make business opportunities accessible and achievable for rural women (specifically considering regional areas of Andhra Pradesh, Telangana) through an AI-powered platform that provides tools, guidance, and resources for entrepreneurial success.

---

## Challenge Description 

The project addresses significant barriers faced by women entrepreneurs in rural India:
- Limited access to business knowledge and resources
- Language barriers in accessing digital business content
- Lack of structured guidance and mentorship
- Limited technology adoption due to complexity
- Insufficient access to business tools and networks

---

## Setup Instructions

### 1. Clone the Combined Repo with Submodules using the below-mentioned command:
```bash
git clone --recurse-submodules https://github.com/d-aggarwal/EmpowerHer-Combined.git
```

---

### 2. EmpowerHerBackEnd Setup - Node.js
**Prerequisites**: Node.js installed

a) Navigate to the EmpowerHerBackEnd subfolder using the command:
```bash
cd EmpowerHer-BackEnd
```

b) Install dependencies:
```bash
npm install
```

c) Set up environment variables:
- Create a `.env` file in the root of the EmpowerHer-BackEnd repo.
- Add the necessary environment variables:
  ```
  PORT=your-port-number
  MONGODB_URL=your-mongodb-url
  CORS_ORIGIN=your-allowed-domains
  ACCESS_TOKEN_SECRET=your-access-token-secret
  ACCESS_TOKEN_EXPIRY=your-access-token-expiry
  REFRESH_TOKEN_SECRET=your-refresh-token-secret
  REFRESH_TOKEN_EXPIRY=your-refresh-token-expiry
  FLASK_API_URL_STRATEGY=http://localhost:5000
  FLASK_API_URL_BUSSI=http://localhost:5001
  FLASK_API_URL_NAME=http://localhost:5002
  FLASK_API_URL_TIME=http://localhost:5004
  ```

d) Run the backend server:
```bash
npm run dev
```

---

### 3. EmpowerHerFrontEnd Setup - React
**Prerequisites**: Node.js installed

a) Navigate to the EmpowerHerFrontEnd subfolder:
```bash
cd EmpowerHerFrontEnd
```

b) Install dependencies:
```bash
npm install
```

c) Set up environment variables:
- Create a `.env` file in the root of your frontend repo.
- Add the necessary environment variables:
  ```
  REACT_APP_API_URL=http://localhost:${PORT mentioned in backend env file}
  ```

d) Run the frontend app:
```bash
npm start
```

---

### 4. AI Models Repositories Setup - Python

Each AI model repo contains:
- Python scripts
- `requirements.txt` with dependencies

For each AI model repo:

a) Navigate to the AI model subfolder:
```bash
cd ai-model-repo-1
```

b) Install dependencies:
```bash
pip install -r requirements.txt
```

c) Set up environment variables:
- Create a `.env` file in the root of each AI model repo.
- Add the necessary environment variable:
  ```
  GEMINI_API_KEY='your-gemini-api-key'
  ```

d) Run the Python script:
- Execute the main Python file (`marketingstrategy.py` or similar) to ensure it runs.
```bash
python marketingstrategy.py
```

Verify the AI model execution.

---

#### Check Proper Running of Website from FrontEnd

### General Note:
- Environment Variables: Ensure all necessary variables are added to the `.env` files for all repositories.

---

## Dependencies List

### Backend Dependencies (Node.js)
- **Node.js** 
- **bcrypt**   
- **cookie-parser**  
- **cors**
- **dotenv** 
- **express**  
- **jsonwebtoken**  
- **mongodb** 
- **mongoose** 
- **mongoose-aggregate-paginate-v2** 
- **multer** 
- **concurrently**
- **nodemon**

---

### Frontend Dependencies
- **Node.js** 
- **@craco/craco**  
- **axios** 
- **body-parser**    
- **cors** 
- **dotenv** 
- **express**   
- **prop-types** 
- **react** 
- **react-dom**  
- **react-helmet**  
- **react-router-dom**  
- **react-scripts**  
- **tailwindcss**

---

### AI Models Dependencies
- **Flask** 
- **flask-cors**  
- **google-generativeai**  
- **python-dotenv**

---

## Usage Examples

EmpowerHer provides tools and resources for rural women to launch and manage businesses effectively. Below are some usage scenarios showcasing the platform's capabilities:

### 1. **Business Strategy Guidance**
- **Scenario**: A woman entrepreneur in a rural area wants to start a small organic farming business.
- **How EmpowerHer Helps**:
  - Recommends strategies based on successful organic farming models.
  - Provides a step-by-step business plan tailored to the local market.
  - Suggests optimal pricing and distribution methods using AI-powered insights.

### 2. **Language-Specific Support**
- **Scenario**: A user prefers to access business resources in Telugu.
- **How EmpowerHer Helps**:
  - Automatically translates key business content into Telugu on one click using Google API.
  - Allows seamless switching between English and Telugu.

### 3. **Simple Technology for Rural Adoption**
- **Scenario**: A group of women wants to start a co-operative dairy farm but has limited technical knowledge.
- **How EmpowerHer Helps**:
  - Simplifies technology adoption with an intuitive user interface.
  - Offers easy-to-use tools for productive sales and financial calculations.

---

## Demo Video

---

## Team Members
- Drishti Agarwal 
- Roshini Nadella
- Modukuri Sanjeev 
- Puligilla Yashwanth 
- Sriya Akepati
```

This follows the typical markdown format for a `README.md` file.