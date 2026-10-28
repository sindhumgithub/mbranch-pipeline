This project is mainly microservice with Multibranch pipeline project which consists of multiple services like: 1. Frontend 2. Product Page 3. Suggestions 4. Cart 5. Currency 6. Payments 7. Receving Mail

Frontend code is maintained in frontend branch Product Page is maintained in product page branch Suggestions are maintained in Suggestion branch Cart is maintained in cart branch Currency is maintained in currency branch Payments is maintained in payment branch Receving Mail is maintained in email branch

The Project Workflow is: Pull the Code from github repo --> Create Dockerfile --> Docker Image --> Push to DockerHub/Docker Registry To perform the same steps for all above services I need to use Multi Branch Pipeline