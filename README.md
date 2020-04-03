# hackthecrisis
status46.se &amp; VABomaten

Jag har två projektidéer till Hack the Crisis.
"status46" och VABomaten


## status46.se 
Montitoring peoples health by broadcasting questions over sms to all mobile phones in a specific area 📲 once per day. People can answer with just one word like good, bad, cold, fever or give a more detailed response. They can even reply with an emoji. The data that comes in would be collected to properly visualize how people in the area are feeling, and how that's developing over time. And how the course of the disease ("sjukdomsförloppet") is for many people. Anyone who replies they're sick can be asked about how they're feeling multiple times per day to get more relevant data. Depending on what you reply you'd either get a thank you  for reporting (if you're feeling :ok_hand::skin-tone-4:), or if you've mentioned fever (:face_with_thermometer:) then you'd get a few follow up questions; do you have any other symptoms? Is there anything you'd like help with? .. if they reply yes, then send them information about all the existing ways/initiatives where they can ask for help (the solution could be developed to ask a few other people in the same area that replied :ok_hand::skin-tone-4: that day, if they're willing to help someone out who lives nearby and is sick today. People that don't wish to be tracked can simply not reply, or clearly answer "stop asking me", and we wouldn't as again.

**Background:** I would be happy to provide data about how I'm feeling, if it was easy to do. I've been sick myself and I'm guessing it was Corona because of the symptoms, and I lacked an easy way to report this and to keep track of the "course of the disease" (sjukdomsförloppet). 

TODOs:
- [ ] landingpage 
- [ ] create a demo
  - [ ] setup a number
  - [ ] create conditions for how to interpret replies
  - [ ] setup different flows of what happens next depending on what the reply is
  - [ ] show examples of how replies can be agregated and visualized
  - [ ] create a video explaining this
- [ ] handle integrity issues

Detail: An option would be that people go to status46.se and fill out their phonenumber to start receiving questions each day, but then that would require lots of work on communicating the existance of this setup.


## VABomaten
Reporting VAB to work + Försäkringskassan is such a hassle, as if taking care of a child wasn't enough. Throughout this crisis a lot of people are, and will be reporting VAB, and the accumulated effort is such a waste of time and energy. So, here's VABomaten! You send in a message to the VAB-omat through mail, sms or slack.

For example:
**If you have 1 child**
- **VAB** -> VAB, 100%, idag, ditt enda barn... -> email is sent to someone, or multiple people at work, a calendar event is setup for you, so that it's easy for you to go back and see which days you've reported VAB. You would also automatically get a summary if you ask VABomaten which days you've reported VAB previously.
- VAB, 50 -> VAB, 50% idag, {personnumret för ditt enda barn...}



**If you have two or more children**
- VAB Ingrid -> {follow up question: which child?} -> "ingrid" -> "VAB + ingrid" -> VAB, 100%, idag, {Ingrid -> 20200303-2481 ett av dina barns personnummer }
- VAB Ingrid -> [VAB, 100%, idag, {Ingrid -> 20200303-2481 ett av dina barns personnummer }] -> Sent to Försäkringskassan, send one ore multiple e-mails, update my calendar.

You activate VABomaten by entering your phone number/e-mail on the VAMomaten website (long term this would be run by Försäkringskassan), you'd then get a link to your phone/e-mail where you verify your identity using BANKID. Once that's setup you can start using VABomaten from that e-mail/phone number. You can recall permissions at any time.

TODOs:
- [ ] konfa sms_url på ett [46elksnummer](https://46elks.com/hackthecrisis)
- [ ] Sätt upp ett flöde i zapier för att snabbt få upp ett demo som uppdaterar din kalender och skickar ett mail, och gör ett POSTanrop till ett påhittat API hos Försäkringskassan.
- [ ] Speca förväntningar på API hos Försäkringskassan
- [ ] Skapa hemsida där en kan göra de inställningar en vill ha

Bonus om det hinns med:
- [ ] Få till koppling till BANKID


**jobbsamtal.se**
*Challenges by Business Region Göteborg*: 
- How can idle resources, like people and vehicles, in one sector be matched against the increased demand in another sector? 
- How can we motivate people to exercise in a safe manner during the crisis?

Jo! Du spelar in ditt CV och ansöker om jobb genom att ringa in. Den som har ett jobb som behöver utföras kan enkelt beskriva det och låta den som vill ansöka genom att ringa in och lämna ett meddelande. 
Den som söker folk kan då lyssna på ansökningar samtidigt som hen rör på kroppen. Framförallt kan du som söker jobbet svara på frågor och berätta om erfarenheter du har som är relevanta för jobbet utan att stressa över att få till ett snyggt CV. Den som tar emot ansökningar kan också vlja att få alla dessa som PDF-dokument, (speach to text) för att snabbt kunna skumma igenom flera ansökningar. 
