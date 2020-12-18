# Wat Gun Mai

**Wat Gun Mai** is a web application about reviewing temples around the user. The web application comes with these amazing features such as Searching for your temples and viewing their UV, temperatures, reviews on that specifics temple, and the nearest five temples around your temple.

Team Members
---

| Student ID   | Name                         | GitHub                                        |
|--------------|------------------------------|-----------------------------------------------|
| 6110545473   | Chanachida Fuachai           | [llleyelll](https://github.com/llleyelll)     |
| 6110545643   | Sivanat Subpaisarn           | [tiemfah](https://github.com/tiemfah)         |
| 6110545660   | Sirikorn Songsaengthong      | [Sirikonss](https://github.com/Sirikonss)     |
| 6110545783   | Phantakarn Kiatpaisarnsopon  | [wodwine](https://github.com/wodwine)         |
| 6110545678   | Arisa Pangpeng               | [kidstylex](https://github.com/kidstylex)         |

Project setup
---
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
 * run nearby temples  
 `❯ python3 nearby_temple.py` 
 ---
 ### Backend module setup
 * install backend dependencies  
 `❯ cd watgunmai-backend && npm i`  
 * read and finish env.example instruction  
 `❯ cat env.example`  
 * run project  
 `❯ npm start`
 ---
 ### Frontend module setup
 * install dependencies (on another terminal)  
 `❯ cd watgunmai-frontend && npm i` 
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
