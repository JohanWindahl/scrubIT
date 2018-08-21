# Scrubit
The main part of the project in the course Platform-Spanning Systems - 1DL620

A [Webapp](https://scrubit.herokuapp.com/) for our local kiosk Skrubben.

### Tools
- Customer application: React, React Native.
- [Admin application](https://github.com/JohanWindahl/scrubIT-JavaClient): Java, Java FX. 
- Database management: Mongo DB, mLab.
- Server side: Node js.
- Cloud service: Heroku.
- External API: Swish API. 

**Details:** The organization IT-sektionen at Uppsala University runs a venue for mostly IT-students, but also other students at the university. It is called Skrubben. There, students socialize, study and are provided with snacks. For buying the snacks, we created a web-shop, called Scrubit. 

With Scrubit, one simply choses the goods he/she wants to buy and gets redirected to the payment application Swish, with all information pre-filled. Separate from the web-shop, Scrubit also provides an admin application. The board of IT-sektionen are the only ones that has access to it. From there, they can insert, update and delete items in the web-shop. 

The purpose of Scrubit is to make the shopping in Skrubben more efficient. The application also strengthens the status of IT-sektionen outwards. 



### Snapshot of the webstore:

![dm](https://github.com/JohanWindahl/scrubIT-JavaClient/blob/master/img/store1.png)
![dm](https://github.com/JohanWindahl/scrubIT-JavaClient/blob/master/img/store2.png)

### Installing

Download or clone the project and follow the steps bellow. Make sure node and npm are installed:

First, you have to install all dependencies:

```
npm install
```
### Run

Start the server:

```
NODE_ENV=production node server/server.js
```


