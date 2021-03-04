# CS97-WebApp
Web App final for CS97

How someone who cloned this can run our app
  - with inclused shell commands needed for setup
  
In order to be able to run the webapp, we first 
1) need to have node installed 
2) will be working in the command line 
  
First we need to clone the repository 
```
  git clone https://github.com/Striker528/CS97-WebApp.git
```
The repository will be named CS97-WebApp and this holds everything we did with the webproject.
The actual webapp is in a directory named FinalProject within the main repository.

We can navigate to the correct directory using
```
 cd CS97-WebApp/FinalProject/
```
and we will be initializing and installing libraries into the correct directory. 

Next we need to initalize the file by running the line
```
 npm init 
```

A concern to note with the npm init command is that at the bottom we will see a line saying 
```
 Is this OK? (yes)
```
Be careful not to just to click past this part. However, if you happen to click past this, just run npm init and go down to the line again. 
With this we have to make sure we type yes to initalize the line so the should look like this after we input yes and press enter.
```
 Is this OK? (yes) yes
```

Next we need to install some libraries using 
```
 npm install express --save
 npm install nodemon --save-dev
 npm install body-parser --save
 npm install mongodb --save
 npm install ejs --save
 npm install locus --save 

```

Everything should be installed now and we should be able to run the application using 
```
 npm start 
```

The application should be running on localhost:3000 and we will see in the command line 
```
listening on 3000
```
which means the application is running!!!


Can move everything into codesandbox and run it there. 

need to run npm install:
  npm install mongodb
  npm install locus
  npm install express
  npm install ejs
  npm install body-parser
  
  
  how to build the thing

  clone from git 
  git clone https://github.com/Striker528/CS97-WebApp.git

  file will be called CS97-WebApp
  cd CS97-Webapp
  cd Final Project (location of the app)

  Lines to run
  npm init 
  - must make sure to say yes at the bottom


  libraries to download
  npm install express --save
  npm install nodemon --save-dev
  npm install body-parser --save
  npm install mongodb --save
  npm install ejs --save
