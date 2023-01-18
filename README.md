# AI's NEW FRONTIER is called Chat-GPT

***********

<img align="right" width="300" height="300" src="https://avatars.githubusercontent.com/u/115706761?s=400&u=7c6cae892816e172b0b7eef99f2d32adb948c6ad&v=4">

# PROMETHEUS <br /> DATA SCIENCE LAB


***********


## Context & Doel

Exemplarisch voor AI anno 2023 is de lerende machine [ML] genaamd [ChatGPT](https://chat.openai.com/). Een state-of-the-art, grootschalig taalmodel [LLM] dat gebruik maakt van natuurlijke taalverwerkende [NLP] AI-technologie. 

Het is gevoed met meer dan 8 miljoen unieke dialogen.
ChatGPT’s gebruikersinterface is ontworpen om menselijke conversatie na te bootsen. Het revolutionaire aan deze AI-technologie zijn de ogenschijnlijk levensechte gesprekken die het kan onderhouden met mensen.

<br>

Deze GitHub repository is een primer met bijsluiter dat op basis van <i>prompt</i> voorbeelden  demonstreert hoe ChatCPT werkt.

<!--

```mermaid
```mermaid
flowchart LR

id1[Deze GitHub repository is een primer met bijsluiter dat op basis van <i>PROMPT</i> voorbeelden  demonstreert hoe ChatCPT werkt.]

```

-->
<br /> <br /> 


<img align="left" width="200" height="300" src="https://user-images.githubusercontent.com/684692/212558117-0445bc99-5ef7-438c-9421-e758f64473da.jpg">


<br>

>Stel je een computer voor die jouw zinnen kan afmaken met een betere zinswending;  of een gesprek met je kan voeren over een thema dat jouw interesseert; of een probleem direct kan oplossen door honderden regels computercode te schrijven binnen enkele seconden. Een dergelijke computer vormt een schakel in een lange keten van werktuigen zoals het weefgetouw, de boekdrukpers en de stoommachine die de industriële revolutie opgang brachten. Tegelijkertijd is het onderdeel van een nieuwe klasse aan _lerende machines_, omdat het de symbolen in taal omzet & computercode schrijft op manieren die creatief lijken. Een beetje zoals een mens dat zou doen. 




<br><br><br><br>

*******
### [1] HOE LEREN COMPUTERS EEN GESPREK TE VOEREN?
*******


Een taalvaardig AI-model kan worden "gevraagd" om een taak uit te voeren op basis van tekstuele instructies. <br > Dit heet  *"prompting"* of *"priming"* in het Engelse taaldomein. 

Dit proces is vergelijkbaar met een Google zoekopdracht. <br> Het verschil is dat de uitkomst nu niet een verwijzing moet zijn naar een reeks relevante webpagina's, <br> maar een antwoord zoals een mens dat zou geven.

Om hieraan te voldoen moet de chatbot eerst worden getraind aan de hand van een grote hoeveelheid 
voorbeelden van deze taak in combinatie met menselijke feedback

Binnen het AI-domain wordt dit proces *"reinfored learning"* genoemd. <br> Het is een proces waarbij een taalmodel wordt aangepast aan een specifieke taak. <br> In dit geval het voeren van een gesprek.

<br>

<div style="float:center;">

```mermaid
---
title: [ChatGPT volgt menselijke instructies]
---
classDiagram
DataBase --|> Mens
DataBase : PROMPT
Mens --|> ChatGPT
Mens : Instructie
ChatGPT : Fine tunning
Stap01  --|> Stap02
Stap01 : selecteer een taak
Stap01 : uit dialoog-dataset
Stap02 : demonstreer de 
Stap02 : gewenste uitkomst
Stap02 --|> Stap03
Stap03 : Promt + Uitkomst wordt
Stap03 : opgeslagen door
Stap03 : het taal model
Voorbeeld01 --|> Voorbeeld02
Voorbeeld02 --|> Voorbeeld03
Voorbeeld01 : Leg uit wat een paard is
Voorbeeld01 : aan een Biologie student
Voorbeeld02 : Een paard is een viervoetig zoogdier ...
Voorbeeld03 : Het door de mens vervaardigde antwoord
Voorbeeld03 : fungeert als instructief voorbeeld  voor het model
Voorbeeld03 : hoe het dient reageren op een prompt
```


<br> <br>

Geraadpleegde bronnen: 
* Ouyang, L., Wu, J., Jiang, X., Almeida, D., Wainwright, C. L., Mishkin, P., Zhang, C., Agarwal, S., Slama, K., & Ray, A. (2022). Training language models to follow instructions with human feedback. arXiv. https://doi.org/10.48550/arXiv.2203.02155 
* OpenAI Guthub Repository: InstructGPT [Training Language Models to Follow Instructions with Human Feedback.](https://github.com/openai/following-instructions-human-feedback)

<br>

********
### [2] HOE GEEF IK EEN OPDRACHT AAN CHATGPT?

********

<img align="right" width="600" height="400" src="https://user-images.githubusercontent.com/684692/212562846-e56214b4-2f95-452f-a1b8-ee8adfb37079.gif">

ChatGPT maakt gebruik van  *"prompting"* of *"priming"*. 

De prompt is de vraag , het verzoek of de vraag van de gebruiker in tekst-vorm. 

De prompt wordt vervolgens doorgegeven aan het model, die op zijn beurt hier op reageert in text-vorm, waarbij de gegenereerde tekst beetje bij beetje wordt vrijgegeven. 

De eindgebruiker krijgt zo de indruk dat het AI-model vragen beantwoordt en/of opdrachten uitvoert zoals een mens dat zou doen.


<br /> 

********
### Kan ChatGPT uitleggen wat het is?

********

```mermaid
sequenceDiagram
RF->>ChatGPT: note "Ben jij een voorbeeld van een generatief taalmodel AI?"
ChatGPT->>RF: "Ja, ik ben in staat om nieuwe tekst te genereren door het analyseren en leren van grote hoeveelheden aan tekst"
ChatGPT->>RF: "Ik kan antwoorden geven op vragen, tekst genereren  in verschillende stijlen en talen."
ChatGPT->>RF: "Ja, ik ben een voorbeeld van generatieve AI."
RF->>ChatGPT: "Ben jij een voorbeeld van een generatief taalmodel AI?" 
```




### PROMPT VOORBEELDEN


********


<img align="right" width="600" height="450" src="https://user-images.githubusercontent.com/684692/212640154-7a754bbe-61cf-4986-ac73-8e6a42c110b3.png">

<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />


<img align="right" width="600" height="450" src="https://user-images.githubusercontent.com/684692/212640177-747d0ab2-1852-4423-b27d-ef359e365407.png">


<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />


<img align="right" width="600" height="450" src="https://user-images.githubusercontent.com/684692/212640181-5dd706fb-a3c2-4f8c-a8ed-e339f4e37416.png">


<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />


<img align="right" width="600" height="450" src="https://user-images.githubusercontent.com/684692/212640182-2c972779-e064-4f74-ad62-82df78396ea9.png">


<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />






