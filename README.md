The purpose of this project is to develop a small networked networked a-frame game over one weekend.

Test of firebase and networked a-frame

To develop,
 ```
cd server
ln -s ../public/ static
In Windows this is better cd server; move ../public static
Dont forget to put it >move server\static public
npm install
npm run easyrtc-install
npm run dev
 ```

To deploy
 ```
npm -g install firebase-tools

firebase login
firebase deploy
 ```