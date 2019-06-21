##Petz

![Logo](/images/logo.png)

![Items](/images/items.png)

Are you tired of ugly mobs? Do you like the kawaii world and taste?
The PetZ are here now for you!
For v5.0+

###Mobs
####Kitty
![Kitty](/images/kitty.png)
-3 colors: brown, black and gray.

####Puppy
![Puppy](/images/puppy.png)
-3 colors.

####Duckies
![Ducky](/images/ducky.png)
-3 types: Yellow, Black and Mallard.
-Peaceful and dumb animal.
-They can put duck eggs from time to time.You can tame it but not give it any order.
-You can breed ducks creating a nest with an egg inside, optionally you can leave an empty nest near a ducky so it lay an egg.
-It drops feathers when killed.

####Beaver
![Beaver](/images/beaver.png)
Behaviour:
-It lives near water (in rivers in the case of valleys mapgen).
-It can be tamed.
-It can walk, swim and dive underwater.
-It drops Beaver Fur to create Beaver Oil when killed.
-It got a chance of create an unique dam on the coast or river.
-You can spread beaver oil on your pet skin. In tamagochi mode your pet will be happy, but the fact of not do it it is not mandatory for it to be sad.

####Lamb
![Lamb](/images/lamb.png)
In 3 colors: White (common), grey & dark gray (rare) and brown (very rare).
-Lambs eat grass.
-You can get Wool with the Shears (right click).
-To wool to regrow feed your lamb or let it eats grass.

####Lion
![Lion](/images/lion.png)
-It lives in the Savanna. Wild animal. Dangerous.
-It likes raw meat.
-Can be tamed and give it orders with meat or a Whip (3 lashings to tame)
-In tamagochi mode:
- You have to lash your lion in 48h or it lost affinitty with you.
- Be careful, if you lost your lion as pet, it will attack you!

####Calf
![Calf](/images/calf.png)
-Available in three skins.
-It eats grass from time to time, like the lambs.
-It drops Leather when killed.
-It can be milked with an empty bucket.
-In order the calf to have more milk, you have to feed it or let it to eat some grass.

####Panda
![Panda](/images/panda.png)
-Panda is tamable and loves papyrus.

####Frog
![Frog](/images/frog.png)
-Frog is a semiaquatic animal. It loves fireflies to eat'em. It drops a leg that you can cook in order to get a Roasted Frog Leg (food).

####Grizzly
![Grizzly](/images/grizzly.png)
-Not a Teddy Bear, but a wild one. It lives in woods. It's tamable like the lion.

####Pony
![Pony](/images/pony.png)
-You can mount it with a Saddle and get a ride.
-You can give it orders.
-The Saddle can be cut with the Shears.
-Ponies are slow where you ride them. You can breeding them to get stronger and fastest ones.

####Parrot
![Parrot](/images/parrot.png)
-Tree species.
-Tamable and you can give it orders.
-It loves wheat seeds.
-It lives naturally in the jungle.
-You can order it to alight and to fly again.
-It can drop Raw Parrot meat which it can be cooked.
-You can put your parrot on your shoulder (2 minutes max.).

####Chicken
![Chicken](/images/chicken.png)
-Farm Animal.
-It can lay Chicken Eggs like the duckies.
-It drops Raw Chicken to cook it as food.

####Pigeon
![Pigeon](/images/pigeon.png)
-Flying bird.

####Chimp
![Chimp](/images/chimp.png)
-Agile monkey.
-Arboreal mob: It can climb trees, wood and leaves.
-It loves blueberries.

####Piggy
![Piggy](/images/piggy.png)
-It's a source of meat.
-It drops Porkchop to being cooked.

####Turtle
![Turtle](/images/turtle.png)
-Semiaquatic mob.
-It eats kelps.
-It has a chance of drop its shell.

####Clownfish
![Clownfish](/images/clownfish.png)
-A sea fish.
-It lives close to a coral reef.
-It is attracted to orange coral.
-It can be captured and put into a fish tank.
-It suffocates when outside water.
-In tamagochi mode you have only to feed it, but no if it is in a fish tank.

###Things you can with Petz
-Configure the models as "mesh" (by default) or "cubic" (nodebox, no animated, no too laggy) via the 'petz.conf'
-Configure the mob API: Only "mobs_redo" by now via 'petz.conf'.
-Configure the following food (aka food to health) it via 'petz.conf'. Use right click.
-Give it orders: follow you or stand: Right click if you are the owner.
-Configure if they spawn in the map via 'petz.conf'.
-Your pet can be tamed and captured.
-Internationalization support.
-Spawn Eggs.

NodeboxEditor (.nbe) and Blender (.blend) models included.

###Licenses
- Models, icons and textures by runs. GPL3 Feel free to use it.
- Sounds: Check the 'license.md' file inside the 'sounds' folder.

###Depends
default, mobs, stairs, dye, vessels, wool

