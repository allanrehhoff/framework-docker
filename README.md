# Framework Docker

A docker build for my `allanrehhoff/framework` project.  
This project aims to test and verify compaitiblity with nginx webserver.  
But may be compatible with other use case scenarios.  

**To use this project:**
1. `$ git clone --recurse-submodules REPOSITORY-URL`
2. `$ docker-compose up --build`
3. `$ mv .env-sample .env`
4. Modify the newly renamed .env accordingly
5. Happy testing.

**In this stack**  
✅ docker base  
✅ nginx  
✅ PHP-FPM  
✅ MySQL  
