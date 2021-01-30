## QProfile
###This is my portfolio that I worked on as a part of Crio.do CWOD event. 
I wanna thank the [Crio.do](https://www.crio.do/) for this opportunity. 

---

### Portfolio-Frontend 
The Frontend is built using HTML5, CSS, ReactJS and Gatsby and is deployed to Netlify. 
It interacts with the github site to fetch the profile owner’s projects using REST API.

#### Deployment
1. You need to create a netlify account and then follow the commands below in your terminal to deploy:

2. `netlify login` - Used to login to netify account

3. `netlify deploy --dir=public --prod` - Used to deploy the app. 
---

### Portfolio-Backend
The Backend is built using ExpressJS and is deployed to Heroku. 
It interacts with the Frontend using REST API and stores the contact details sent from the Frontend in a Database.


#### Deployment

1. You need to create an app on your heroku account.
2. After that use the folowing steps : 

* `heroku login -i` - Used to login to the heroku account. 
* *heroku plugins:install heroku-builds* - Install the heroku extension needed for the build. 
* `heroku builds:create -a <name_of_your_app>`  - For building and deploying the app to your heroku account.

---

