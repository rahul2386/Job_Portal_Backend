nd
- frontend

## Getting Started
To run this application, follow these steps:

Clone the project using:
`git clone https://github.com/Zeeshu911/MERN-Stack-Job-Seeking-Web-Application`

### Backend

1. Create config directory using `mkdir backend/config/`
2. Inside `config` dir, create a file `config.env` (See provided example)
3. Change directory using `cd backend` from project root
4. Run `npm i` to install missing dependencies
5. Run the server using `npm start` or `npm run dev`

### `config.env` example:
```
PORT = 4000
CLOUDINARY_CLIENT_NAME=<client_name>~
 
CLOUDINARY_CLIENT_API=<client_api>
 
CLOUDINARY_CLIENT_SECRET=<client_secret>
 
FRONTEND_URL=http://localhost:5173
MONGO_URI=mongodb://<replace_with_username>:<replace_with_password>@localhost:27017
 
JWT_SECRET_KEY=<jwt_secret_key>
JWT_EXPIRES=7d
COOKIE_EXPIRE=7
```

### Frontend

1. Change directory using `cd frontend`
2. Run `npm i` to install missing dependencies
3. start frontend using `npm run dev`

> NOTE: If you encounter CORS issues, ensure that the origin URL matches the FRONTEND_URL provided in the config.env file.
> Any discrepancies, such as a different port number or trailing slashes, could cause CORS to fail.