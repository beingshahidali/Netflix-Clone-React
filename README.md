
<h1 align="center">
  <img title="Netflix" src="https://fhsknightlife.com/wp-content/uploads/2020/04/uVASXqvMzyUrAPfSn9pMtxOC7s89ulzdDKBdtqCP.png" alt="NETFLIX Logo" width="400" />
  <br>
  Netflix Clone Built Using React.JS & Firebase
</h1>

<p><font size="3">
  This is a clone of Netflix website built using <strong><em>React.JS</em></strong> as a Front-end & <strong><em>Firebase</em></strong> as Back-end. It's not a replica, and it     doesn't have all the features of Netflix website. it's a similar version of Netflix with my own design touch, showing my abilities in React.JS to build something advanced       like Netflix. It contains the home page, sign-in page, sign-up page and account page.
  <br><br> 
  
</p>







# Technology Used

I have built this project using the following tools & techniques:
- React.JS
- React Router.
- React Forms.
- React Hooks.
- useState.
- useContext.
- useEffect.
- useState.
- Compound Components.
- JSX.
- CSS Modules.
- Firebase.
- VSCode.

# Screenshots

![Screenshot](https://github.com/beingshahidali/Netflix-Clone-React/blob/main/public/screenshot/1.png)
![Screenshot](https://github.com/beingshahidali/Netflix-Clone-React/blob/main/public/screenshot/2.png)
![Screenshot](https://github.com/beingshahidali/Netflix-Clone-React/blob/main/public/screenshot/3.png)
![Screenshot](https://github.com/beingshahidali/Netflix-Clone-React/blob/main/public/screenshot/4.png)
![Screenshot](https://github.com/beingshahidali/Netflix-Clone-React/blob/main/public/screenshot/5.png)



# How To Use

To be able to use this react app locally in a development environment you will need the following:

1) You will need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) installed on your computer.

2) You will need an account on [Firebase](https://firebase.com) and you should create a project on your firebase account dedicated to this Netflix project.

3) You will need the "./seed.js" file (which I added in this repo) to seed your firebase backend with movies information. OR you can use your seed file with your information if you want.

4) Then From your terminal, you should do the following:

```cmd
# Clone this repository
git clone https://github.com/beingshahidali/Netflix-Clone-React

# Go into the repository
cd netflix-clone-react

# Install dependencies
npm install 

```

5) Then you will need to create the ./src/firebase.js file in your local repo, The content of firebase.js file will be like the following:

```js
import Firebase from 'firebase/app';
import 'firebase/firestore';
import 'firebase/auth';

// 1) when seeding the database you'll have to uncomment this!
// import { seedDatabase } from '../seed';

const config = {
  apiKey: '',
  authDomain: '',
  databaseURL: '',
  projectId: '',
  storageBucket: '',
  messagingSenderId: '',
  appId: '',
};

const firebase = Firebase.initializeApp(config);
// 2) when seeding the database you'll have to uncomment this!
// seedDatabase(firebase);
// 3) once you have populated the database (only run once!), re-comment
// this so you don't get duplicate data

export { firebase };

```

6) Then you should use your firebase project information to fill the config information in firebase.js file.

```js
const config = {
  apiKey: '',
  authDomain: '',
  databaseURL: '',
  projectId: '',
  storageBucket: '',
  messagingSenderId: '',
  appId: '',
};

```



8) After seeding your firebase database with the movies information & reverting the Github Pages changes you can run the Netflix React App using the following command from your terminal:

```
# Run the app
npm start
```

9) Now you can see the project in your browser as you see in the live demo link. 
Happy Hacking!


# Show Your Support

Give a ⭐️ if you like this project!

# Acknowledgments

Hat tip to everyone helped me to learn the techniques used in building this project.




