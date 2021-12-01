# www.skillz.co.uk

**[View the live project here.](https://)**

------

## Index

- \1. User experience (UX)
  - [1.1. Project goals](https://)
  - [1.2 User stories](https://)
  - [1.3 Design](https://)
  - [1.4 Information architecture](https://)
  - [1.5 Mockup designs](https://)
- \2. Features
  - [2.1 Existing features](https://)
  - [2.2 Features left to implement in the future](https://)
- [3. Technologies used](https://)
- [4. Testing](https://)
- [5. Deployment](https://)
- [6. Credits](https://)
- [7. Acknowledge](https://)
- [8. Disclaimer](https://)

------



# 1. User experience (UX)

### 1.1 Project goals

- Making a full-stack site that allows users to manage a common dataset about a particular domain.
- Making a full-stack site that uses HTML, CSS, JavaScript, Python+Flask and MongoDB.
- To design and build a candidate searchable database for businesses to identify potential new Employees for their open positions.
- To utilize python, flask, mongodb, heroku, and other appropriate development technology. 
- To make a visually pleasing experience for both candidates and businesses.
- Includes easy to use registry and profile page to hold the correct amount of information so the search criteria is accurate. 

### 1.2 User stories

**Visitor goals:**



**Member goals:**



**Admin goals:**



### 1.3 Design

- #### Colour scheme

- #### Fonts

- #### Icons

- #### Images

- #### Defensive design

- #### Interactive design

  - The website has to be easy to navigate.
  - The user can quickly find the information he/she wants to find.

### 1.4 Information architecture

### 1.5 Mock-up designs

# 2. Features

### 2.1 Existing features

#### 1. Design

- An attractive and simple layout with consistency.
- Simple navigation throughout the website by using the navigation bar.
- Showing the recipes .simple and clearly

#### 2. General

- 

#### 3. Developer profiles

- 

#### 4. Signup, login and logout

- 

### 2.2 Features left to implement in the future

- 

# 3. Technologies used

#### Languages used

- HTML5
  - HTML5 provides the structure and the content for my project.
- CSS3
  - CSS3 provides the style of the HTML5 elements.
- jQuery
  - jQuery used as the JavaScript functionality.
- Python
  - Python provides the backend of the project.

#### Frameworks, libraries & Other

- Gitpod
  - The GitPod is used to develop the project.
- Git
  - The Git was used for version control to commit to Git and push to GitHub.
- GitHub
  - The GitHub is used to host the project.
- Google Fonts
  - Google Fonts is used to provide the font for the text that is used in the project.
- Materialize
  - Materialize is used for the design framework.
- MongoDB
  - MongoDB is the fully managed cloud database service used for the project.
- Heroku
  - Heroki is the cloud platform to deploying the app.
- Flask
  - Flask is the web framework used to provide libraries, tools and technologies for the app.
- Jinja
  - Jinja is used for templating Python
- Werkzeug
  - Werkzeug is used for password hashing and authentication and authorization.

#### Testing tools used

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/open) is used to detect problems and test responsiveness.
- W3C Markup Validation Service
  - The W3C Markup Validation Service is used to check whether there were any errors in the HTML5 code.
- W3C CSS validator
  - The W3C CSS validator is used to check whether there were any errors in the CSS3 code.

# 4. Testing

The testing process can be found [here](https://)

# 5. Deployment

#### Requirements

- Python3
- Github account
- MongoDB account
- Heroku account

#### Clone the project

- To make a local clone, follow the following steps.
- Log in to GitHub and go to the repository.
- Click on the green button with the text **“Code”.**
- Click on **“Open with GitHub Desktop”** and follow the prompts in the GitHub Desktop Application or follow the instructions from **[this link](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop)** to see how to clone the repository in other ways.

#### Working with the local copy

1. Install all the requirements: Go to the workspace of your local copy. In the terminal window of your IDE type: **pip3 install -r requirements.txt**.

2. Create a database in MongoDB

   - Signup or login to your MongoDB account.
   - Create a cluster and a database.
   - Create collections in the db: **Developer, skillset, subscribers, users.**
   - Add string values for the collections. See how the [here](https://) database is set up for this project.

3. Create the environment variables

   - Create a .gitignore file in the root directory of the project.
   - Add the env.py file in the .gitignore.
   - Create the file env.py. This will contain all the environment variables.

   ```
   Import os
   os.environ.setdefault("IP", "Added by developer")
   os.environ.setdefault("PORT", "Added by developer")
   os.environ.setdefault("SECRET_KEY", "Added by developer")
   os.environ.setdefault("MONGO_URI", "Added by developer")
   os.environ.setdefault("MONGO_DBNAME", "Added by developer")
   ```

4. Run the app: Open your terminal window in your IDE. Type python3 app.py and run the app.

#### Heroku Deployment

1. Set up local workspace for Heroku

   - In terminal window of your IDE type: **pip3 freeze -- local > requirements.txt.** (The file is needed for Heroku to know which filed to install.)
   - In terminal window of your IDE type: **python app.py > Procfile** (The file is needed for Heroku to know which file is needed as entry point.)

2. Set up Heroku: create a Heroku account and create a new app and select your region.

3. Deployment method 'Github'

   - Click on the Connect to GitHub section in the deploy tab in Heroku.

     - Search your repository to connect with it.
     - When your repository appears click on **connect** to connect your repository with the Heroku.

   - Go to the settings app in Heroku and go to

     Config Vars. Click on Reveal Config Vars.

     - Enter the variables contained in your env.py file. it is about: **IP, PORT, SECRET_KEY, MONGO_URI, MONGO_DBNAME**

4. Push the requirements.txt and Procfile to repository.

   ```
   $ git add requirements.txt
   $ git commit -m "Add requirements.txt"
   
   $ git add Procfile 
   $ git commit -m "Add Procfile"
   ```

5. Automatic deployment: Go to the deploy tab in Heroku and scroll down to **Aotmatic deployments**. Click on **Enable Automatic Deploys**. By **Manual deploy** click on **Deploy Branch**.

Heroku will receive the code from Github and host the app using the required packages. Click on **Open app** in the right corner of your Heroku account. The app wil open and the live link is available from the address bar.

# 6. Credits

#### Profiles

- 

#### Media

- 

#### Code

- 

# 7. Acknowledge

Who helped me for the project:

- The support and guidance of my mentor 
- The lessons and knowledge of [Code Institute.](https://codeinstitute.net/)

# 8. Disclaimer

This project is for educational purposes only. 

Thanks for visiting