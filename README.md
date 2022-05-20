# blinkistClone
Blinkist Application Clone using React

#### - This application uses React, typescript, material UI

## Running the application

step 1 - Install JSON Server 
```bash
npm install -g json-server
```

step 2 - Run Mock Server to use the server's data
```bash 
json-server --watch data/db.json --port 3333
```

step 3 - If you get an error saying execution of scripts is disabled on this system, use
```bash 
powershell -ExecutionPolicy Bypass -File script.ps1
json-server --watch data/db.json --port 3333
```

step 4 - Run react server in another terminal
```bash
npm start
```
