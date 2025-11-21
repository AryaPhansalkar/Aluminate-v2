# Aluminate

## Project Setup Guide

### Cloning the Repository
After forking the repository clone repository using git clone as 
```bash
git clone https://github.com/AryaPhansalkar/Aluminate-v2
```
Note: switch the url with your own url

Change directory using
```bash
cd Aluminate-v2
```

### Install Dependencies

**Install dependencies:**
```bash
npm run install:all
```

### Setting up .env file
Inside the server folder create a .env file and copy all the contents from .env.example .
Replace the MONGODB_URI with your own mongoDB URI.

## Scripts & Commands
Run from the *root directory* 

Starts both frontend and backend concurrently (if configured) 
```bash
npm run dev:all
```

> Make sure `concurrently` is installed if using `npm run dev:all`.

If `concurrently` is not installed run the command:
```bash
npm install concurrently
```

If you want to start frontend and backend seperately follow the following steps:


Starts the React frontend   
```bash
npm run dev:client
```

Starts the Express backend       
```bash
npm run dev:server
```


