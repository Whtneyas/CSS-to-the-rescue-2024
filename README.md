# CSS-to-the-rescue-2024
Dit is een project van school.

## Bedieningspaneel
Dit is een interactieve toepassing gemaakt in HTML en CSS.

## Week 1
### Concept
In week 1 kwam ik met een concept. Door op zoek te gaan naar inspiraties van modulaire ontwerpen die ik kan hermaken, kwam ik uiteindelijk op het idee van een camera.

### Schetsen
<img src="./imgs/WhatsApp%20Image%202024-03-15%20at%2011.11.50%20(1).jpeg" alt="Image Alt Text" width="500" height="500">

<img src="./imgs/WhatsApp%20Image%202024-03-15%20at%2011.11.50.jpeg" alt="Image Alt Text" width="500" height="500">



## Workshop - kleur hsl , rgb , oklch , display_p3
Tijdens deze workshop heb ik het verschil geleerd tussen de verschillende *kleurmodellen*. Ik heb een oefening gedaan waarbij het duidelijker werd wat elk kleurmodel doet.

### Notities ( Kleurpanelen)*

- HSL (Hue, Saturation, Lightness):

   - Hue: Representeert de kleur zelf, variërend van 0 tot 360 graden (rood tot rood).
   - Saturation: Beschrijft de intensiteit of zuiverheid van de kleur, variërend van 0% (grijstinten) tot 100% (volledig verzadigd).
   - Lightness: Geeft de helderheid van de kleur aan, waarbij 0% zwart is en 100% wit.


- RGB (Red, Green, Blue):
   - Rood, Groen en Blauw zijn additieve primaire kleuren, waarbij elk varieert van 0 tot 255 (of 0 tot 1 in sommige contexten).

- OKLCH (LCh, Lightness, Chroma, Hue):
   - Lightness: Vergelijkbaar met HSL, representeert helderheid van 0 (zwart) tot 100 (wit).
   - Chroma: Beschrijft de kleurrijkheid of verzadiging van de kleur.
   - Hue: Representeert het type kleur, vergelijkbaar met HSL.

Link naar codepen: https://codepen.io/Whitneyas/pen/vYMXBZa


## Ideeën en inspiraties?
- Piano
- Printer
- Desktop
- Wasmachine
- Camera (Voorkeur)

### Experimenting with gradients 
***

### Geexperimenteerd met tekstschaduw

Ik experimenteerde met hoe tekstschaduw werkt en hoe ik letters één voor één kan animeren. Ik begon te experimenteren in CodePen. Ik heb ook aantekeningen gemaakt over dingen die ik ontdekte over tekstschaduwen.

https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/e9b83d14-4f18-448a-a9ce-153eea122ae6


## WEEK 2 

In week 2 kreeg ik het idee om gordijnen toe te voegen die opengaan in mijn concept. Dus het idee is dat wanneer het gordijn opengaat, de titel verschijnt. Zowel de gordijnen als de tekst zouden geanimeerd worden. Ik volgde een typografie-workshop en tijdens deze workshop leerde ik hoe ik tekst kon animeren.

### Experimenten in CodePen - Gordijnen
Voordat ik het naar VSCode overzette, moest ik eerst experimenteren in CodePen om te zien of het werkt. Ik experimenteerde met gradients en animaties, hoe ik het kon animeren om te openen en te sluiten. De kennis die ik opdeed tijdens de typografie-workshop paste ik toe op mijn concept. Maar eerst heb ik het uitgeprobeerd in CodePen.
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/b343240e-439b-4267-b182-e1d25dc76c88)
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/eff69b4f-1dbb-4b15-a380-926981f4a3d5)

### Final results for the curtains and title 
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/2222ada5-92b1-4388-9ac1-9c8e2379cf8a)


Wat heb ik nu?

In codepen : https://codepen.io/Whitneyas/pen/mdgroxd

### Wat heb ik geleerd?
- Hoe tekst afzonderlijk te animeren door voor elke letter een span te gebruiken.
- Het gebruik van vw om componenten responsief te maken (was nieuw voor mij).
- Het gebruik van filter.

### Deciding on the structure of my camera 

Voordat ik besloot over de structuur van mijn camera, heb ik eerst mijn camera getekend en bedacht hoe ik wilde dat het eruit zou zien en welke onderdelen het zou bevatten. Met dit in gedachten zou de structuur er als volgt uitkomen:

![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/ffdea408-dc56-4723-9aaf-bc2087a625e0")
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/789059d4-6021-4029-8395-41f06ed3cf43)
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/494e353f-f22a-4c77-be6e-47bc2e99e723)
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/9f5c9949-06e5-4c51-b026-8a66d67ea7e4)


### Code structure
Ik twijfelde aan de structuur van mijn code voor de camera. Voordat ik begon, wilde ik de structuur vastleggen zodat het gemakkelijker voor me zou zijn om te beslissen welke eigenschappen ik wilde gebruiken en aan welk component ik eerst moest werken.
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/e666dcf9-2e39-41ec-aed8-e302c1500057)


## Week 3 
In week 3 i decided to work on the different parts of my camera. 

