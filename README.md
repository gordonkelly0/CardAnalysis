looking online for a dataset to look into, I found this AllSets-x.json file which has all of the cards created for the card game Magic the Gathering with their information. 

Link to dataset download https://www.kaggle.com/datasets/mylesoneill/magic-the-gathering-cards/versions/1/data

Below is my to do list with this dataset.

1) As there is a lot of data here my first job is to read in this Json file and normlaize and flatten the data.
2) Neeed to filter data down to just one set (LEA which is the first over magic set Alpha)
3) Now that i have only one set, i need to filter down my columns so it has only relevant data
4) Now i should have an eaisly readable dataframe with all of Alphas cards and their infomration including name, CMC and type

Questions i should explore once the dataframe is readable:
1) Which Artsit has the most cards in Alpha?
2) How many cards in Alpha are on the reserve list?
3) which color has the most cards in Alpha?
4) How many of each card type is there?
5) what is the most reprinted card



Answers to the above:
1) Which Artsit has the most cards in Alpha? - Dan Frazier is the artist that has the most art in Alpha with 37 unique cards
2) How many cards in Alpha are on the reserve list? - There are 48 cards on the reserve list. Thats 16.0% of all cards in Alpha
3) which color has the most cards in Alpha? - W is the most commom color in Alpha with 52. Thats 18.0% of all cards in Alpha
4) How many of each card type is there?
   Creatures:	88
   Enchantment: 68
   Artifacts:	47
   Instants: 43
   Sorceries: 30
   Lands: 14
6) what is the most reprinted card - Swamp is the most reprinted card in Alpha with 96 reprints.
