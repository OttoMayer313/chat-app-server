<!-- intro -->
<h1>Chat Server</h1>
<br/>
git clone https://github.com/ottomayer313/chat-server.git <br/><br/>

cd chat-app-api <br/>

npm install nodemon -g <br/>

npm install <br/>

Create a config.env file in root and add some env variables. <br/>

NODE_ENV=development <br/>
DB_STRING=your mongodb database string <br/>

// I have used sendgrid to send emails, <br/>
// create a sendgrid account and after your setup is done add your credentials here <br/>

SENDGRID_USERNAME=your sendgrid username <br/>
SENDGRID_PW=your sendgrid password <br/>
EMAIL_FROM=email from which you are sending mails. <br/>

JWT_SECRET=any random string you want (preferred min 32 strings) <br/>
JWT_EXPIRES_IN=expiry date for your jwt tokens <br/>
JWT_COOKIE_EXPIRES_IN=expiry date for your cookies <br/>

// I have used pusher to make this app real time <br/>
// create a pusher account and after your setup is done add your credentials here <br/>

PUSHER_APP_ID=your pusher app id <br/>
PUSHER_KEY=your pusher app key <br/>
PUSHER_SECRET_KEY=your pusher secret key <br/>
PUSHER_CLUSTER=your pusher app cluster <br/>

Now you are done and can start your development server <br/>

npm run dev <br/>
