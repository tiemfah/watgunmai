# watgunmai
 
 ### Project setup
 * clone project and its submodules   
 `❯ git clone --recurse-submodules https://github.com/tiemfah/watgunmai.git`  
 ---
 ### Scrapper module setup
 * create and run env  
 `❯ python3 -m venv env`
 * install requirements  
 `❯ pip3 install -r requirements.txt`  
 * run scrapper  
 `❯ python3 webscrap.py`  
 ---
 ### Frontend module setup
 * run project  
 `❯ npm start`
 ---
 ### Backend module setup
 * install backend dependencies  
 `❯ cd watgunmai-backend && npm i`  
 * read and finish env.example instruction  
 `❯ cat env.example`  
 * run project  
 `❯ npm start`
---

### Project deployment
You can use any docker supported hosting service for deployment we have included dockerfile for creating docker images.

### Test and CI/CD
Backend API testing can be found in Backend project we use postman collection for testing.
Setting up Jeckins can be use with Node environment then include postman collection for Continuous Integration and select hosting service of your choice for deployment
