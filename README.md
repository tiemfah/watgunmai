


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
### Project requirements and tools
 - [Frontend project requirement](https://github.com/tiemfah/watgunmai-frontend/blob/main/package.json)
 - [Backend project requirement](https://github.com/tiemfah/watgunmai-backend/blob/main/package.json)
 - [Scrapper project requirement](https://github.com/tiemfah/watgunmai-scrapper/blob/main/requirements.txt)
---

### Project deployment guide
You can use any docker supported hosting service for deployment we have included dockerfile for creating docker images.

---

### Project CI/CD setup guide
Backend API testing can be found in Backend project we use postman collection for testing.
Setting up Jeckins can be use with Node environment then include postman collection for Continuous Integration and select hosting service of your choice for deployment

---

### Project specification and design document

 - Technologies used
	 - Node.js with express for server API
	 - React for frontend and data visualization
	 - MongoDB atlas
	 - Google Authentication service
	 - Google Place API
	 - Jenkins for CI/CD
	 - Swagger for API documentation
	 - Postman for API testing 
	 - Python3 with Beautiful soup 4 for web scrapping
 - System Architecture
	 - Backend
		 - 3 routes for each resource
			 - `/users`
			 - `/temples`
			 - `/reviews`
	 - Frontend
		 - 3 pages
			 - landing page with search box
			 - search result page with multiple possible dynamic links
			 - detail page for specifics temple
	 - Data model
		 - [Temple](https://github.com/tiemfah/watgunmai-backend/blob/main/models/temple.js)
		 - [User](https://github.com/tiemfah/watgunmai-backend/blob/main/models/user.js)
		 - [Review](https://github.com/tiemfah/watgunmai-backend/blob/main/models/review.js)
 
 ---
