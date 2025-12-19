# Diary of a Georgia Voter: Diary Map Using Mapbox & Scrollytelling

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*oFCI_1lrLxkMeB75sPaIFg.png" width="800"/>
</p>

## Background
When I tell people I waited four hours to vote, it immediately sounds like a hyperbole. To describe the experience, I wanted to create a geospatial representation of what it actually feels like to move at just .05 mph for 4 hours. As a designer and a visual storyteller, I immediately whipped up this static map of my experience, in the hopes that it might make be a good resource for organizations like Fair Fight, who collected my story as part of their initiative to account for and document instances of voter suppression.

Next, I took Mapbox’s Election Mapping Challenge as my invitation to make my static map into something interactive and to level up my rookie engineer skills. I also thought it would be interesting to interpret a singular, personal story on a map.

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1600/format:webp/1*CNN_w6x4gMFrKqiw6TG_zw.png" alt="diagram" />
  <figcaption> The initial static map I designed that inspired this project.</figcaption>
</p>

## The Making Of
This is the first map I ever made, so it was a tremendous learning experience. When I first started on this endeavor, I did not even know how to find longitude and latitude for a specific location! Feeling ambitious, I toyed with the idea of an AR game where you arrowed through the four-hour wait with me (maybe in real time, if I wanted it to be tortuous.) After realizing I was way out of my depths, I returned to the drawing board. Fortunately, I had my static map to work from, and I used that as my MVP.

I settled on a “Scrollytelling” style of building the map after toying around with a few different formats for sharing the map I had in mind. I found [this tutorial](https://blog.mapbox.com/how-to-build-a-scrollytelling-map-ead6baf2cd1b) by Lo Bénichou to be invaluable.

[Here is the raw mapping data in Mapbox](https://api.mapbox.com/styles/v1/slashinsky/ckg2nqo9s0w5p19muw9au2uco.html?fresh=true&title=view&access_token=pk.eyJ1Ijoic2xhc2hpbnNreSIsImEiOiJjajgzZ3lmaXcydm9mMzJvMGhnZDV5dzY0In0.EPHCQX6kQANsHdJueUZLmQ&source=post_page-----8354e9b1a386---------------------------------------#18.48/33.7356292/-84.3659421), with custom iconography. To make the map, I created two folders: one with the path that I traveled, and one with key points of interest along my route. In the Scrollytelling template, I assigned a card to each point of interest, and added a title, photo, and description to each card.
