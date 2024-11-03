# Ruine

## Idée

### Concept

Une personne est connectée à un simulateur de crampes menstruelles et à un capteur de fréquences cardiaques. La douleur reçue va venir changer l'environnement du participant, tout selon le pouls de celle-ci. Les designs graphiques projetés sur le mur et l'éclairage sont modifiés tout dépendant des fréquences détectées. Ce qui rend le tout intéressant, c'est que toute personne recevant les douleurs peut réagir différemment et donc interagir avec la pièce de manière unique, bien sûr, avec certaines limites. De plus, les participants extérieurs (n'ayant pas le simulateur) pourraient avoir le contrôle des sons ambiants via un capteur de mouvement, ce qui rajoute du chaos à l'oeuvre. Cela mettrait en lumière l’idée que les douleurs menstruelles sont parfois mal comprises et incontrôlables. Le tout deviendra un environnement pour y faire comprendre l'impact nerveux d'une personne souffrante de crampes très douloureuses. À tout moment, la personne recevant les crampes pourra arrêter la simulation à l'aide d'un bouton.

### Objectifs

Le but est de faire comprendre ce qu’une personne aillant des crampes menstruelles ressent à chaques mois, autant physiquement que mentalement. L’idée est de placer quelqu’un qui n’en souffre pas dans la situation de celles et ceux qui en sont affectés. Il s’agit aussi d'**ouvrir la parole sur un sujet qui serait tabou.**.

### Motivations

