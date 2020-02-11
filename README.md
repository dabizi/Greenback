# Greenback

Welcome,
you'll find here the sources and code of the calculation made by the Greenback app.

You can download the app here : https://play.google.com/store/apps/details?id=com.greenback.janin.v0_05&hl=fr

Currently, the app is available on the Playstore. I'm converting it from java to javascript and will upload the contents in javascript as I progress through this conversion.
This is the reason why the code is not available here yet.

Total of carbon emission for each area of the world
https://ourworldindata.org/contributed-most-global-co2

Sources
MOD PLANE :

1) AIRLINE INDEX 2018 - https://www.atmosfair.de/wp-content/uploads/aai2018-englischsw.pdf

2) Footprint of flights - https://www.epa.gov/sites/production/files/2018-03/documents/emission-factors_mar_2018_0.pdf (three different type of distance available 
-> results not perfect, on various situations, a direct flight has a higher footprint when compared to one with connection. Last modified 9 march 2018

3) Calculating the Carbon Footprint from Different Classes of Air Travel - http://documents.worldbank.org/curated/en/141851468168853188/pdf/WPS6471.pdf (Worldbank)

(Interesting but in French : 
https://www.lemonde.fr/m-perso/article/2019/02/22/l-avion-plaisir-coupable-de-l-ecolo-voyageur_5426851_4497916.html
https://www.mangoandsalt.com/2019/03/01/empreinte-carbone-5-conseils-pour-voyager-plus-vert/
https://www.lemonde.fr/planete/article/2019/03/04/les-gestes-a-adopter-pour-moins-polluer-en-avion_5430958_3244.html)


MOD FOOD :
1) Footprint per type of food (without transport) - https://www.bbc.com/news/science-environment-46459714 (Based on Poore & Nemecek 2018, published in Science 
-> https://josephpoore.com/Science%20360%206392%20987%20-%20Accepted%20Manuscript.pdf)

MOD CLOTHES :
1) Footprint per type of clothes - https://www.ademe.fr/sites/default/files/assets/documents/acv-biens-equipements-201809-rapport.pdf



More :
Great animation of cumulative CO2 emissions since 1750 per countries (updated in 2019).
https://twitter.com/CarbonBrief/status/1120715988532629506

https://www.lemonde.fr/planete/article/2019/04/11/combien-de-co2-pourrez-vous-emettre-dans-votre-vie-si-le-rechauffement-est-contenu-a-1-5-degre_5448606_3244.html



# Use of React-Navive
npm install -g expo-cli

New project : expo init <name>
  
List of available emulator : emulator -avd 

move to folder then : expo start




# Source for app design :
Video :
https://www.youtube.com/watch?v=RT5h-lLH0QA

Color gradient :
3ADB3A -> 206F20

Background :
https://unsplash.com/photos/0lHIMPhRtN8
https://unsplash.com/photos/dEOC8M_lmxI
https://unsplash.com/photos/QsWG0kjPQRY


Coalition for Rainforest Nation, effectiveness
https://founderspledge.com/stories/climate-change-executive-summary
According to our cost-effectiveness model, a donation to CfRN will avert a tonne of CO2e for $0.12, with a plausible range of $0.02 - $0.72. Equivalently, a $100 donation to CfRN would avert ~857 tonnes of CO2e with a range of ~138 tonnes to ~4,600 tonnes. These estimates are highly uncertain. For context, the average person in the UK causes the emission of around 10 tonnes of CO2 per year, and it is generally considered to be difficult to avert a tonne of CO2e for less than $2. 



Internet :

Top tips to reduce your digital carbon footprint:
Always use Wi-Fi over 3G or 4G – this is the more environmentally friendly option, with 4G requiring almost 8 times more energy than Wi-Fi

Unsubscribe from any spam/junk emails even if you don’t open them – Unopened spam emails still use 0.3g of carbon dioxide
Source : https://www.openaccessgovernment.org/carbon-footprint/70917/

-----------

60,000 searches made on Google every second. Combine that with the fact that the average search produces around 0.2g of CO2 and the quantity of emissions is quite remarkable.

According to ‘internet live stats’, there are more than 2.5 million emails sent every second with a “everyday” email emitting 4g of CO2. That is quite astonishing. Especially when they also say that around 67% off all emails are spam. Anti-virus specialists, McAfee, say that this number is even higher, reporting that a remarkable 78% of all incoming emails are spam and that approximately 62 trillion spam messages are sent every year.

Facebook say that their annual per-user carbon emissions is 299g of CO2, which is less than making 1 latte or boiling 1 pot of tea. This is quite an achievement, but when there are so many people using the site, it still adds up to a lot of emissions.

