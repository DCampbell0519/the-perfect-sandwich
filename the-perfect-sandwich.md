# How To Make The Perfect Sandwich

Making the perfect sandwich is as much art, as it is science.  I mean sure, there's something inherently American about being able to slap anything between two slices of whatever-the-fudge bread and calling it a *sandwich*.  But there's a big difference between that sorry excuse of a man-dinner, and culinary magic.  And look, I get that the idea of "The Perfect Sandwich is *subjective,* and everyone has their own idea of what constitutes said *perfection,* but let me be the first to tell you... 

... They're wrong.  

## 1. The Bread

```javascript
const myBread = sourdough;
console.log(myBread + " is the only bread worth breading.")
``` 

> PRO TIP: Melt a little butter to the outsides of your sourdough.  Turn that bad boy into a grilled-cheese-style man-wich!

## 2. The Spread

The Spread is your opportunity to really *individualize* your sandwich.  Mayhaps that tub of full-fat *mayo* gets the nostalgic juices flowing, reminiscent of weekends at Grandma's when you were young and enjoyed the immortality of youth.  Mayhaps you watched a lot of Buffy The Vampire Slayer at a formative age and think a nice *Garlic Aioli* is the way to go.  Or maybe you're like me and enjoy a nice kick.  Mayhaps a nice *creamy horseradish* is the way to go!

```javascript
const mySpread = ["Garlic Aioli", "Mayo"];

for (let i = 0; i < mySpread.length; i++) {
  if (i < 1) {
    mySpread.push("Horseradish");
    }
}
console.log(mySpread);
```

## 3. Meat and Cheese

The meat and cheese portion is/are probably the most subjective ingredient(s) of your sandwich.  There are lots of popular options to choose from!

|MEAT                   |      CHEESE         |     
| :---                  | :---                |
|- Roast Beef           |- Cheddar            |
|- Honey Turkey         |- American           |
|- Oven Roasted Turkey  |- Swiss              | 
|- Ham                  |- Provolone          |
|- Cold Cuts            |- Pepper Jack        |
|- Buffalo Style Chicken|- Gouda              | 

> PRO TIP: Don't bother with fish.  Fish is basically a vegetable.  A vegetable sandwich is basically a salad.  And you know who makes great salads? 
> 
> ... Who cares.

## 4. Toppings

Good toppings are kind of like *The Spread* with regards to their versatility.  But also tend to be much less exciting, kind of like every Marvel movie after *End Game.*  But like most things in life, a spectrum exists.  And just like the MCU ranges from Winter Soldier > Madame Web, so to do sandwich toppings range from Hard-Boiled Egg > raw onion.

### ***In Descending Order of Greatness:***
- Hard-Boiled Egg
- Avocado
- Oregano
- Sauteed Mushrooms
- Sauteed Onions
- Raw Onions
- Lettuce
- Tomato
- ... 
- ... 
- ... 
- Pickles

> PRO TIP: If you're making a sandwich at your buddy's house and he tries to offer you pickles, never fear.  You have plenty of time to make new friends.

## 5. Putting It All Together

The time is nigh.  Your appetite has made you hangry.  Your ingredients and fixins are strewn about the counter.  Your significant other is prowling outside the kitchen wondering just what kind of monstronsity he/she is going to have to clean up later.  All that's left to do is jigsaw puzzle all of the pieces together.  And then... we feast.

> PRO TIP: The Cheese should always be the outermost layer of any sandwich.  It acts as a moisture barrier for the bread!

> PRO TIP SECONDUS: If your lovely wife comes around asking for a bite of your sandwich, don't let her.  That's a rookie mistake.  And ends with your wife eating your perfect sandwich, while you're busy munching on the leftover Saltines you found in the pantry.
 

```javascript
const mySpread = ["Mayo", "Garlic Aioli", "Horseradish"];
const myMeat = ["Roast Beef", "Turkey", "Ham"];
const myCheese = ["Cheddar", "Swiss", "Pepper Jack"];
const mySandwich = [];

for (let i = 0; i < mySpread.length; i++) {
  mySandwich.push("My perfect sandwich has " + mySpread[i] + ", " + myMeat[i] + " and " + myCheese[i])  
} 

console.log(mySandwich);
```