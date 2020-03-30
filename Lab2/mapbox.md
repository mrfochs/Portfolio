## Making a Custom Map Style in Map Box and Bringing it into ArcMap
<img style="float:right; padding:5px;" src="https://live.staticflickr.com/4054/5157988485_6e474d60d8_c.jpg" width="35%" />Similar to my attempt to make a map style in <a href="https://mrfochs.github.io/Portfolio/Lab1/google_map" tagret="_blank">Google Maps Style Editor</a>, I wanted to see what I could come up with using Map Box's custom style editor. Specifically, I wanted to see if I could make a generic, primarly based map style that reminded me a little of the flat graphical stylings of airplane safety cards (the laminated things no one ever reads when the flight attendants tell you to). I had always be in love with the flat, shaddowless cartoon drawings and admired how they convey a lot fo information with little to no words.

### The Process and Testing in ArcMap
Starting with a rather general base color for land, I was able to add in small splashes of solid color for water, land, and roads. I also made the buildings a bright yellow similar to the life vests in the plane graphics. The result is a nice and flat map style that is not cluttered and a good vessle for more colorful and detailed mapping layers on top. When I was happy with the map style, I then used the Web Map Tile Service to bring the style into ArcMap to see how the base map style would work within a more traditional GIS prgram. To my surprise, there were a few small differences (mostly around the font style, size, and location), but in general it was an easy way to build a base map for use in future projects.

<a href="https://studio.mapbox.com/styles/mrfochs/ck8dk09d50w3c1imw424piur5/edit/#15.64/40.439768/-80.002627/0/44" target="_blank">View the style live in Mapbox here</a>

Base Map in Mapbox          City-level view of style            Base Map imported into ArcMap
<img style="float:left; padding:5px;" src="https://mrfochs.github.io/Portfolio/Lab2/mapbox_style.PNG" width="30%" />
<img style="float:left; padding:5px;" src="https://mrfochs.github.io/Portfolio/Lab2/mapbox_style.PNG" width="30%" />
<img style="float:left; padding:5px;" src="https://mrfochs.github.io/Portfolio/Lab2/mapbox_style_in_arcmap.PNG" width="30%" />

*Airplane Saftey Card Image used under creative commons, non-commercial from <a href="https://www.flickr.com/photos/phossil/5157988485" target="_blank">Phossil</a> via Flickr*