- Mon expérience personnelle et celle de mon entourage.
- Le mouvement féministe.
- Le manque d'oeuvres interactives au mouvement féministe (Un domaine majoritairement homme).
- Le manque de recherches effectuées pour les cas tels que l'endométriose, le développement de contraceptifs aux symptômes minimisés, et ainsi de suite.
- *Female Rage*
- [Ada x](https://www.ada-x.org/):

>*"Ada X est un centre d’artistes féministe bilingue engagé dans l’exploration, la création et la réflexion critique en arts médiatiques et en culture numérique."*

## Scénario

- Note participant B: Plus il y a de participants B, plus il y a de chaos.

```mermaid
graph TD;
    A[veille]--Participant A-->B{Met le simulateur};
    
    B --Intercepte la douleur--> C[Réaction];
    
    C --Variations de douleurs --> D{Si tolérence grande};
    D --> G[Animations minimes, déformations visuelles]
    D --> J{Si veux arrêter};
    G --> J;
    

    C --Variations de douleurs --> E{Si tolérence moyenne};
    E --> H[Animations plus présentes, déformations visuelles];
    E --> J;
    H --> J;


    C --Variations de douleurs --> F{Si tolérence légère};
    F --> I[Animations plus présentes, déformations visuelles];
    F --> J;
    I --> J;
    

    J -- Presse le bouton arrêt --> K[Arrête le simulateur];
    K --> A;
    
    A --Participant B-->L{Se promène};
    L -- Passe devant capteur--> M[Changements];
    M --> N[Influance la réaction du Participant A];
    M --> O[Influe les ajouts et déformations de sons, et donc de chaos];
    O --> P{Part};
    L --> P;
    P --> A;
    
```

## Ambiance

### Planche d'ambiances visuelles

![Moodboard](/images/Moodboard.png)

### Planche d'ambiances sonores

#### Musique:
- [Universe of Fire Particles Falling from the Sky](https://www.youtube.com/watch?v=UdKfehqXZc0)
- [THE DAY WE LEFT FIELD](https://www.youtube.com/watch?v=oZAot9EZFM0&t=1s)
- [Oriens](https://www.youtube.com/watch?v=IC1x9fgReQ0)
- [Behind INEXISTENCE](https://www.youtube.com/watch?v=d7vyEsxvKpQ)
- [Atmospheric Experimental Sound Design](https://www.youtube.com/watch?v=3w7ay5LPtOY)

### Références artistiques

#### Exemples d'oeuvres inspirantes faites par des femmes:

- **[Eunoia](https://www.thelisapark.com/work/eunoia)** de [Lisa Park](https://www.thelisapark.com/)

![Eunoia](/images/Eunoia.png)
![Eunoia](/images/Eunoia_02.png)

- **[I dream of a soft oasis](https://www.rihabessayh.com/i-dream-of-a-soft-oasis-2022)** de [Rihab Essayh](https://www.rihabessayh.com/)

![oasis](images/softOasis.png)

- **[Freeing the Voice](https://imma.ie/collection/freeing-the-voice/)** de [Marina Abramović](https://fr.wikipedia.org/wiki/Marina_Abramovi%C4%87)

![Voice](images/FreeVoice.png)


#### Liens d'autres oeuvres multimédias servant d'inspirations au projet:

- [Machine hallucinations](https://refikanadol.com/works/machine-hallucinations-nature-dreams/) de Refik Anadol
- [Body Sculptures](https://clotmag.com/body-sculptures/stelarc) de STELARC
- [PainStation](https://www.youtube.com/watch?v=qMie0he1H7s) de Volker Morawe et Tilman Reiff
- [Pulse Room](https://www.lozano-hemmer.com/pulse_room.php) de Rafael Lozano-Hemmer
- [Heavy Duty Love for Future Sensitive Humans](https://www.ngv.vic.gov.au/exhibition/lucy-mcrae/) de Lucy McRae
- [Infinity Room](https://refikanadol.com/works/infinity-room/) de Refik Anadol
- [Universe of Fire Particles Falling from the Sky](https://www.teamlab.art/ew/universe_fireparticles_falling/planets/) de Teamlab
- [TOUCH](https://studioroosegaarde.net/project/touch) de Studio Roosegaarde
- [PSYCH.E](https://en.36degres.art/psych-e) exposition expérience mise en place par 36 degrés et la Galerie Charlot

## Technologies

### Support médiatique

- Vidéos interactives, particules 3D de TouchDesigner, modifications à partir des fréquences cardiaques.
- Interactivité sonore, ambiances stéréos, modification à l'aide de capteurs.

### Matériel
- Simulateur de muscles TENS

![Tens_02](/images/tensunit_02.png)

- Capteur de fréquences cardiaques

![Heartrate](/images/heartrate.png)

- Speakers
- Projecteurs
- Lumières
- Bouton
- Cables
- Ordinateur portable
- Chaise
- Une salle

### Logiciels

|Arduino|TouchDesigner|Reaper|Logic Pro|
|----|----|----|----|
|![Arduino](/images/arduino-logo.png)|![TouchDesigner](/images/TouchDesigner_logo.png)|![Reaper](/images/REAPER_logo.png)|![LogicPro](/images/Logic_Pro_icon.png)|

# Planification

## Modifications apportés

### Notes

- **Modification** par rapport à la prise de données du participant A: Fréquence cardiaque **prise plus simplement à l'aide d'un kit PulseSensor** et programmation dans Arduino détaillée et documentée. Le participant met le bout de son doigt sur le sensor et ainsi on peut avoir des données assez précises, comme indiqué dans la documentation de leur [site PulseSensor.com](https://pulsesensor.com/).

## Scénarimage

![Scenarimage legende](images/scenarimage_legende.jpg)

![Scenarimage 1-4](images/scenarimage_1-4.jpg)

![Scenarimage 5-8](images/scenarimage_5-8.jpg)

## Simulation

![Simulation 1](images/Ruine_simulation_view1.png)
![Simulation 1](images/Ruine_simulation_view2.png)
![Simulation 1](images/Ruine_simulation_view2.png)

- Modèle 3D utilisé: [Person](https://sketchfab.com/3d-models/person-9033c37ccf394abe97f48021c393cc56) par jDunn

## Synoptique
```mermaid
graph TD;
    
    A[Chariot/ordis]--->|DMX XLR|B[Spot];
    B--->C[Projette lumière pour illuminer la table];
    A---> D[Atom5];
    D -.- A;

    A--->|HDMI|E[Projecteur 1];
    E--->F[Projette à droite];

    A--->|HDMI|G[Projecteur 2];
    G--->H[Projette au centre];

    A--->|HDMI|I[Projecteur 3];
    I--->J[Projette à gauche];

    D--->|PulseSensor|K[Capteur fréquence cardiaque];
    K--->L[Prends le pouls du participant A];
    L-.-|Données|D;

    A--->|USB à USB-C|M[Simulateur de crampes];
    M--->N[Envoie douleur à Participant A]
  
    D--->O[Key Unit/BTN stop];
    O--->P[Arrête le simulateur]
    P-.->M;
    O-.-D;

    D--->Q[Capteur TOF/distance x3];
    Q--->R[Capte la distance du participant B];
    R-.-D;
    
    A--->S[Carte de son];
    S--->T[Speaker gauche];
    T--->U[Son Stereo Gauche]

    S--->V[Speaker droit];
    V--->W[Son stereo Droit];

```

## Plantation
### Dessus
![Top](images/top.png)
### Côté
![Side](images/side.png)
### Devant
![Front](images/front.png)

## Devis technique

### Vidéo
- 3x Murs/écrans
- 3x Projecteurs
- Cables au besoin

### Audio

- 2x Hauts-parleurs
- 1x Carte de son
- Cables audios

### Éclairage

- 1x Spot
- Cables pour éclairage

### Captations

- 3x Capteurs de distance TOF fournis par l'école
- Atom5 fournis par l'école
- Key Unit fournis par l'école

-Un ordinateur/chariot fournis par l'école

### Simulateur de crampes

- 1x Système de simulation de crampes menstruelles TENS
- Cables USB à USB-C ou celui au besoin selon le modèle TENS

[PDF sur la création d'un système de simulation de crampes menstruelles](https://www.jstage.jst.go.jp/article/jrobomech/33/5/33_1051/_pdf)

Dans le document, Il est expliqué qu'un Power Supply est connecté à un Control Board contrôlé par Arduino, ce Control Board est relié par deux électrodes qui envoient des pulsions musculaires au bas-ventre et simulent les crampes. Ce système peut aussi être lié à Unity pour coder la puissance électrique.

```mermaid
graph TD;
    
    A[Power Supply] ---> C[Control Board];
    B[Arduino] ---> C;
    C---> D[2x Electrodes];
    D---> E[Participant A];

```

>The power supply used was P4K36-1 (Matsusada Precision Inc., Japan) with voltage control. The voltage was set to be updated every 0.1 s using the supplied SDK and Unity to change the strength of electrical stimulation.

- Problématiques: très risqué de faire le simulateur pas soi-même.
- Solution: Prendre un simulateur déjà existant et trouver le moyen d'utiliser la notion apprise pour recréer les cycles de douleurs à l'aide de Unity et Arduino.

**À Noter**
- Selon un [article sur Reddit](https://www.reddit.com/r/TwoXChromosomes/comments/wnr46u/using_a_tens_device_to_simulate_period_cramps/) un utilisateur met ses settings à **SD2 WIDTH 50 μs 36 Hz** et un autre explique de ne pas mettre les électrodes proches du coeur.
- Faire attention au courant qui passe, trouver des matériaux en plastique ou en caoutchouc plutôt qu'en métal afin d'éviter une catastrophe ?

![Tens_01](/images/tensunit.png)
[Lien](https://www.amazon.ca/%C3%89lectrostimulateur-musculaire-rechargeable-g%C3%A9n%C3%A9ration-%C3%A9lectrodes/dp/B07795GZS4/ref=sr_1_4_sspa?__mk_fr_CA=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=ODI3FH3G7SX0&dib=eyJ2IjoiMSJ9.DsshipwxMCJ9cegYk4f-ysu2Q2kfUJGDWKRGyXUJ2pyp__nlgQA0YNacWzMjRRRkVvOWZO71WRu6ZeFy-B51iOW_hMls4t3P0J_SdsbULNXQGTpARmdfXs8LcRKhkSXqHHgI6GvL1oBvKgWwgjWzsrL_Rvex86-juE9w8kEmFlYzI0ytrRUGt8HfvF9BZItfgE1bq5Ftd62TWdVhWWia9hDVMgD2cSBPnErbhPXP4TcIsr9EvcYQHG_JbtqoyenqaaTCK0PDPLAbd1frWpgBt5_gfofIYU7BNW43Scyq7Hk.o0p0uQz1TkEEH1LH1epNQUIyxcX3MrhlcvFm4yQ44pA&dib_tag=se&keywords=auvon&qid=1730584064&sprefix=auvon%2Caps%2C88&sr=8-4-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)

### Capteur de fréquence cardiaque

Le capteur cardiaque peut être emprunté à l'école selon le cours d'Espace Interactif.

Sinon, le site [site PulseSensor.com](https://pulsesensor.com/) montre leurs matériels et les possibilités offertes pour la captation de fréquences cardiaques.

**Ce que le site fournit:**
- Prix de leurs produits.
- Codes Arduinos.
- Documentation détaillée.

![PulseSensor](/images/plusesensorfullkit.png)

## Coûts de matériel à acheter

|Matériel|Coût|
|----|----|
|Tens|~39,99$|
|PulseSensor|~42$|
|Total|~82$-92$|  

## Sécurité
Selon **[ChatGPT](https://openai.com/index/chatgpt/)**, afin d'assurer la sécurité autant des participants que celle du projet, il faut suivre quelques étapes importantes.

![Règlementations 1](images/chat_gpt_regl.png)
![Règlementations 1](images/chat_gpt_regl_2.png)
![Règlementations 1](images/chat_gpt_regl_3.png)
![Règlementations 1](images/chat_gpt_regl_4.png)

## Sources

### Recherches pour la conception:
- https://www.serwah.xyz/digital-art
- https://www.thelisapark.com/work/eunoia
- https://www.thelisapark.com/
- https://www.lozano-hemmer.com/pulse_island.php
- https://www.wikiart.org/fr/marina-abramovic
- https://imma.ie/collection/freeing-the-voice/
- https://fisheyeimmersive.com/article/art-numerique-quand-les-femmes-questionnent-le-sexe/
- https://www.ada-x.org/
- https://htmlles.net/
- https://www.ada-x.org/activities/exposition-lorraine-oades/
- https://www.ada-x.org/activities/unfolding-sequences-ima-pico/
- https://www.ada-x.org/activities/pas-dapparat-corps/
- https://www.ada-x.org/activities/les-larmes-evaporees-des-roses-de-sable-rihab-essayh/

### Vidéos pour la conception:

- https://www.youtube.com/watch?v=UdKfehqXZc0
- https://www.youtube.com/watch?v=4XeSs9a1rLQ&list=PLBBz6wzKh2tMFQ-kCNZKN96oCJCIcehtk
- https://www.youtube.com/watch?v=Tu0psLnYyW4&list=PLBBz6wzKh2tMFQ-kCNZKN96oCJCIcehtk&index=7
- https://www.youtube.com/watch?v=d7vyEsxvKpQ&list=PLBBz6wzKh2tMFQ-kCNZKN96oCJCIcehtk&index=10
- https://www.youtube.com/watch?v=50UKqoiqf3k&list=PLBBz6wzKh2tMFQ-kCNZKN96oCJCIcehtk&index=11
- https://www.youtube.com/watch?v=3w7ay5LPtOY&list=PLBBz6wzKh2tMFQ-kCNZKN96oCJCIcehtk&index=12
- https://www.youtube.com/watch?v=PuiWm2Lb-hk
- https://www.youtube.com/watch?v=qMie0he1H7s
