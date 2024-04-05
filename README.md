# My-LinkedIn-Greets
Automating my LinkedIn to greet every connection, Because Why not!
- It can also play detective and guess your Age and Gender 🤭

![Banner](mm.png)

# LinkedIn Automation Toolkit

## 1. LinkedIn - Get Age and Gender from Profile Picture

### Description
Estimate a person's age and gender based on their LinkedIn profile picture.

### Disclaimer
- This code is not affiliated with or endorsed by LinkedIn.

### Input
- LinkedIn cookies:
  - `LI_AT`: Cookie used to authenticate Members and API clients
  - `JSESSIONID`: Cookie used for Cross Site Request Forgery (CSRF) protection and URL signature validation
- LinkedIn profile URL

### Output
- Estimated gender and age of the LinkedIn profile owner

## 2. LinkedIn - Accept All Invitations and Send First Message

### Description
Quickly and easily accept all LinkedIn invitations and send a personalized introductory message to each new connection.

### Disclaimer
- This code is not affiliated with or endorsed by LinkedIn.

### Input
- LinkedIn cookies:
  - `LI_AT`: Cookie used to authenticate Members and API clients
  - `JSESSIONID`: Cookie used for Cross Site Request Forgery (CSRF) protection and URL signature validation
- Optional:
  - `limit`: Number of invitations to be accepted. If `limit = -1`, all invitations are accepted.
  - `first_message`: First message to be sent
  - `cron`: Cron params for Naas scheduler.

### Output
- Display result of invitations accepted

### Prerequisites
- Get your cookies on LinkedIn:
  - `LI_AT`: Cookie used to authenticate Members and API clients
  - `JSESSIONID`: Cookie used for Cross Site Request Forgery (CSRF) protection and URL signature validation
- Mandatory:
  - `LI_AT = "YOUR_COOKIE_LI_AT"`
  - `JSESSIONID = "YOUR_COOKIE_JSESSIONID"`
- Optional:
  - `limit`: Number of invitations to be accepted. If `limit = -1`, all invitations are accepted.
  - `first_message`: First message to be sent
  - `cron`: Cron params for Naas scheduler. More information: [crontab.guru](https://crontab.guru/)
 
Isn't it amazing how every connection request gets a response faster than a LinkedIn influencer posting about #MotivationMonday? Talk about networking at the speed of Wi-Fi! 💬

