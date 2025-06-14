Movie Star (MS) - Film Directing Game

____Introduction____
Welcome to Movie Star (MS), a film directing game that allows you to experience the role of a director. 
In MS, you can create and direct your own movies, choose actors, scripts, and participate in competitive events.


____Game Description____
Each player has the ability to create and direct movies, select actors, scripts, and other details. 
The goal of the game is to create the best movies and win awards at competitive events.


____Entities____

~Player_Movie_Star	 

~Director
    -Movie_International
    -Movie_Domestic
    -Country
    -Cities
        Sets
        Genre
    -AI_Machine
        Script
    -Sponsors

~Actors
    -Contract
    -Roles
    -Physical_Characteristics
    -Intellectual_Characteristics
    -Technical_Characteristics
    -Training_Programs

~Competitions
    -Awards
    -Top_Directors
    -Movie_Statistics
    -Social_Media_Pages
    -Posts
    -Friendships


____Relationships____

 One-to-One (1:1) Relationships
    Director and Movies:
        Each domestic/international movie  is directed by exactly one director, and each director directs exactly one domestic/international movie.
     Movies and Genres:
        One movie can be associated with only one genre.
    
 One-to-Many(1:N) Relationships
    Player and Directors:
        Each player can be associated with multiple directors.Each director is associated with only one player.
    Director and Director:
        Directors can connect with each other.
    Director and AI_Machine:
        One director can be linked to multiple AI machines.Each AI machine is associated with only one director.
    AI Machine and Scripts:
        One AI Machine can be associated with multiple scripts.One script is used for only one AI.
    Country and Cities:
        One country can encompass many cities.Each city is associated with only one country.
    Actor and Contracts:
        One actor can have multiple contracts.Each contract is associated with only one actor.
    Genres and AI_Machine:
        Each movie genre can be associated with multiple AI engines.One AI engine can be associated with only one genre at a time.  
    Sponsors and Movies:
        One movie can have many sponsors.
    Movies and Competitions:
        Each domestic/international movie can participate in multiple competitions.
    Movies and Movie_Statistics:
        A movie can have multiple statistics associated with it.
    Competitions and Movie_Statistics:
        For each competition, there can be multiple statistics associated with each movie participating in that competition.   
    Competitions_SocialMedia:
        Competitions may employ multiple social media pages, each dedicated to a single competition.
    Movies_Directors:
        Directors can create a multitude of social media posts.
    Director_TopDirector:
        Every director has one place in the pantheon(even 0).
    Director_Posts:
        A Director can make multiple posts.
    Movies_Posts:
        One movie can have many posts.
    Friendships:
        Two directors can befriend each other in a competiton.


 Many-to-Many (N:M) Relationships:  
    Actor and Characteristics(Physical,Intellectual,Technical):
        An actor can have multiple characteristics.A characteristic can be associated with multiple actors.
    Actor and Training Programs:
        An actor can participate in multiple training programs.A training program can have multiple actors enrolled in it.
    Training Programs and Technical characteristics:
        Each technical characteristic can be influenced by multiple training programs.Each training program can contribute to enhancing multiple technical characteristics.
    Actors and Roles:
        An actor can play multiple roles in different movies.A role can be played by multiple actors in different movies.   
    Competitions and Awards:
        Each competition can have multiple awards, and each award can be given in multiple competitions. 
    


Contributors
    ΑΜ:1115202200199  Όνοματεπωνυμο: Φάτιμα Τσόντρι
    ΑΜ:1115201900348  Όνοματεπωνυμο: Γρηγόριος Φωτόπουλος
    ΑΜ:1115201900238  Όνοματεπωνυμο: Κυριάκος Λάμπρος Κιουράνας
