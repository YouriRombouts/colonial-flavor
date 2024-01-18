# Colonial Flavor
This EU4 mod that adds flavor to the game for colonizing new world nations by adding a new estate and formable nations.

## Settlers estate
The mod adds a new estate called the settlers (or Trekboers for Dutch or Boer nations). The settlers represent the people who left their homes in the old world in hope of finding riches or at least a better life in the colonies.

![Screenshot of the settlers arriving event](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/trekboers_arrive.jpg?raw=true)

### Who has access to the estate?
The settlers are available to any nation that meet all of the following requirements:
- The nation has unlocked the general colonization law idea (`Expansion ideas #6`).
- The nation has their capital in North America, South America, Africa, Oceania or in the random new world continent.
- The nation knows a nation in the old world (Europe or Asia) which has colonialism embraced and owns a province with a culture belonging to the new world nations culture group. Both of these nations need to have a port.
- The nation is not nomadic.

### What does the estate do?
The settlers estate adds some events, priviliges, a disaster and some agendas which give colonial nations a bit more flavor and content:

- The settlers have some agendas available which focus on colonization, development and conquering lands of technologically inferior neighboring nations.

- The settlers have two mutually exclusive privileges, one focussing on colonization of uncolonized provinces the other giving dev cost modifiers similar to what the cossacks give Eastern European nations.

![Screenshot of the settlers privileges](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/settlers_privileges.jpg?raw=true)

- The settlers also have a privilege which allows for the discovery of iron, copper, gems or gold in mountains, hills, highlands, jungles or deserts in areas of the map where these goods can be found while colonizing.

- When the settlers get too influential a disaster will start to progress which leads to them breaking free and forming a breakaway peasant republic.

### Refugee events
To simulate people fleeing from war and devastation towards the colonies for a better life new events have been added.

#### Refugees leaving event
This province event fires for provinces which have a lot of devastation (first at 20 then 40 and finally 60) which decreases the development of the province by 1 in all categories. After decreasing the development the event gives player a choice as to what to do with the refugees with the following options:
- Send relief to return the development to the affected province.
- Send them to a province with the same culture as the affected province.
- Send them to a province with the primary culture of the affected nation.
- Send them to a colonial nation of the affected nation.
- Send them to a different nation which has access to the settlers estate.
- Let them wander through the owners nation (this only an option if no nation has access to the settlers estate).

![Screenshot of the refugees fleeing](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/refugees_depart.png?raw=true)

#### Refugees arriving event
This event fires for new world nations who receive the refugees. This event moves the development from the devastated province to the new world nation. The receiving nation has a choice as to where to send the refugees:
- Settle them in a city (random province with 15 dev or capital).
- Settle them on rural land (random province).
- Settle them where they arrived (random port).
- Settle them all over (does not give immediate development but dev cost reduction for the entire nation).

![Screenshot of the refugees fleeing](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/refugees_arrive.png?raw=true)

## South African flavor
The mod also adds some additional flavor for people who are interested in playing in South Africa:

- An event for nations with their capital in South Africa which adds a center of trade to Matsolo as well as the "important natural harbour" modifier to both Matsolo and Cape when both provinces are both primary culture and religion.

- An event which gives the option to spawn either a republic or a monarchy in South Africa as a colonial nation when playing as the Netherlands. A monarchy can only be released when the releasing nation is a monarchy itself.

![Screenshot of the refugees fleeing](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/event.png?raw=true)

![Screenshot of the refugees fleeing](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/ideas_zar.jpg?raw=true)

- An event which spawns a South African nation that works the same as the one for the Netherlands but is more generic and available to all nations.

![Screenshot of the refugees fleeing](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/ideas_saf.png?raw=true)

- A decision to flee to South Africa for the Netherlands similar to the decision to flee to Brazil as Portugal.

![Screenshot of the refugees fleeing](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/exile_government.jpg?raw=true)

- A decision to form South Africa when exiled as the Netherlands.

- Dynamic province names for Dutch or Boer cultured nations around the Lowlands and South Africa.
![Screenshot of a Dutch South Africa](https://github.com/YouriRombouts/colonial-flavor/blob/main/screenshots/dutch_province_names.jpg?raw=true)

- The Boer culture. This culture is created by an event that can fire when a nation has a province in Africa with a Germanic culture.

### Early slavery abolition
The mod adds a new decision to abolish slavery early, it is intended to simulate a nation which has a highly accepted and integrated native African community. It can be used by nations which meet the following requirements:
- The nation has its capital in Africa and has either an African culture group or has at least 150% native assimilation.
- The nation has completed the humanist idea group.
- Ruler has at least 3 diplomatic skill.
- The nation has at least admin technology level 15.
(The AI will never take this decision)

## Special thanks to:
- u/YeetPistachio684 on Reddit for allowing me to use his flag for the generic South African nation. The flag is originally from [this post](https://www.reddit.com/r/vexillology/comments/j776ah/i_love_the_design_of_the_south_africa_flag_but_i/?utm_source=share&utm_medium=web2x&context=3)
- MajorMajor on discord for allowing me to use the South African flag from the victoria 2 mod divergences of darkness as well as some of the Dutch dynamic province names in South Africa.