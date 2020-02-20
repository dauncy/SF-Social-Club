**SF SOCIAL CLUB** 

SF Social Club is a full CRUD command line apllication for users to search for upcomming events in San Francisco. 
Data was gathered from the EventBrite API (which has since been depricated) and stored in the databse using Sqlite. 
To run the app, fork or clone this repo, CD into the repo, and type...
``` 
ruby bin/run.rb 
```


What can a user do?
- Signup or Login, visit his/her profile page to see current RSVPs 
- Search for events by category, date posted, and title.
- Add/remove RSVPs.
- See which events are most popular.
- Check which events his/her friends' have RSVP'd to.
- Look up a random event. 

***Languages and Technologies Used***
- Ruby using ActiveRecord relations and Sqlite to persist user data to the databse.
- EventBrite API for collecting events in San Francisco.
- RestClient and JSON Ruby gems implemented to parse the API JSON data and seed the database with events in San Francisco. 

