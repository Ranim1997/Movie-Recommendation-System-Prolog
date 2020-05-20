# Movie-Recommendation-System-Prolog
For many years, movies were a way to entertain for a lot of people. Nowadays, the evolution of technologies; movie lovers could find a huge number of movies via multiple movie providers. In order to help movie lovers to save time and effort looking for movies satisfy with their preference; we came up with a Movie Recommendation System. The Movie Recommendation System has the ability to give the user the best match movie based on their preference.


# Analysis and Design
The system has two main users. The first user is the admin, who has the authority to control the
system (display all movies, add, and delete a movie). The second user is a movie love, who can interact
with the system to get a specific recommendation based on his/her preference.

Shows the flow of the system in case of the movie lovers use the system:
![](https://github.com/Ranim1997/Movie-Recommendation-System-Prolog/blob/master/img/movielover.JPG)

Shows the flow of the system in case of the admin use the system:
![](https://github.com/Ranim1997/Movie-Recommendation-System-Prolog/blob/master/img/admin.JPG)


# Implementation
### The first phase of the implementation is to define the information needed for each movie, which are category, language, age restriction, season.

- Category includes: Drama, Science, Fantasy, Mystery, Action, Adventure, Romance, Comedy, Animation, and Horror.
- Language includes: English, Korean, Indian, Japanese, and No preference.
- Age includes: G, PG, R, NC-17, and No preference. The meaning of age restriction:
+ G – General Audiences, All ages admitted. Nothing that would offend parents for viewing by children.
+ PG – Parental Guidance Suggested - Some material may not be suitable for children. Parents urged to give "parental guidance". May contain some material parents might not like for their young children.
+ R – Restricted, Under 17 requires accompanying parent or adult guardian. It contains some adult material. Parents are urged to learn more about the film before taking their young children with them.
+ NC-17 – Adults Only, No One 17 and Under Admitted. Clearly adult. Children are not admitted.
- Season includes: 2019 first quarter, 2019 second quarter, 2019 third quarter, 2019 fourth quarter, and No preference.
