<h1 align="center">Welcome to Mern Admin Dashboard</h1>


> An admin dashboard built using Node, Express, Node and React to for managing users easily. Coming from a django background, there is a free admin panel all models, So I decided to build one with MERN so I could easily manage the user data easily.

> To test the live

```
Email: test@gmail.com
Password: testing
```

## Install

```sh
npm install
```

## Usage

> To get this project running pefectly on your local, ensure you follow the instructions below.

1. Create a .env file in the root directory.
2. In the .env file ensure you have the following setup.

```
MONGODB_URI=YOUR MONGODB URI
TOKEN_SECRET = THIS IS FOR THE SIGNING THE JWT, YOU CAN USE ANY RANDOM CHARACTERS
BASE_URL=http://localhost:8000/api/
port=YOUR PREFERRED PORT i.e 8000
```

3. Run the npm command below

```sh
npm run dev
```

4. Refer to the docs located at /api/v1/docs/ i.e http://localhost:8000api/v1/docs/ to create a user.

5. Visit http://localhost:8000 to login the user you created.

## Run tests

```sh
npm run test
```

