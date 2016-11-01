# Marvin React App

Client operating off boilerplate available [here](https://github.com/erikras/react-redux-universal-hot-example)

# Installation
```
npm install
```

# Running the server
Development
```
npm run dev
```

Production
```
npm run build
npm run start
```

The difference between development and production is that in production all code
is minified and uglified, and hot reloading is disabled.

# Changing the API endpoint
The client server has a simple configuration option to set the API proxy
endpoint that connects to the restful flask backend. These can be changed in
`src/config.js`.
