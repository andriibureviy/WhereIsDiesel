# Ruby Telegram Bot(PetProject)

### Running The Bot

Install all dependecies
```
bundle
```

Create database.yml and secrets.yml
```
cp config/database.yml.sample config/database.yml
cp config/secrets.yml.sample config/secrets.yml
```

Create database
```
rake db:create
```

Run the bot 
```
bin/bot
```