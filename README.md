# c-karshe.github.io
Poké-Job Recommendation

Using data from the Pokédex (thanks GameFreak for the dataset!) we can see which Pokémon is best for the input task prompt using their base stats and Pokémon descriptions. Here are some goals for our Poké-Job Recommendation System:
Recommend the best Pokémon battle matchups for an input Pokémon.
Categorize the input prompt into a task needing one of the 6 primary stats (HP, Attack, Defense, Special Attack, Special Defense, & Speed).
Recognize which Pokémon type is most suited for a task (Normal, Fire, Water, Grass, Electric, Ice, Fighting, Poison, Ground, Flying, Psychic, Bug, Rock, Ghost, Dark, Dragon, Steel, Fairy). Keep in mind that many Pokémon can have duo-types. For this project I will be ignoring Mega-Evolution, Terrastallized Pokémon, and other circumstances that can change a Pokémon’s type.
Recognize keywords from Pokémon description that can make it well-suited for input task. (ex: task input = taking care of injured patients. Chansey’s description: “This kindly Pokémon lays highly nutritious eggs and shares them with injured Pokémon or people.” In this case, Chansey would be one of the recommended Pokémon.)


The goal output would be a list of 5 Pokémon that can be best suited for helping with the input task. With the Poké-Job Recommender System, various tasks can be solved in much more efficient and effective ways! 

