<div>
  <h1>Wanderlust</h1>
  <h2>The Ultimate Travel Blog 🌍✈️ for You </h2>
</div>

![Preview Image](https://github.com/krishnaacharyaa/wanderlust/assets/116620586/17ba9da6-225f-481d-87c0-5d5a010a9538)

<hr>

<div>
  <h2>🔗 Important Links</h2>
</div>

<table border="1">
  <tr>
      <td><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/5ca6c472-5c73-41b2-a2df-389cc3e14881.png" alt="Discord Logo" width="50"></td>
      <td><a href="https://discord.gg/FEKasAdCrG"> Join our project's Discord Channel here </a></td>
  </tr>
  <tr>
      <td><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/ffda08c0-3c7a-46b0-b7ac-6bc374184ec7.png" alt="Figma Logo" width="50"></td>
      <td><a href="https://www.figma.com/file/zqNcWGGKBo5Q2TwwVgR6G5/WanderLust--A-Travel-Blog-App?type=design&node-id=0%3A1&mode=design&t=c4oCG8N1Fjf7pxTt-1"> Find our project's Figma links here</a></td>
  </tr>
  <tr>
      <td><img src="https://github.com/krishnaacharyaa/wanderlust/assets/133582566/47d71dd6-0390-479e-9d4e-3f077ef1a987.png" alt="YouTube Logo" width="50"></td>
      <td><a href="https://youtu.be/ANfC1u_N_A0?feature=shared"> Find our Collaboration Video with TrainwithShubham here </a></td>
  </tr>
</table>

<hr>

<div>
  <h2><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/4a07b161-b8d6-4803-804a-3b0db699023e" width="35" height="35"> Goal of this project </h2>
</div>

At its core, this project embodies two important aims:

1. **Start Your Open Source Journey**: It's aimed to kickstart your open-source journey. Here, you'll learn the basics of Git and get a solid grip on the MERN stack and I strongly believe that learning and building should go hand in hand.
2. **React Mastery**: Once you've got the basics down, a whole new adventure begins of mastering React. This project covers everything, from simple form validation to advanced performance enhancements. And I've planned much more cool stuff to add in the near future if the project hits more number of contributors.

_We want you to get the most out of this project—it's all about learning, contributing, and growing in the open-source community._
<hr>

<div>
  <h2><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/1ee5934a-27be-4502-a7bf-e6a8c78fe5a3" width="35" height="35"> Installation</h2>
</div>

- **Clone the code :** git clone https://github.com/Shahzad33/wanderlust.git
- **Navigate to the backend dir:** cd wanderlust/backend
- **Install required package:** npm i                        //show error because of node js not 
- **Navigate to the backend dir:** cd ../..
- **Install node js:** Refer this links for install:  https://nodejs.org/en/download/package-manager
- **Install installs nvm (Node Version Manager):** curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
- **Reboot the system:** sudo reboot 
- **Download and install Node.js:** nvm install 22
- **Node.js and NPM version:** node -v and npm -v
- **Navigate to the backend dir:** cd wanderlust/backend
- **Install required package:** npm i 

<div>
  <h2><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/1ee5934a-27be-4502-a7bf-e6a8c78fe5a3" width="35" height="35"> Setup your MongoDB database</h2>
</div>

 
- **Navigate to the root dir:** cd ../..
- **Import the public key:** sudo apt-get install gnupg curl
- **To import the MongoDB public:** curl -fsSL https://www.mongodb.org/static/pgp/server-7.0.asc | \
   sudo gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg \ --dearmor
- **Create the /etc/apt/sources.list.d/mongodb-org-7.0.list file:** echo "deb [ arch=amd64,arm64 signed-by=/usr/share/keyrings/mongodb-server-7.0.gpg ] https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/7.0 
    multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-7.0.list
- **Reload local package database:** sudo apt-get update
- **Install the MongoDB packages:** sudo apt-get install -y mongodb-org
- **Start MongoDB:** sudo systemctl start mongod
- **Check the mogodb:** mongosh
- **Exit the mogodb:** exit
- **Navigate to the backend dir:** cd wanderlust/backend
- **Import data from a JSON:** mongoimport --db wonderlust --collection posts --file ./data/sample_posts.json --jsonArray
- **Copy contant:** cp .env.sample .env
- **Exit the mogodb:** npm start
<hr>

