# 46elks [sms api](https://46elks.com), [mms api](https://46elks.com), [voice api](https://46elks.com/link-to-details-about-voice) - Automate and integrate telephony into your routines!

## Introduction

Welcome!

You can use the [46elks](https://www.46elks.com) api to send and receive text messages, and phonecalls, from and into your system. Here you'll find [sample code]() and inspiring [Demos & Projects]().

### Useful links

  * [Documentation](https://www.46elks.com/api-docs#introduction)
  * [Sample code](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/samples)
  * [Dashboard](http://dashboard.46elks.com/)
  * [Articles about API, Basic auth, and integrations with 46elks - link to resources further down in this document](46elks@medium) 
  * [Contact 46elks](46elks.com/help#contact)

## Getting started

1. You need *credentials* (a username & a password, also known as your api keys) to use the 46elks api. Create your free 46elks account at [46elks.com/create-account](https://www.46elks.com/create-account), to get a username and password. Used for connecting to the api through [basic auth](46elks@medium article about basic auth).
2. *Documentation* is available at [46elks.com/docs](https://46elks.com/docs).
3. You might want to dig right into *[Sample code](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/samples)*.

## Sample code

### Quick start
Using [46elks credentials]() enter this into your terminal:
```
curl -X POST \
  -u <API-Username>:<API-Password> \
  -H 'Content-Type: application/x-www-form-urlencoded' \
  -d 'from=VILLE' \
  -d 'to=+358503672181' \
  -d 'message=Test Message To your phone.' \
  'https://api.46elks.com/a1/SMS' 
``` 

You've now sent an sms!




### Send sms

[C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/send-sms) &nbsp;
[Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir)  &nbsp;
[Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go)  &nbsp;
[PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php)  &nbsp;
[Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py) &nbsp;
[Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)

### Receive SMS

[C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/receive-sms)
[Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir/receive-sms)
[Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go)
[PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php)
[Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py)
[Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)


### Make a phone call

[C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/receive-sms)
[Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir/receive-sms)
[Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go)
[PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php)
[Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py)
[Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)


### Receive a phone call

[C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/receive-sms)
[Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir/receive-sms)
[Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go)
[PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php)
[Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py)
[Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)

### Build an interactive voice response (IVR)

What is an ivr? It's ... A more complete article can be found [medium](46elks@medium/What is ivr?)

[IVR samples](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/code%20samples/Voice%20-%20IVR%20-%20interactive%20voice%20menues)



### Demo applications

#### Smart support - Have one supportnumber; redirect it to different people different times of the day, or selected days of the week, accept incoming sms from customers into your e-mail inbox with Zapier, and reply to their e-mail if you have it on record, or reply to them via sms, by replying to the e-mail.

#### Two factor authentication

#### Elkme - Send textmessages from your terminal

#### Sms game at fair.

#### Open sesame - open gates at your local..  with an sms.

## Tutorials

* [Love messenger](https://github.com/gish/love-messenger)
* [Receive SMS into Google spreadsheet](https://medium.com/@46elks/receive-sms-into-google-spreadsheet-435b51393493#.9ku01h462)

## Resources
Articles on Medium by 46elks.
46elks on twitter
Article about ... by @{username}
Article - README driven development
Article - User research drive nREADME. How this README came to developed.
  
## Integrations
  * Zapier [Zapier tutorial](http...)
  * Filemaker PRO [Link to article about how to integrate 46elks with Filemaker Pro]()
  * Microsoft Excel
  * Google spreadsheet

## Contributors
  THANK YOU!
  @{username} - Added sample code for...
  @{username} - Created
  
## Hackathons
  We are keen on helping out, and we'd be happy to help you with.. and credits for participants etc. [Talk to us](mailto:hello@46elks.com). We're also particularily interested in helping events and organizations working with teaching coding to beginners, initiatives that encourage diversety in IT, and among conferences. We enjoy meetups, let us know if you’d like for someone to come and hold a presentation about APIs - getting started with apis, how to send an sms in Elixir/Ruby/Go..  We exist to help you build useful and cool things!
  Say hi! Twitter: Uppsala: In Stockholm: In Göteborg: In Poland:

## WIP
As with most things in life, this README is work in progress! It's a living document that changes as we improve.
Would you let us know if you see how it can be improved?
Feel free to open up a pullrequest, or send us a message at hello@46elks.com!

## Call for contributions

### Accessability 

#### language

We have a dream, that this service should be super duper accessible to you, and a we think a first step is to localize this README. We'll try our best in the languages we know. We'll ask our friends. Is your language missing? Can you help us out?
