The weather system in the game has been adjusted to suit each season. Winters are now cold with a likelihood of snow and hail, autumns have a high chance of rain and summers are generally dry and warm.

The 7 day weather forecast is shown in the top right corner, just below the in-game hud, and by can be toggled by pressing `Left Alt + F` (default key mapping). A good farmer will use this forecast to plan their activities.
You can also see the current air and soil temperatures, left of the current weather and time. Be sure to keep an eye on this. The forecast might not always be right.

*Note*: The extra weather effects, such as snow, will work on any map, but for the full gameplay experience, we highly recommend you to play on maps that have been optimised for seasons.

The weather can also be customised by map makers, or other mods. For further info, check out [further info for map makers](Info-for-Map-Makers)

WIP

### Snow

- Pedestrians do not spawn in the Winter.

- When snow falls, tippers and shovels fill up. Put them in a shed (when the map has a snow mask) or activate the cover.
- Snow will melt from tippers and shovels when it is not freezing outside.


A: Snow is a swath. You can handle it with any bucket you would be able to use on grass. Because of the Tip Anywhere functionality, there is this new feature called the TipCol. This is a way for map developers to decide where swaths can't be placed. Good places are inside buildings, or on roads that are made of models. (The swaths would not be able to be cleaned up by machinery because the road is in the way). This technique is also present in Goldcrest Valley (it is why you can't tip on the road).

We can't use this TipCol (for performance and technical reasons), so we place snow everywhere. This will sadly cause a lot of ploblems on roads where it can't be cleared by a snowplough. So we added a way for map makers to tell us where we can and can't place snow. As long as the map does not tell us this, we will keep the snow till a minumum, which is 1 layer (6 cm).

If you want more fun with more snow, ask you mod-map maker to update his or her map for Seasons.