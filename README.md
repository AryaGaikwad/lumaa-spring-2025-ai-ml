# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

## Overview

This system generates personalized movie recommendations based on user input. It works by first processing the user’s query and identifying relevant genres from it. The movie dataset is then filtered based on the detected genres to narrow down the options.

To rank the movies, the system calculates similarity scores between the user query and movie descriptions, ensuring the recommendations are closely related to the user’s interests. Additionally, a genre match score is incorporated to further prioritize movies that align with the user’s genre preferences.

If the user specifies a preferred country, the system filters the recommendations to give higher priority to movies from that country. Finally, the system combines the similarity and genre match scores into a weighted score, which is used to rank the movies and return the top recommendations.

This approach combines both content-based filtering and genre-based preferences, providing diverse and relevant movie suggestions based on the user’s input.

---

## Requirements

1. **Dataset**  
   - Download the **titles.csv** in the repository
     
2. **Setup**:
   - Python version, virtual environment instructions, and how to install dependencies (`pip install -r requirements.txt`).  
3. **Running**: Run the **main.ipynb** notebook 
4. **Results**:
   


4. **Output**  
   - When given an input description (e.g., `"I like action movies set in space"`), your system should print or return a list of recommended items (e.g., 3–5 titles).  
   - Include the similarity score or rank if you’d like.

5. **Summary & Instructions**  
   - A short `README.md` that includes:
     - **Dataset**: Where it’s from, any steps to load it.  
     - **Setup**: Python version, virtual environment instructions, and how to install dependencies (`pip install -r requirements.txt`).  
     - **Running**: How to run your code (e.g., `python recommend.py "Some user description"` or open your notebook in Jupyter).  
     - **Results**: A brief example of your system’s output for a sample query.
        User query: "I love space action movies"
       📌 Detected Genres: ['action']

       🔍 Top 10 Recommendations:
       
       1. 🎬 A StoryBots Space Adventure
             📖 Join the StoryBots and the space travelers of the historic Inspiration4 mission as they search for answers to kids' questions about space.
             🌎 []
             🎭 Genres: animation
       --------------------------------------------------
       2. 🎬 The Wonderful: Stories from the Space Station
             📖 In unusual circumstances, scientists from different countries work together to achieve a common scientific goal. Locked in their spinning space lab, they are isolated from the world — family and friends - and can only watch from the outside as life on Earth continues without them. The space station is a monument not only to the weaknesses of humanity, but also to its ability to do the impossible for the sake of life in space.
             🌎 ['US']
             🎭 Genres: documentation
       --------------------------------------------------
       3. 🎬 Fukrey Boyzzz: Space Mein Fukrapanti
             📖 Delhi Boys Going To Space
             🌎 []
             🎭 Genres: animation, comedy, family
       --------------------------------------------------
       4. 🎬 Action Pack
             📖 The heroic kids of the Action Academy take on the bad guys with their hearts, their wits and their superpowers, and bring out the best in them.
             🌎 ['US']
             🎭 Genres: family, action, animation, fantasy, scifi, comedy
       --------------------------------------------------
       5. 🎬 Space Force
             📖 A four-star general begrudgingly teams up with an eccentric scientist to get the U.S. military's newest agency — Space Force — ready for lift-off.
             🌎 ['US']
             🎭 Genres: comedy
       --------------------------------------------------
       6. 🎬 Last Action Hero
             📖 Following the death of his father, young Danny Madigan takes comfort in watching action movies featuring the indestructible Los Angeles cop Jack Slater. After being given a magic ticket by theater manager Nick, Danny is sucked into the screen and bonds with Slater. When evil fictional villain Benedict gets his hands on the ticket and enters the real world, Danny and Jack must follow and stop him.
             🌎 ['US']
             🎭 Genres: action, fantasy, comedy, family
       --------------------------------------------------
       7. 🎬 Space Sweepers
             📖 When the crew of a space junk collector ship called The Victory discovers a humanoid robot named Dorothy that's known to be a weapon of mass destruction, they get involved in a risky business deal which puts their lives at stake.
             🌎 ['KR']
             🎭 Genres: scifi, drama, fantasy, action
       --------------------------------------------------
       8. 🎬 The Space Between Us
             📖 In this interplanetary adventure, a space shuttle embarks on the first mission to colonize Mars, only to discover after takeoff that one of the astronauts is pregnant. Shortly after landing, she dies from complications while giving birth to the first human born on the red planet – never revealing who the father is. Thus begins the extraordinary life of Gardner Elliot – an inquisitive, highly intelligent boy who reaches the age of 16 having only met 14 people in his very unconventional upbringing.
             🌎 ['CN', 'US']
             🎭 Genres: drama, romance, action, scifi
       --------------------------------------------------
       9. 🎬 Tito
             📖 Tito is the second installment in the new-wave Egyptian action movies. After Mafia by Sherif Arafa, which was a breakthrough in Egyptian cinema making, Tarek El-Aryan brings us Tito, the next logical step. Very simply, this movie is about an ex-con who tries to escape his sinful life by starting a new one, but his past comes back to haunt him. The reason, why Tito is better than Mafia is because the script and story line in Tito is more complex, and some of the characters had real depth in them and where fully developed throughout the movie.
             🌎 ['EG']
             🎭 Genres: documentation, crime, drama, romance, action
       --------------------------------------------------
       10. 🎬 The Getaway King
             📖 An action crime comedy set in the last days of communism in Poland, a story of folk-hero thief, who escaped 29 times from cops. Naymro was living on his own terms against the system. But love and collapsing Berlin Wall changed everything.
             🌎 ['PL']
             🎭 Genres: drama, action, comedy, crime

---





3. **Short Video Demo**  
   - In a `.md` file (e.g., `demo.md`) within your fork, paste a link to a **brief screen recording** (video link).  
   - Demonstrate:
     - How you run the recommendation code.  
     - A sample query and the results.

rization, similarity measure).

**We look forward to seeing your solution!** Good luck!
