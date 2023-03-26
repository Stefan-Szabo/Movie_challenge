# Movie Challenge Repository

Foundation for a program for movie fanatics to keep track of what movies they have watched and how many times they watched each movie.

## Desription

The program supports the following:



class Movie - models a movie which includes

- movie name

- movie rating (G, PG, PG-13, R)

- watched - the number of times the movie has been watched



class Movies - models a collection of movie objects



Obviously, Movies needs to know about Movie since it is a collection of Movie object

However, our main driver should only interact with the Movies class.





Additionally, 

- if we try to add a movie whose name is already in the movies collection 

we should display this error to the user

- if we try to increment the watched count for a movie whose name is not in the movies

collection we should display this error to the user


