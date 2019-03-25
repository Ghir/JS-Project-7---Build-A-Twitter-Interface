An Express app that authenticates with Twitter to show recent activity and send tweets.


### Config file
Create a config.js file on the root and add your Twitter App credentials:
```
module.exports = {
  consumer_key: "YOUR-CONSUMER-KEY",
  consumer_secret: "YOUR-CONSUMER-SECRET",
  access_token: "YOUR-ACCESS-TOKEN",
  access_token_secret: "YOUR-ACCESS-TOKEN-SECRET"
};
```

### Running
* `npm install`
* `npm start`
