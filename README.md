# Machinaal Leren: Project 
### (Bram Breda - Maxime Van Hees - Ewoud Allart)

## Formatten van de features
- [x] rank
- [x] restaurant name : DELETED
- [x] general rating
- [x] number of reviews
- [x] tags
- [x] address
- [x] phone number
- [x] website url
- [x] menu url
- [x] timetable	
- [x] email address
- [x] travelers choice
- [x] michelin
- [x] food rating	
- [x] service rating	
- [x] value rating	
- [x] atmosphere rating	
- [ ] description
- [ ] dutch description	
- [x] price range
- [x] cuisines
- [x] special diets
- [x] meals	
- [x] restaurant features	

## Ideeën / TODO's :
* Volledige cleanening van de dataset
  - Wat doen met outliers?
  - Zelf features aanpassen? 
  
* Histogrammen van numerische datatypes
* Correlatiematrix opstellen tussen belangrijkste features
* Scatterplots?

* Mogelijke ideeën om interessante inzichten te verkrijgen over de data:

- Voorbeelden van op project-uitleg:
  - Are there substantial price or cuisine differences between cities?
  - Is there a between the review score and the price?
  - Is there a between rank and review score or other attributes?
  - If you want to open a restaurant, how would you design your restaurant to be the most profitable?
    - What kind of restaurants is most popular?
    - How can you beat other competitors?
    - Find similar restaurants.
  - Extract keywords from reviews / descriptions
  - Perform sentiment analysis on a review
  - Automatically make a list of positive and negative points for a listing based on the reviews

- Verdere uitbreidingen:
  - Heatmap die goedkope/dure restaurant regio's aantoont?
  - Mischien de prijsklasses anders verdelen want nu zitten bijna alle restaurants in dezelfde prijsklasse - eventueel via 'tags' kolom met de dollartekens, dis is ook vaker ingevuld
  - Kijk naar de gemiddelde review score per restaurant per jaar of maand
    - Welke restaurants zijn er op vooruit gegaan?
    - Welke restaurants zijn er op achteruit gegaan?
  - Reviews naar nederlands vertalen vooralleer we er keywords uit gaan halen - enkel als dit performant genoeg kan want er zijn meer dan 1 mil reviews 
  - ligt de gemiddelde score van restaurants die vegan/vegetarian friendly zijn hoger dan wanneer ze dit niet zijn? 
  - Welke restaurant features leiden tot een hogere review score? 
  - Welke prijsklasses zorgen voor de meeste reviews (en dus ook meer klanten vermoed ik?)
  - Welke keukens zorgen voor de meeste reviews (en dus ook meer klanten vermoed ik?) 
  - Welke keukens zorgen voor de beste scores - wat eten de mensen in belgië dus het liefst?
  - Als de menukaart van een restaurant online staat, zorgt dit er dan voor dat er meer klanten gaan eten in dat restaurant?
  
 
#### BELANGRIJK: alles moet ook duidelijk (tekstueel) worden uitgelegd

## Logboek
- 14/10 het field meals is verwerkt tot bruikbare data + cuisines is klaar om verwerkt te worden, er zijn echter wel veel categorieen, er is een boxplot opgesteld die aantoond dat veel cateogrieen niet veel voorkomen die kunnen we reduceren tot bv. `andere`
- 15/10 restaurant features voorgesteld, special diets data voorgesteld

## Reference
https://www.kaggle.com/code/russellpecar/tripadvisor-restaurant-data-cleaning-and-eda?fbclid=IwAR0ZysqEXJYYVLRlVftanWCqDt-B7gwMBxeNaJ0zNXAdpSV5lHZ2utnJw-I
https://blog.jovian.ai/analyzing-1-million-european-restaurants-from-tripadvisor-9ef5d1b690a2
