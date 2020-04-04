# hackthecrisis
Jag har nu tre projektidéer till Hack the Crisis. **"status46"**, **VABomaten** och **jobbsamtal**

## status46
[status46](https://github.com/littlekid/status46) har fått eget [repo](https://github.com/littlekid/status46).
<br>

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


## **jobbsamtal.se**
*Challenges by Business Region Göteborg*: 
- How can idle resources, like people and vehicles, in one sector be matched against the increased demand in another sector? 
- How can we motivate people to exercise in a safe manner during the crisis?

Jo! Du spelar in ditt CV och ansöker om jobb genom att ringa in. Den som har ett jobb som behöver utföras kan enkelt beskriva det och låta den som vill ansöka genom att ringa in och lämna ett meddelande. 
Den som söker folk kan då lyssna på ansökningar samtidigt som hen rör på kroppen. Framförallt kan du som söker jobbet svara på frågor och berätta om erfarenheter du har som är relevanta för jobbet utan att stressa över att få till ett snyggt CV. Den som tar emot ansökningar kan också vlja att få alla dessa som PDF-dokument, (speach to text) för att snabbt kunna skumma igenom flera ansökningar. 


## Corona hotline
Ett nummer (0766866668) du kan ringa om du har frågor om Corona-läget.
https://46elks.com/hotline
Ex: 
Tryck 1 för att få höra senaste nyheterna och lagändringarna. 
Tryck 2 om du vill frivilligt vill rapportera in symptom. 
Har du frågor om VAB eller ersättning vid arbetslöshet? 
Tryck 3 så kopplar vi dig vidare till Försäkringskassan.

### Uppdaterad summerad viktig information (nyheter & bestämmelser)
Om det finns en textkälla, eller om FHM skapar en sida på sin hemsida med bara den texten så kan den scrape:as..) och sedan kan text to speach köras för att bygga en .mp3 varje gång texten har ändrats. Minimalt med arbete för FHM att få upp en text någonstans på sin hemsida.
´´´´
say -o hello.aiff -v 'Alex' 'Hello, my name is Alex'
open hello.aiff
´´´´
