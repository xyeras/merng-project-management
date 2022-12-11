## Steps to set up
1. `npm install`
2. `touch .env`

### config.js content

```
NODE_ENV = 'development'
PORT = 5555
MONGO_URI = 'Placeholder'
```

3. For your MONGO_URI, go [here](https://www.mongodb.com/atlas/database)
4. Create an account if you don't have one
5. Once you have one, login
6. Create and name an project
7. Create a cluster
8. Create user with username and password; keep your username and password safe
9. Add your current IP address; you may need more for each wifi you have access
10. Click on "Connect on the cluster"
11. Click on "Connect your application"
12. Grab the given uri; the uri should start with "mongodb"
13. Replace the placeholder for uri inside the quotes with uri
14. `npm run dev`