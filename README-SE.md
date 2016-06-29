# 46elks - SMS & telefoniapi!
([Smsapi](https://46elks.com), [mmsapi](https://46elks.com), [voiceapi](https://46elks.com/link-to-details-about-voice) 

## Introduktion
Välkommen! 
Om du vill vill automatisera eller integrera telefoni in i dina rutiner, eller leka med sms, automatiskt ringa upp och informera användare om att flyget är försenat, eller skicka uppmuntran till nära och kära, då är 46elks api för dig.
{:Hur besvarar vi på bästa sätt varför 46elks api finns? Hur kan läsaren ha glädje av 46elks api? :}

### Snabblänkar (Viktiga länkar? Vad är en bra rubrik här?)

  * [Dokumentation](https://www.46elks.com/api-docs#introduction)(på engelska)
  * [Exempelkod](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/samples)
  * [Artiklar om API, Basic auth, and 46elks integrationer](46elks@medium)  << länkar till lista med resurser längre ner i denna README?
  * [Kontakta oss](46elks.com/help#contact) (Du kan ringa +46... :))

## Snabbstart
Med dina [46elks apinyckel](dashboard..)(Användarnamn och lösenord som du får gratis när du [skapar ditt 46elks-konto]()) kopiera in detta i terminalen:
``` curl -X POST \
  -u <API-Username>:<API-Password> \
  -H 'Content-Type: application/x-www-form-urlencoded' \
  -d 'from=VILLE' \
  -d 'to=+358503672181' \
  -d 'message=Test Message To your phone.' \
  'https://api.46elks.com/a1/SMS' ``` 

Du har nu skickat ett sms!

## Komma igång

1. Du behöver skapa ett konto för att kunna använda api:et. Du får ett användarnamn och ett lösenord (apinycklar(nyckel?)) som du använder när du gör anrop till apiet.
Du kan skapa ett konto gratis på [46elks.com/create-account](https://www.46elks.com/create-account). När du har dessa uppgifter ansluter du till api:et med [basic auth](46elks@medium article about basic auth).
2. *Dokumentation* finns [46elks.com/docs](https://46elks.com/docs#introduction).
3. Kodsnuttar med exempel finns här: *[Sample code](https://github.com/littlekid/testing-learning-to-create-a-good-getting-started-and-readme/tree/master/samples)*.

## Kodexempel
<< APIDOCS "Sample code" links to this location

### Skicka sms

[Elixir], [Go], [Ruby], [PHP]

  
### Ta emot SMS

[Elixir], [Ruby], [PHP]


### Ring ett samtal

[], [Ruby], [PHP]


### Ta emot samtal

[], [Ruby], [PHP]

### Bygg upp "_IVR_" (interactive voice response).

Vad är ivr? Det är....  Du kan läsa mer i denna ypperliga artikel: [medium](46elks@medium/What is ivr?)
{Länk till sample JSON i IVR mapp. Var placerar vi den mappen? I samma nivå som Språkmapparna?}

### Demo

Har du byggt något med 46elks api:et att visa upp? Hör av dig! :)

#### Smart support - Have one supportnumber; redirect it to different people different times of the day, or selected days of the week, accept incoming sms from customers into your e-mail inbox with Zapier, and reply to their e-mail if you have it on record, or reply to them via sms, by replying to the e-mail.

#### Two factor authentication

#### Elkme - Send textmessages from your terminal

#### Sms game at fair.

#### Open sesame - open gates at your local..  with an sms.

## Tutorials

* [Love messenger](https://github.com/gish/love-messenger)
* [Receive SMS into Google spreadsheet](https://medium.com/@46elks/receive-sms-into-google-spreadsheet-435b51393493#.9ku01h462)

## Resurser
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

## Svenska insatser
  THANK YOU!
  @{username} - Added sample code for...
  @{username} - Created
  Länk till all contributors --> Till #mainreadme!
  
  
## Hackathon
  Vi hjälper gärna till! Vi kan hjälpa dig med... och ... och ... Paket med krediter till deltagare. [Hör av dig](mailto:hello@46elks.com). We're also particualry interested in helping events and organizations working with teaching coding to beginners, initiatives that encourage diversety in IT, and among conferences. We enjoy meetups, let us know if you’d like for someone to come and hold a presentation about APIs - getting started with apis, how to send an sms in Elixir/Ruby/Go..  We exist to help you build useful and cool things!
  Say hi! Twitter: Uppsala: In Stockholm: In Göteborg: In Poland:

## WIP
As with most things in life, this README is work in progress! It's a living document that changes as we improve.


This source code is released as public domain. Use freely.
