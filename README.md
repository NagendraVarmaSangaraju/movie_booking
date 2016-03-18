# movie_booking
A python script to  notify you when ticket booking of a movie starts
I am using BookMyShow's website for verifying ticket booking status.
So go the BookMyShow website and copy the URL of your movie and in 
the res variable when we are making a request put that URL.
e.g.
res = requests.get('https://in.bookmyshow.com/kanpur/movies/batman-v-superman-dawn-of-justice/ET00030143')
we are requesting Dawn of Justice in Kanpur city.
after that it will work fine.
You will get notifications and your shell will also print status results.

Requirements:
requests module
bs4 module
gi.repository module
