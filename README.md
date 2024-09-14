# Node.js MongoDB youtubeSubscribers App
Aniket3199

A simple Node.js application using MongoDB to manage subscriber data.

## Features

- Add, update, and delete subscribers
- Retrieve all subscribers
- Retrieve subscribers by name and channel
- Retrieve a subscriber by ID
  

# Technologies Used
- Fronted:HTML CSS

- Backend:node.js,Express.js,Mongoose

- Database:Mongodb
- API: Custom API for fetching Subscriber Data
  

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) or a local MongoDB instance

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2. Install the dependencies:
    npm install

3. Create a .env file in the root directory and add your MongoDB URI:
    MONGO_URI= mongo db connection string

4. Create the database and insert initial data:
    node src/createDatabase.js
   #Link
   Deployedlink:

### Running the Application

    ## Start the server:

    node src/index.js

    Open your browser and navigate to http://localhost:3001.

### API Endpoints

    GET /subscribers: Retrieve all subscribers
    GET /subscribers/names: Retrieve subscribers with only names and subscribed channels
    GET /subscribers/:id: Retrieve a subscriber by ID
