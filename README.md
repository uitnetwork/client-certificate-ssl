#Client Certificate SSL
- Demonstrate client certificate SSL authentication.


#Setup
- Checkout the project
- Execute gradle bootRun to run the project

#Verify
###Without Client SSL import
- Navigate to: https://127.0.0.1:8080/
- Should get *ERR_BAD_SSL_CLIENT_AUTH_CERT* error
###With Client SSL import
- Import src/main/resources/client.p12 into browser
- Navigate to Navigate to: https://127.0.0.1:8080/
- Select the imported key as client certificate ssl authentication
- Verify to get **Demo Client Certificate SSL** response

