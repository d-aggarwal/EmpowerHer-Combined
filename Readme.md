# Project overview 

#### To make business opportunities accessible and achievable for rural women (specifically considering regional areas of Andhra Pradesh, Telangana) through an AI-powered platform that provides tools, guidance, and resources for entrepreneurial success.


## Challenge Description 

 The project addresses significant barriers faced by women entrepreneurs in rural India:
 Limited access to business knowledge and resources
 Language barriers in accessing digital business content
 Lack of structured guidance and mentorship
 Limited technology adoption due to complexity
 Insufficient access to business tools and networks


## Setup Instructions


#### 1. Clone the Combined Repo with Submodules using below mentioned command - 
git clone --recurse-submodules https://github.com/d-aggarwal/EmpowerHer-Combined.git

#### 2. EmpowerHerBackEnd Setup - Node.js
Prerequisites:
Node.js installed

Steps:
Navigate to the EmpowerHerBackEnd subfolder using command:
cd backend-repo

Install dependencies:
npm install

Set up environment variables:
Create a .env file in the root of EmpowerHer-BackEnd repo.
Add the necessary environment variables:

PORT=your-port-number
DATABASE_URL=your-database-url
API_KEY=your-api-key
Run the backend server:

bash
Copy code
npm run dev
Verify the backend:

Open your browser and visit: http://localhost:your-port-number to ensure the backend is running.
3. Frontend Repo Setup - React
Prerequisites:
Node.js installed (version 14 or higher).
Ensure you have a .env file in the frontend repo with the required environment variables.
Steps:
Navigate to the frontend repo subfolder:

bash
Copy code
cd frontend-repo
Install dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env file in the root of your frontend repo.
Add the necessary environment variables:
env
Copy code
REACT_APP_API_BASE_URL=https://api.your-service.com
Run the frontend app:

bash
Copy code
npm start
Verify the frontend:

Open your browser and visit: http://localhost:3000 to ensure the frontend is running.
4. AI Models Repositories Setup - Python
Each AI model repo contains:

Python scripts.
requirements.txt with dependencies.
For each AI model repo:

Navigate to the AI model subfolder:

bash
Copy code
cd ai-model-repo-1
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Python script:

Execute the main Python file (main.py or similar) to ensure it runs.
bash
Copy code
python main.py
Verify the AI model execution:

Run any provided test or validation scripts to ensure the model works as expected.
General Notes:
Environment Variables: Ensure all necessary variables are added to the .env files for backend and frontend.
Cross-referencing APIs: Ensure the backend and frontend API URLs are properly linked.
Testing: Test each component independently to ensure there are no conflicts.