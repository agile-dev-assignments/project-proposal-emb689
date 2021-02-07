# Stonks Only Go Up

### What? Why? Huh?
The foundation of this project is built around two key ideas: following recent trends and actually being useful (to some degree) in the real world.

**Stonks Only Go Up** is a SaaS platform that allows users to get realtime updates from certain websites, articles, and forums relating to the stock or crypto market. Essentially, once there is an unusually amount of chatter about a specific company OR specified individuals that the user 'follows' talks about a certain company/crypto, our platform sends an update to inform the user so that user can now execute a trade based on that response.

Lets take a simple example. Let's say you absolutely love Elon Musk to the point where you literally do not care about financials and just want to invest in whatever he tweets about or supports (cough cough TSLA overvalued cough cough). You then follow that person on our software and as soon as he tweets about something related to, for example, Amazon, then you would become notified of that specified message along with relevant data on Amazon so you can then execute a trade. This notification can be included in a text message or email.

An example text would be "Hey Joe! Elon Musk just tweeted Dogecoin to the moon! # 1:04pm EST (New York). Snapshot price of DogeCoin: $2,329.29"

### Whom?
This will be specifically cater towards some individuals who are absolutely in love with following what others are doing to make money in the stock or crypto market. Specifically, we are targetting young investors (16-30), but our product can also be used for more seasoned investors to understand Gen Z chatter.

### How?
Ideally, this will include the following core components:
* User Authentication
    - handles the user's follows and saves the notification data.
* Dashboard
    - displays the 'follows' of the user along with some basic market data
* New Follow
    - Would have a few core components that the user can pick up to have 'listeners' on:
        - Forum Post (insert a URL to a forum you want to recieve updates on)
        - Twitter (select a user you want to follow market updates from)
        - whatever else...
* Settings & Profile
    - Configure how you want to recieve updates
    - Edit profile info
        - login data, notification mgmnt, phone num, email

### Additional Notes
There are a bunch of different APIs we can use (Twitter has a prominent one in particular) as well as using basic web scrapping to get stock market/crypto data. For auth, can use Google Auth or another service. EmailJS good for sending emails in ReactJS to a user.

Also, this idea kinda started as a joke but it honestly seems pretty fun and forces us to work on external tools/apis to get it done with a TON of flexibility and potential other features.
