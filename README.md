# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF
![](https://github.com/flix/simulation.gif)

### Notes
This project gave me practice working with swift files and storyboards, as well using the third-party framework Alamofire to query data from an API. I also learned about cell recycling, and how to save memory using the tableview. I've noticed a lot of similarities to web development, but the syntax is completely new for me.

When I was nearly done creating the app, I started getting an error thrown that one of my UIImageViews had a value of 'null' when not allowed. I looked through all of my swift files and couldn't find the variable they were referring to anywhere - I was so confused why Swift was giving me an error for a variable that didn't even exist. I went to office hours for help and my TA was also unsure. It turned out to be painstakingly simple, which was that at some point in my storyboard I had accidentally created two imageViews that were directly layered on top of one another. From now on I won't focus so heavily on my swift files while debugging, but on my storyboard as well!