Twitter
Raffi Krikorian, a developer at Twitter once stated that each tweet consumes around 90 joules, equalling 0.02g of CO2 emissions. Hardly anything right? Correct, however there are approximately 8,000 tweets written and published every single second.

Youtube
An article in the Guardian revealed that 1g of CO2 was emitted for every 10 minutes of YouTube watched or 0.0017g per second. That’s right, so the next time you’re up late at night watching funny cat videos, remember that those adorable, cute and cuddly fur balls mean you are contributing to the breakdown of the Ozone layer.
https://www.creditangel.co.uk/blog/consumption-and-carbon-footprint-of-the-internet

--------

The Cost of Music is a joint venture between the University of Glasgow and the University of Oslo, and warns that the energy used to store and stream digital media is just as harmful for the environment as plastic waste.[...]

The study found that while music has never been cheaper to own – a vinyl record in 1977 cost an average of $28.55 in today’s money while a digital download in 2013 cost $11.11 – the amount people were willing to spend on music in those years dropped from 4.83% of their salary a week to 1.22%.

https://www.factmag.com/2019/04/09/streaming-music-emissions-study/

-----------


Netflix se défend de contribuer massivement aux émissions de gaz à de serre. Selon son analyse publiée en 2015, un client a une empreinte carbone de seulement 300 g de CO2 / an et ajoute que ses infrastructures émettent 0,5 g de CO2 équivalent pour une heure de streaming. Et s'en amuse : "En moyenne la respiration humaine émet environ 40g par heure, près de 100 fois plus. Rester immobile en regardant Netflix économise probablement plus de CO2 que Netflix n'en brûle." 
https://www.notre-planete.info/actualites/247-streaming-emissions-CO2

----------

•La vidéo est un support d’informations dense : 10h de film haute
définition, c’est davantage de données
que l’intégralité des articles en anglais
de Wikipédia en format texte !
•Le visionnage de vidéos en ligne a
généré en 2018 plus de 300 MtCO2,
soit autant de gaz à effet de serre que
l’Espagne, ou près de 1 % des émissions mondiales.
•Les vidéos pornographiques constituent 27 % de tout le trafic vidéo en
ligne dans le monde. Elles ont généré
à elles seules en 2018 plus de 80 MtCO2
,
soit autant que l’habitat en France, ou
près de 0,2 % des émissions mondiales.
•Les émissions de gaz à effet de
serre des services de vidéo à la
demande (de type Netflix ou Amazon Prime) équivalent à celles d’un
pays comme le Chili (plus de 100
MtCO2
eq/an, soit près de 0,3 % des
émissions mondiales), qui accueille la
COP25 en 2019.

https://theshiftproject.org/wp-content/uploads/2019/07/R%C3%A9sum%C3%A9-aux-d%C3%A9cideurs_FR_Linsoutenable-usage-de-la-vid%C3%A9o-en-ligne.pdf


-----
https://addons.mozilla.org/fr/firefox/addon/carbonalyser/

--------
https://theshiftproject.org/wp-content/uploads/2019/09/Guide-R%C3%A9duire-le-poids-de-vos-vid%C3%A9os-en-5-minutes_V6.pdf

--------

http://www.clickclean.org/france/fr/

--------

A report from the Department of Energy’s Lawrence Berkeley National Laboratory figures that those data centers use an enormous amount of energy — some 70 billion kilowatt hours per year. That amounts to 1.8% of total American electricity consumption. At an average cost of 10 cents per kwh, the annual cost of all that juice is on the order of $7 billion.

Seventy billion kilowatt hours is such a giant number that it’s helpful to put it into some other terms. For comparison purposes, 1 kwh is enough power to keep ten 100-watt lightbulbs illuminated for one hour, or to keep your smartphone charged for an entire year. To generate 70 billion kwh you’d need power plants with a baseload capacity of 8,000 megawatts — equivalent to about 8 big nuclear reactors, or twice the output of all the nation’s solar panels.

Sliced up per capita, the average American uses about 200 kwh a year for his or her internet use, costing about $20. For those of you obsessed with carbon footprints, your internet use is responsible for the emission of about 300 pounds of carbon dioxide per year.

(Edit. One for the Green Techies – Food for thought isn’t it. So next time you recharge your phone just remember how much green house gas you are generating.)

But our internet addiction is only growing. According to Nielsen, the average adult in the United States spends 10 hours and 39 minutes a day consuming digital media. That’s up an hour a day in the past year. And we’re spending most of that additional time peering at our smart phones, which now occupy us for an hour and a half each day.
https://www.thebyte.com.au/it-takes-70-billion-kilowatt-hours-a-year-to-run-the-internet/

