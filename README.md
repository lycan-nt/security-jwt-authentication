# security-jwt-authentication
     Spring Security with JWT authentication
     
 <img src='https://github.com/lycan-nt/security-jwt-authentication/blob/main/login.png'>

  ## Built with
  - 🍃SpringBoot
  - 🍃Java 11
  - 🍃SpringSecurity
  - 🌶Lombok
  - 🔑JWT
  
## Starting
  - Clone or download the project
  - Import the project into your preferred IDE like IntelliJ for example.
  - start the project
  - Use a platform like postman to test routes
  
### API resources
  - URL Base: localhost:8080/
      - Resource Authentication
        - Requisition Type: POST, Route: /login/ 
            (Log in with a username and password that must be sent in the request header.
              KEY: username
              KEY: password
              This implementation uses memory login and the two registered users are:
              user/user
              admin/admin)
              Note: After logging in, a token will be returned in the response header, 
              it must be used in the next requests and lasts for 5 minutes.
        - Requisition Type: GET, Route: /profile/ 
            (This request expects an authentication token)
        - Requisition Type: GET, Route: /admin/ 
            (This request expects an authentication token)
            
## Author
    Felipe D. Santos
    
## License
    MIT
  
