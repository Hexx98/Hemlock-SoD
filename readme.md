Season of Discovery Update (1.1.6-sod) — by Hexx
---------------------------------------
* Fixed Occult Poison tracking: the button now counts both Rank I and Rank II and crafts the highest rank you know (previously only handled Rank I)

Season of Discovery Update (1.1.5-sod) — by Hexx
---------------------------------------
* Updated Interface version for Classic Era 1.15.9
* Added buttons for Season of Discovery poisons: Sebacious (217345), Numbing (217346), Atrophic (217347), Occult Poison I (226374)
* Added a safety check so clicking a poison you haven't learned no longer throws an error
* Note: Occult Poison uses roman-numeral ranks (I / II) in its base name, so inventory/rank matching may be imperfect if both ranks are known

Classic Update
---------------------------------------
* Migrated to Ace3 / LibDropDown
* Support for Classic
* Added confirmation dialog
* Alternative icons support

Hemlock - Minimalistic addon to automate poison buying and creation
---------------------------------------
This is a Classic fan update version of the addon Hemlock : https://www.wowace.com/projects/project-14170.

**Introduction:**

The entire idea is to make the entire poison-buying process as simple, fast, and brainless as possible.
It doesn't make you bother with ranks or anything - it assumes you want to refill your highest-rank poison to a threshold you set.

**How to use:**

1. Right-click to set the number of poisons you want to automatically buy and make.
2. Left-click to buy the exact amount of components for your poisons needs.
Hemlock also keep track of your inventory so it won't buy more reagents than needed!
3. Left-click again to automatically craft your poisons.
alt textThe number of poisons in your inventory appears in red is when the threshold is not reached and green are when you already have enough poisons. 
![alt text](https://i.imgur.com/iOqOjZZ.png)

*/hemlock reset* to show all poisons and reagents buttons or use the ingame addon option menu.

**Lacking Features, Ideas & Problems**

The "ignore old poisons in inventory" option is not working properly, this is due to hemlock not knowing what poison rank you can craft when you open the vendor window.
