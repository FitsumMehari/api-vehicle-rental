# Update Notification

## Attention Backend Team

Please ensure to update the `README.md` file with details of any new API endpoints you implement. This will help the frontend team to work simultaneously and stay in sync with the backend developments.

### What to Include:
- Endpoint URL
- HTTP Method (GET, POST, PUT, DELETE, etc.)
- Request Parameters
- Response Format
- Any Authentication/Authorization requirements

Thank you for your cooperation!

# Endpoints
- ## For sign up
    ```
        POST /auth/register
    ```

    ### request parameters: 
     - body:
        ```
            {
                "username": "",
                "password": "",
                "email": "",
                "userType": "",
                "securityQuestion": "",
                "securityAnswer": ""
            } 
        
        ```
    ### response format: 
        ```
            {
                "message": "Account Created Successfully!",
                "otherUserInfo": {
                    "username": "",
                    "email": "",
                    "userType": "",
                    "securityQuestion": "",
                    "securityAnswer": "",
                    "_id": "",
                    "createdAt": "",
                    "updatedAt": "",
                    "__v": 0
                }
            }
        ``` 
