# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).


## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/x7uUWgDkQZ.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.
I was stumped on how to debug the collection view having compressed images even after 15 minutes, so I had to resort to the solution CodePath provided.
I noticed there is a bug where the tab bar on the Superhero page turns to black when you scroll all the way down to the bottom (you'll see it in the GIF); I will work with the TAs to fix it.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/Omjsf7bip9.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.

One challenge I had was with getting CocoaPods to run on my MacBook because the commands I put into Terminal did not work at first. I did not realize until later that I had an M1 MacBook, and so I  needed to install CocoaPods in a different way by using different commands.
