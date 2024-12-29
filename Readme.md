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


#### 1.  Clone the Combined Repo with Submodules using below mentioned command: 
```python
  git clone --recurse-submodules https://github.com/d-aggarwal/EmpowerHer-Combined.git

```


#### 2. EmpowerHerBackEnd Setup - Node.js
  Prerequisites:  Node.js installed


a)  Navigate to the EmpowerHerBackEnd subfolder using command:
```python
  cd EmpowerHer-BackEnd
```


b)  Install dependencies: npm install



c)  Set up environment variables:
  Create a .env file in the root of EmpowerHer-BackEnd repo.
  Add the necessary environment variables:

PORT=your-port-number 

MONGODB_URLL=your-mongodb-url 

CORS_ORIGIN=your-allowed-domains 

ACCESS_TOKEN_SECRET = your-acess-token-secret

ACCESS_TOKEN_EXPIRY = your-acess-token-expiry

REFRESH_TOKEN_SECRET = your-refresh-token-secret

REFRESH_TOKEN_EXPIRY = your-refresh-token-expiry

FLASK_API_URL_STRATEGY= http://localhost:5000

FLASK_API_URL_BUSSI= http://localhost:5001

FLASK_API_URL_NAME= http://localhost:5002

FLASK_API_URL_TIME= http://localhost:5004




d)  Run the backend server:

```python
  npm run dev
```



#### 3.  EmpowerHerFrontEnd Setup - React
  Prerequisites:
  Node.js installed



a)  Navigate to the EmpowerHerFrontEnd subfolder:

```python
  cd EmpowerHerFrontEnd
```


b)  Install dependencies:

```python
  npm install
```


c)  Set up environment variables:
  Create a .env file in the root of your frontend repo.
  Add the necessary environment variables:

```python
  REACT_APP_API_URL=http://localhost:${PORT mentioned in backend env file}
```


d)  Run the frontend app:
```python
  npm start
```



#### 4.  AI Models Repositories Setup - Python

  Each AI model repo contains:
  Python scripts.
  requirements.txt with dependencies.


  For each AI model repo:
a)  Navigate to the AI model subfolder:

```python
  cd ai-model-repo-1
```


b)  Install dependencies:

```python
  pip install -r requirements.txt
```


c)  Set up environment variables:
  Create a .env file in the root of each aimodel repo.
  Add the necessary environment variable:\\

  GEMINI_API_KEY='your-gemini-api-key'\\



d)  Run the Python script:
  Execute the main Python file (marketingstrategy.py or similar) to ensure it runs.

```python
  python marketingstrategy.py
```

  Verify the AI model execution:


####  Check Proper running of website from FrontEnd

###  General Note:
  Environment Variables: Ensure all necessary variables are added to the .env files for all repositories.
