# Reference
https://betterprogramming.pub/how-to-host-your-react-app-on-github-pages-for-free-919ad201a4cb
https://stackoverflow.com/questions/43943999/after-npm-run-deploy-errors-occured 

https://nextjs.org/docs/getting-started

“homepage”: “https://ameliatyr.github.io/react-deploy/"


$ git init
$ git add .
$ git commit -m "add: initialCommit"
$ git remote add origin https://github.com/username/React-Deploy.git
$ git push origin master

npx create-react-app "app name"
npm install gh-pages --save-dev

  "scripts": {
    "start": "react-scripts start",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "homepage": "https://ameliatyr.github.io/react-deploy/",
  
  
  npm run deploy