###Tamagochi Mode
If this mode is activated (true by default) you have to take care of your pet. The pet will have two stats: Love and Hunger. If those stats go down to 0, your pet abandon you or will starve.

In multiplayer games (servers) the Tamagochi Mode is paused if the pet owner is offline.

###Feed it!
-You have to feed your pet once each 2 days at least (Minetest time) (right click wielding its food) (the food is configurable via petz.conf). Your pet then would be happy. Check your pet status (right click), if "Hungry" feed it, but if 'Satiated' then don't bother. If you do not feed your pet every 48 hours, its health would damaged and it would be sad.
This does not apply if your pet is inside its kennel.

###Brush it!
![Brush](/images/brush.png)
-You have to brush your pet once each 2 days at least, or it will be sad. Firstly create a hairbrush with two wood sticks and one string.
This does not apply if your pet is inside its kennel.

###ImageLash it!
![Lash](/images/lash.png)
In the case of a lion or grizzly, you have to lash it with a whip once each 2 days at least in order to control it.
Do not use the whip with another petz!

###ImagePolish it!
![Beaver Oil](/images/beaver_oil.png)
You can spread beaver oil on your pet skin. In tamagochi mode your pet will be happy, but the fact of not do it it is not mandatory for it to be sad.

Also keep in mind that:
-If you don't feed your pet in 8 days will die (configurable).
-If you punch your pet, it gets unhappy.
-If your pet is unhappy, it could abandon you.
-If your pet is inside its kennel, it'll be well cared for and happy and won't starve. But close the door!

Notes
-You can configure the time when your pet is checked in 'pet.conf'. 2400 by default (2 days).
-In a singleplayer game the pet stats remain intact between restarts.
-You can configure the node over where your pet is safe (no hunger) in 'pet.conf'. So you can do your our kennels.
-The Tamagochi Mode is paused for pet owners in multiplayer games (servers) when they are offline.

##Pet Bowl
![Pet Bowl](/images/pet_bowl.png)
Make a house to your pet and put a Pet Bowl. The pet will stand near it.

##Kennel
![Kennel](/images/kennel.png)
A schematic. Simply make a hole and punch inside it. You can put your pet inside after capture it. For creative mode only.
In there your dog will be well cared for and you won't have to worry about its health.

##Ducks/Chicken Farm
![Ducks/Chicken Farm](/images/duck_chicken_farm.png)
You can breed ducks or chickens via its eggs:
- Create a empty nest and put an egg inside (right click), optionally you can create a nest with an already egg inside. Await for the egg to hatch into a new ducky or chicken.
- Also if a ducky or chicken has an empty nest near, it can lay an egg on it.

##Capture Petz

Use the followig items to capture a petz:
-MobsRedo Net and Default Bug Net for Frog, Chicken, Kitty, Parrot, Pigeon, Ducky, Beaver, Clownfish, Monkey and Turtle.
-MobsRedo Lasso for Calf, Lion, Puppy, Piggy, Lamb, Panda, Grizzly and Pony.

###Capture Mechanics:
-To capture a pet (i.e. kitty) you have to own it. But to to capture a no pet (i.e. frog) you can capture it directely.
-To own a pet you have to tame it.
-To tame a pet you have to feed it with its favourite food 5 times. Or lash it in the case of the lion and grizzly.
-You cannot capture the pets of other players by default. To allow to rob pets change the setting 'rob_mobs' in 'petz.conf" file.

##Beaver Dam
![Beaver Dam](/images/beaver_dam.png)
The beaver's home

##Fish Tank
![Fish Tank](/images/fish_tank.png)
-Put your fish inside (right-click)
-Recover your fish with the Bug Net (right click) or breaking it.
-You can connect several fish tank nodes to build bigger tanks and add more fishes (one by node).

##Pony Breeding
![Baby Pony](/images/baby_pony.png)![Pony Breeding](/images/pony_breeding.png)

-Ponies can be male or female. Check its gender right clicking on them.
-Each pony has its own velocity forward, velocity backward and acceleration. You can read its characteristics with the format "1/1/1" where the numbers represent these 3 characteristics.
-Create a Glass Syringe.
-Use (right-click) the syringe on a male pony to get its sperm.
-Use (right-click) the syringe with sperm on a female pony. The pony will be pregnant.
-Right click on a pregnant female pony to check its pregnancy status.
-After 2 days (configurable) a little pony will born with a mixture of gens, from its father and its mother.
-Baby ponies cannot be ridered.
-After 2 days (configurable) the little pony will get to adult.
-You should select the best parent ponies to get better descendency (fastest ponies) when breeding.
-You can breed any pony even if you do not own it. But the owner of the baby ponies will be the mother's owner.
-The male sperm is unlimited but a female pony only can give birth 5 babies máx. After those 5 ponies, the mommy pony turn into infertile.
