# PM - Gridlayout och API
## Introduktion
Min hemsida är ett grid av halloween bilder och en sida med information om ett land. 

## Validationer
HTML valideringen på [validator.nu](validator.nu) gav error i varje source-tag bredvid bilderna för att jag inte hade rätt typ av storlek i srcset. De bildtagarna skapas av 11ty så jag vet inte hur det ska fixas, plus så sätts bildstorlekarna av CSS så jag tycker inte att det här är ett stort problem. Validatorn ger ingen annan varning eller error. 

CSS valideringen på [Jigsaw](https://jigsaw.w3.org/css-validator/) hittar inga fel. 

WAVE ger ingen error eller contrast error. 

Jag vet inte hur man validerar med a11ty så jag kan inte göra det nu. 

## Slutord
Grid sidan blev bra tyckte jag, den kunde göras utan problem. Jag har lärt mig mer om hur grid fungerar. 

Landsidan visar info om ett land vilket på den aspekten så fungerar det bra, men det blev inte direkt som jag ville. Jag ville egentligen att det skulle visa ett helt random land varje gång man laddar sidan eller att man skulle kunna välja, dock efter mycket testande och googling så fick jag det inte att fungera och bara lämnade att visa ett land. Landet som visas bestämms genom en randomisering som körs varje gång Netlify/filen sparas. 

Navbaren blev lite rushad för jag hade missförstått uppgiften och därför slängde jag ihop navbaren snabbt. 