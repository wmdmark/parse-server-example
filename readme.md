To run:

1. Start parse server: `parse-server --appId APPLICATION_ID --masterKey MASTER_KEY --databaseURI mongodb://localhost/test`
2. Start local client server: `python -m SimpleHTTPServer 3000`
3. Open `http://localhost:3000` and check the console. You should see that a user has been created (only works the first time since the user is already created the second time)