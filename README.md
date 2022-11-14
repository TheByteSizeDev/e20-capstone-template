# Getting Started with This Template

**PLEASE READ ALL STEPS BEFORE BEGINING WORK**. This template is designed to get you up and running with your captone as quickly as possible. It comes with a couple gimmes, mainly:

* Everything you get when you run `create-react-app`
* All of your dependencies ready to be installed ie: `react-router-dom`
* Authentication already taken care of

File Structure:

```
public
src
  components
    auth
      Login.css
      Login.js
      Register.js
    views
      ApplicationViews.js
      Authorized.js
    CapstoneTemplate.js  *change to your app name
index.css
index.js
.gitignore    *important! Ignores files you don't want pushed up
package.json
README.md     *important! You will need to fill this out for your app later
```

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## IMPORTANT Before you begin working

### Step 1: Clone from this template

1. Click the "use this template" button in the upper right hand corner of this repo. And select "create a new repository".

![Screen Shot 2022-11-14 at 7 55 27 AM](https://user-images.githubusercontent.com/43580474/201677821-fca0834d-2cf9-4465-9488-d6ab755f0ffa.png)

2. Select yourself from the "Owner" drop down list and name your repo after your app. Important! Make sure it's set to public"

![Screen Shot 2022-11-14 at 7 57 16 AM](https://user-images.githubusercontent.com/43580474/201678218-8b8b85a8-4e09-4b89-bff0-c01c0aa604d9.png)

3. Now you should have a copy of this as a github repo in your github! All you have to do is copy the ssh from the green "<> CODE" button in the upper right hand corner and clone it locally.


### Step 2: Change To Your App Name

1. In your `package.json` file change the "name" property on line 2 to your app's name
2. Rename the `CapstoneTemplate.js` file to your app's name. Do the same with the name of the component

### Step 3: Run `npm i`

Run `nmp i` in your app's root directory and **you're all set**!


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
