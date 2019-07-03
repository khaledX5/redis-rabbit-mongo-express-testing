## Installation &nbsp;
**1) Install Dependencies**
npm install

**2) install Docker 
**3) Build Docker Image**
docker build -t khaled/express -f ./intialization/Dockerfile .

**4) start the app**
in terminal run
docker run -p 3000:3000 khaled/express

you can find the app at http://localhost:3000/


