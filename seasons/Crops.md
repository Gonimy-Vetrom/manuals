WIP
- At the beginning of a new game, the mod will reset all fields to the harvested stage. This is to simulate the fact that you just bought the farm and the fields haven't been worked since the last harvest.
- Using the mod on an existing save game is not recommended, but it is supported. The mod will prompt if you wish to reset all fields in this situation.
- Vanilla growth is completely disabled. The mod controls all growth of fruits, including pine trees (5 years to fully grown, harvestable after 2 years)
- Winter kills certain crops
- Grass is knocked back to stage 2 in the winter
- Crop growth duration is much, much longer: for some crops more than half a year
- Growth is adjusted to match real life life as much as possible - for example, crops will not grow if planted at the wrong time of the year
- Winter and spring crops are possible now. Some crops can be planted in autumn (barley, wheat and canola) and in spring and will reach harvestable stage by the summer. Some crops can only be planted at certain times of the year.
- Growth is configurable and can be changed by map makers to suit their map
- Germination of planted crops will only occur if the soil temperatures rise above the germination temperature.
- Swaths will reduce over time.
- Grass bales will rot and disappear after two days.
- Hay and straw bales exposed to rain will start to rot so keep them inside.
- Wrapped bales needs time to ferment before they are turned into silage
- Treshing can only be done when moisture content of the crop is sufficiently low. After rain the crop needs time and sunny weather to dry. Moist summer nights can also occur.
- Custom fruits are handled gracefully by using barley's growth patterns. Map makers can choose to modify the growth patterns of vanilla fruits and also make the mod aware of custom fruits by supplying custom growth patterns for them
- Plants are only harvestable in the final growth stage, except for poplar, oilseedradish, sugarbeet and potato. Min forage growth state has not been modified
- Using a tedder when crops are wet or when it is raining, leaves wet grass, not dry grass.

- Bunker Silo contents now take one third of a season to ferment.


## Q: My crops keep disappearing?!
A: You are seeding in the wrong season. You can look in the Seasons menu to find out when you can plant each crop. Like in real life, if the soil becomes too cold, crops will not grow. This means winter crops needs to be planted before the temperature drops too much in autumn. You will also have to wait in spring until the soil is warm enough for seeds to germinate in the soil. The temperature limit for sowing is set for each fruit in the growth.xml file. 

## Q: Which crops can be planted in the autumn?
A: Currently poplar, grass, oilseed radish, wheat, barley and canola. Anything else will die during the winter. 

## Q: Does the mod support non-standard fruits?
A: Yes, but in a very rudimentary manner at this point in time. Any non-default fruits will follow the same growth pattern as barley. 

## Q: How does the growth work?
A: There are 12 growth periods during a year. A year is made up of 4 seasons. Therefore each season has 3 growth periods. We do not consider these as months. Instead, we think of them as early, mid and late periods of a season. So, spring would be broken up into early spring, mid spring and late spring. Most crops can be planted in spring and they will grow. Crops planted in the summer will not grow and will die, except for grass, poplar and oilseed radish. These can be planted any time except for when the soil is frozen. No growth happens during winter. Any crops left that should have been harvested in summer or autumn will wither and die at the beginning of winter.  

## Q: What are the growth patterns for all crops? If I plant crop x in season y when will it be ready to harvest?
A: Seb: WIP, to be answered soon.

## Q: How does season length work with the growth periods
A: Season length can be set to 3, 6, 9 or 12 days. So, if season length is set to 3 days, that means early season will be day 1, mid will be day 2 and late will 3. 

Season length 6 days - early: [days 1-2] mid: [days 3-4] late: [days 5-6]

Season length 9 days - early: [days 1-3] mid: [days 4-6] late: [days 7-9]

Season length 12 days - early: [days 1-4] mid: [days 5-8] late: [days 9-12]
