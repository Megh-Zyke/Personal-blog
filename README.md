# Personal-blog

This is a Personal Blog which is made using EJS and node modules. MongoDB Database has been used to store the data.

The Blog runs dynamically on server 3000, and all the links are run dynamically by rendering the EJS file as per the needed requirements.

The node modules imported and used in this project are:
* npm init
* mongoose
* express

npm init <initializer> can be used to set up a new or existing npm package.

initializer in this case is an npm package named create-<initializer>, which will be installed by npx, and then have its main bin executed -- presumably creating or updating package.json and running any other initialization-related operation

 - - - -
 ### Mongoose ###

 Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.
 The database present in the website is *postDB* and has one collection called *posts*.

 The schema of the *postDB* database is as follows:

       const postSchema = new mongoose.Schema({
  
        title:String,
        postBody:String
      })


  The title stores the title of the blog and the postBody stores the data you have entered.

   - - - -

   ### EJS ###

There are a total of 5 views:
* Home Page
* Contact Page
* Post Page
* Compose Page
* About Page


#### Home Page #### 
*The homepage is the first page the user interacts when he runs the application. It has a annectode of the blog which you have entered and an extension which is the link to the entire Blog Post.*

#### Compose Page ####
*By redirecting to the compose page, the user has access to his blog entries. The user can enter the title and the description which when submitted will push the data into the databse and then redirected to thte homepage which is then rendered to update the home page*
  - - - -
  
## *Pictures* ##

#### Home Page ####
![Home Page](https://github.com/Megh-Zyke/Personal-blog/blob/main/Pictures/Home%20Page.jpg)


#### About Page ####
![About Page](https://github.com/Megh-Zyke/Personal-blog/blob/main/Pictures/About%20Page.jpg)


#### Compose Page ####
![Compose Page](https://github.com/Megh-Zyke/Personal-blog/blob/main/Pictures/compose.jpg)

#### Post Page ####
![Post Page](https://github.com/Megh-Zyke/Personal-blog/blob/main/Pictures/Naruto.jpg)




##### MongoDB Server #####
![MongoDB Server](https://github.com/Megh-Zyke/Personal-blog/blob/main/Pictures/MongoDB.jpg)
