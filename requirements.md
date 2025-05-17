# Airbnb Clone Backend - Feature Requirements

This document outlines the detailed backend specifications for key features of the Airbnb Clone project.


## 1. User Authentication

###  Feature Overview:
Enable users to register, log in, and securely manage their sessions using JWT.

###  Endpoints:
# Method 
- POST  
- POST
- GET
- PATCH

# Endpoint  
- /api/auth/register
- /api/auth/login
- /api/auth/profile
- /api/auth/profile

# Description 
- Register a new user
- Log in an existing user
- Get current user profile
- Update user profile 



### Input / Output:

#### POST `/api/auth/register`
- **Input (JSON)**:
```json
{
  "name": "Thato",
  "email": "thato53@gmail.com",
  "password": "123pass",
}
