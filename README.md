# RiHarvest
RiHarvest is a Potion Craft mod which allows you to apply growth and harvest bonuses to your garden using your potions.

This is my first complete mod for a Unity game, so it's entirely possible that it isn't quite as ready for release as I thought. If you run into issues let me know, and if they're particularly major issues then try out this similar mod, [Plentiful Harvest](https://github.com/TommySoucy/PlentifulHarvest), by someone who is clearly a much more experienced modder than I. Or you might just prefer their implementation to mine.

<h2>How to use</h2>
A potion is applied to your garden by simply grabbing it from your inventory and placing it somewhwere in the garden. The potion will be consumed, and its effects will be applied to the garden. Potion effects can stack, but only to a certain extent. You will be prevented from oversaturating your garden.
<br><br />

**Growth I**: Your garden will grow extra over the next coming nights. Some plants that would have taken a few days will now be ready in the morning.

**Growth II**: Your garden will grow extra over the next coming nights. Even more plants that would have taken a few days will now be ready in the morning.

**Growth III**: Your garden will grow extra immediately. In addition, a few Plants that would have taken a few days will also now be ready in the morning.


**Harvest** **I**, **II**, **III**: Each plant that grows while a Harvest effect is active will have a chance to grow with a larger amount of ingredients available to harvest. The stronger the potion, the higher the chances for bonus ingredients and the longer the effect will last.

<h2>Requirement: Installing BepInEx 5</h2>

This mod uses [BepInEx 5](https://github.com/BepInEx/BepInEx/releases)!
Download the latest version from the link above. If needed, follow the BepInEx [Install Guide](https://docs.bepinex.dev/master/articles/user_guide/installation/unity_mono.html).
In short: 
1. Extract the BepInEx zip into your Potion Craft root directory (probably `C:\Program Files (x86)\Steam\steamapps\common\Potion Craft`)
2.  Run your game once to allow BepInEx to perform its setup


<h2>The easy part: Installing RiHarvest</h2>

1. [Download](https://github.com/ColoursRI/RiHarvest/releases) the mod, and simply place `RiHarvest.dll` in `PotionCraft/BepInEx/Plugins`
