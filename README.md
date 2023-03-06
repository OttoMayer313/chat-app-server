### chat-server

<br/>
git clone https://github.com/ottomayer313/chat-server.git

<br/>
cd chat-app-api

<br/>
npm install nodemon -g

<br/>
npm install

<br/>
Create a config.env file in root and add some env variables.

<br/>
NODE_ENV=development
DB_STRING=your mongodb database string

<br/>
// I have used sendgrid to send emails,
// create a sendgrid account and after your setup is done add your credentials here

<br/>
SENDGRID_USERNAME=your sendgrid username
SENDGRID_PW=your sendgrid password
EMAIL_FROM=email from which you are sending mails.

<br/>
JWT_SECRET=any random string you want (preferred min 32 strings)
JWT_EXPIRES_IN=expiry date for your jwt tokens
JWT_COOKIE_EXPIRES_IN=expiry date for your cookies

// I have used pusher to make this app real time
// create a pusher account and after your setup is done add your credentials here

PUSHER_APP_ID=your pusher app id
PUSHER_KEY=your pusher app key
PUSHER_SECRET_KEY=your pusher secret key
PUSHER_CLUSTER=your pusher app cluster

<br>

Now you are done and can start your development server

npm run dev
