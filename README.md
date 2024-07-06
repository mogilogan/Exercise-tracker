# Exercise-tracker
I am doing a Project based learning and this is my 1st MERN stack app.

## How to run
- Clone this repo:
```
git clone https://github.com/mogilogan/Exercise-tracker.git

```
- Go to the cloned directory and install the packages with these commands:

```
cd Exercise-tracker
npm start
cd backend
npm start

```

- Run the backend First and the Frontend:

```
npm start
cd ..
npm start
```

- You can see the backend running on PORT 5000 and Frontend runnong on PORT 3000!


## FRONTEND

The Frontend has 4 Component with navbar to navigate between Them

- The Main component loads all the exercise of the user using [axios](https://www.npmjs.com/package/axios).fetch
- The create exercise is made to create new exercise
- The edit Exercise components takes id as url params and edits the exercies!
- The Create User Component is used to Sign up

![Sample Image](Img/server1.JPG?raw=true "Title")

## BACKEND
The Express App handles REST api in a simpler way. This app two main routes.

+ Exercise Route:
  - get all exercise
  - get exercise by id
  - delete exercise
  - update exercise by id
    
+ User Route
  - Get all users
  - Sign up users

## Database

Two Schemas were used: Exercise document and User document