### Printer
Ik wilde dat de printer er realistischer uitzag, niet alleen als een rechthoek met een rand, maar als een meer realistische 3D-printer. Ik wist niet welke CSS-eigenschap ik moest gebruiken. Toen dacht ik aan de box-shadow met de inset-eigenschap, waarmee ik de schaduw binnen het element kon tekenen en het er realistischer uit kon laten zien. Ik had wat moeite om het er realistischer uit te laten zien, dus voegde ik meerdere insets toe en probeerde verschillende manieren uit totdat het eindelijk was zoals ik het wilde.

### First try 

Met deze heb ik geprobeerd om het onderste binnenste deel een schaduw te geven, waardoor het eruitzag als 2 dubbele balken binnenin het element.

![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/04d9836b-d1fe-4a00-b5aa-f490549c3bd4)

### Second try 
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/48eea535-b408-43f8-af7e-ecc9ebba1a83)

 ### Code for second try
 Nadat ik had geanalyseerd wat het probleem was, besloot ik om de schaduw die ik had toegevoegd aan het onderste binnenste deel van het element te verwijderen om het er realistischer uit te laten zien. 🥰

 ![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/52f23586-20a0-48ad-a4cd-99943ae0a86e)


 ### Turning label/input into clickable buttons



  ### Home screen with button icons
  ![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/ebcd3577-d66b-4bed-80a4-97abd2cd81bc)
  This is the homescreen i have in mind to make. 




  ### Fotoscherm .

 Ik wilde een activeringsknop toevoegen die de camera activeert. Om dit te laten gebeuren, moet ik JavaScript gebruiken. Dat is echter niet toegestaan in deze cursus, maar ik heb toch geprobeerd te zien hoe het zou uitpakken. Ik heb JavaScript gebruikt om dit te laten gebeuren, maar ik kon de camera niet positioneren in de container zoals ik wilde. Het kostte te veel tijd, dus besloot ik in plaats daarvan een camerabeleffect te creëren met alleen CSS.


### First tryout om de camera te activeren
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/0d3e5575-722d-461b-be2f-bae2356a7d8a)

### Code gebruikt 
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/0f40615c-cdaa-4f01-816a-932aa24ae23b)

![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/d4027166-536f-4358-8071-19e86c35bb0f)


  ### Galerij

   In het galerijscherm wilde ik een galerijalbum maken met een scrollanimatie, zodat ik soepel kan scrollen. Ik heb ook de galerij zo gemaakt dat wanneer je op een afbeelding klikt, je een grotere versie van de afbeelding aan de linkerkant krijgt.

Uitdaging: De enige moeilijkheid die ik heb, is om van de verticale scrollbar aan de linkerkant en de horizontale scrollbar aan de rechterkant af te komen. Ik heb geprobeerd overflow hidden te gebruiken, maar dan verbergt het de scrollbar zonder dat ik kan scrollen, en dat is niet wat ik wil. Ik kwam erachter dat het gebruik van overlay de scrollbar zou verbergen maar dat de scrollbar zijn functionaliteit niet zou verliezen. 

  ![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/39ccfa1b-5985-4f41-914d-40c37d1ce7b4)


### Voortganggesprek met Sanne 
Tijdens de voortgang gesprek heb ik met sanne besproken waar ik vast zit en wat kan beter. Sanne heeft tips gegeven hoe ik mijn code beter kan structuren door te refactoren. Ik was begonnen met een large screen ipv van een klein scherm dus mijn ontwerp is niet goed responsief. Samen met sanne heb ik mijn code doorgenomen waardoor sannen denkt dat sommige html en css code niet nodig zijn om te gebruiken dus daar ga ik ook eraan werken.  

Wat ga ik aanpakken 
- Eerst beginnen met het ontwerpen op een klein scherm
- Code refactoren
- Kleine dingentjes aanpassen

## Beginnen met een kleine scherm 
 Soms liep ik vast en moest ik urenlang zoeken naar wat er mis was. Ik heb alle styling in één bestandje gezet, maar binnenkort ga ik ze opsplitsen in verschillende mappen zodat het voor Sanne makkelijker wordt om mijn code te lezen.

 ### Camera werkt niet door de gordijn die ik boven op heb. 
 Omdat de gordijn bovenop staat en op hidden staat, werkt de camera niet. Ik weet niet ik hoe ik deze moet oplossen. Ik heb een gordijn gemaakt dat boven de camera staat. Ik heb een grid ingesteld voor de body en binnen de body heb ik de header (voor het gordijn) en in de main (de camera). Ik heb geprobeerd het gordijn geanimeerd te laten verdwijnen, maar dit heeft de werking van de camera beïnvloed. De knoppen van de camera werken niet omdat het gordijn erbovenop staat, ook al is het verborgen.

Ik heb geprobeerd om met z-index te werken, maar dan komt de camera boven het gordijn te staan. Ik heb Sanne om hulp gevraagd. Als hij niet op tijd kan helpen, zal ik een andere oplossing bedenken. De oplossing die ik momenteel heb, is om een aparte HTML-pagina te maken.
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/af95d339-31f4-47b3-970c-2ed3862bf21c)



  



  







### Resources
Images
- https://stock.adobe.com/nl/search/images?k=simple+cartoon+landscape&asset_id=79905462
  
Text shadows
- https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow

3d transoforms
- https://3dtransforms.desandro.com/3d-transform-functions
- https://3dtransforms.desandro.com/perspective
  

