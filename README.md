Inventory App

This project is an Inventory Management System built with React.
It is fully functional and can be run locally on your computer or mobile device.

Features

Add, update, and delete stock items

Keep track of inventory in real-time

Fully responsive UI

Getting Started (Desktop & Mobile)
Prerequisites

Node.js
 installed

NPM comes with Node.js

PC and Mobile on the same Wi-Fi network (for mobile access)

1. Clone the repository
git clone https://github.com/riyazansari/inventory_app.git
cd inventory_app
2. Install dependencies
npm install
3. Run the app (Desktop)
npm start

Open your browser at: http://localhost:3000

The app will automatically reload if you make edits.

4. Run the app (Mobile)

Find your PC’s local IP address:

ipconfig   # Windows
ifconfig   # Mac/Linux

Example: 192.168.1.10

Start the React server with network access:

npm start -- --host 0.0.0.0

On your mobile browser, open:

http://<YOUR_PC_IP>:3000

Example: http://192.168.1.10:3000

Now you can see and use the full app on mobile!

5. Build for Production
npm run build

Creates a build/ folder with optimized production files

Ready to deploy on any hosting service

6. Optional: Share with Anyone using ngrok
npm install -g ngrok
ngrok http 3000

This gives you a public URL to access your app from any device
