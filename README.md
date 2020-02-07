# :dog2: Cerberus

A handy application to manage music in events, based on public review.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install Cerberus. Use

```bash
npm install
```

## Usage

To make all services functional, you need to save configurations in a `.env` file. The file must contain the entires listed in `.env.sample` file

```

# Store details about database connections
DB_USER=someUser
DB_PASS=mySecurePassword
DB_HOST=localhost:27017
DB_NAME=myDbNane

# Store details about application
PORT=3000
...
```

When the configurations are set, run the server using

```javascript
node app.js
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](./LICENSE)
