![46elks-logo](https://www.46elks.com/images/logo/46elks-240-150.png)

# 46elks [sms api](https://46elks.com), [mms api](https://46elks.com), [voice api](https://46elks.com/link-to-details-about-voice) - Automate and integrate telephony into your routines!

Welcome!

The 46elks api makes it easy for you to add custom telephony features that are perfectly suited to the way you do things – because let’s face it, sometimes ‘off the shelf’ just doesn't cut it.

You can use the [46elks](https://www.46elks.com) api to 

* send and receive text messages
* initiate and receive phonecalls
* build interactive voice sessions

Here you'll find [sample code]() and inspiring [Demos & Projects]().

### Useful links

  * [Documentation](https://www.46elks.com/api-docs#introduction)
  * [Sample code](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/samples)
  * [Dashboard](http://dashboard.46elks.com/)
  * [Introduction - Learn about using an API](https://zapier.com/learn/apis/) 
  * [Contact 46elks](46elks.com/help#contact)


## Getting started

1. You need *credentials* (a username & a password, also known as your api keys) to use the 46elks api. Create your free 46elks account at [46elks.com/create-account](https://www.46elks.com/create-account), to get a username and password. Used for connecting to the api through [basic auth](46elks@medium article about basic auth).
2. *Documentation* is available at [46elks.com/docs](https://46elks.com/docs).
3. You might want to dig right into *[Sample code](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/samples)*.

<br>

## Sample code

**Quick start** - give the api a try! Using your [46elks credentials](https://dashboard.46elks.com) enter this into your terminal:
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



* Send sms [C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/send-sms) [Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir) [Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go) [PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php) [Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py) [Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)

* Receive sms [C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/receive-sms) [Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir) [Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go) [PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php) [Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py) [Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)

* Make phone calls [C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/send-sms) [Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir) [Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go) [PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php) [Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py) [Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)

* Receive phone calls [C#](https://github.com/46elks-getting-started/tree/master/code%20samples/C%23/send-sms) [Elixir](https://github.com/46elks-getting-started/tree/master/code%20samples/elixir) [Go](https://github.com/46elks-getting-started/tree/master/code%20samples/go) [PHP](https://github.com/46elks-getting-started/tree/master/code%20samples/php) [Python](https://github.com/46elks-getting-started/tree/master/code%20samples/py) [Ruby](https://github.com/46elks-getting-started/tree/master/code%20samples/ruby)


### Build an interactive voice menu or response (IVR)

Code examples & how-to in the [IVR samples collection](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/code%20samples/Voice%20-%20IVR%20-%20interactive%20voice%20menues).



## Demo applications

* [Smart support]()  
  Have one supportnumber; redirect it to different people different times of the day, or selected days of the week. Accept incoming sms from customers into your e-mail inbox with Zapier. ...and much more!

* [Two factor authentication]()

* [Elkme]()  
  Send textmessages from your terminal.

* [Sms game]()

* [Open sesame]()  
  Open gates at your local..  with an sms.

## Tutorials

* [Love messenger](https://github.com/gish/love-messenger)
* [Receive SMS into Google spreadsheet](https://medium.com/@46elks/receive-sms-into-google-spreadsheet-435b51393493#.9ku01h462)

Have you written a tutorial or created an app that you're willing to share?
Let us know at hello@46elks.com!


## Resources
* [Postman app](https://www.getpostman.com/) - interact with apis through a Chrome app, also available as an OSX app.
  
## Integrations
  * [Zapier](https://zapier.com/zapbook/46elks/)
  * [Microsoft Excel](https://excel.46elks.com/)
  * Google spreadsheet [Google Script code sample](https://github.com/46elks/SMStoGoogleSheets) | Tutorial: [Receive sms into Google spreadsheet](https://medium.com/@46elks/receive-sms-into-google-spreadsheet-435b51393493#.iu690j86w)

## Contributors
  THANK YOU!
  @{username} - Added sample code for...
  @{username} - Created
  
## Hackathons
  We are keen on helping out, and we'd be happy to help you with.. and credits for participants etc. [Talk to us](mailto:hello@46elks.com). We're also particularily interested in helping events and organizations working with teaching coding to beginners, initiatives that encourage diversety in IT, and among conferences. We enjoy meetups, let us know if you’d like for someone to come and hold a presentation about APIs - getting started with apis, how to send an sms in PHP/Python/Elixir/Ruby/Go...  We exist to help you build useful and cool things!

**Contact 46elks:**  
On twitter: [@46elks](https://twitter.com/46elks)  
Email: hello@46elks.com

## WIP
As with most things in life, this README is work in progress! It's a living document that changes as we improve.
Would you let us know if you see how it can be improved?
Feel free to open up a pullrequest, or send us a message at hello@46elks.com!

### Accessability 

#### Language

We have a dream, that this service should be super duper accessible to you, and a we think a first step is to localize this README. We'll try our best to write READMEs in all the languages we know. We'll ask our friends.  
Is your language missing? Can you help us out? If so; create a pull request, or e-mail us att hello@46elks.com!
