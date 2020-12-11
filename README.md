# Poke-Table

## UPDATE: New Version in the Making
I've made this site a long time ago -- long before I knew anything about the magical power of Javascript or databases. So, I'll be redesigning the entire thing in the upcoming weeks in the hopes of making the site better constructed and optimized. I'm also hoping to get the elemental creatures designed and illustrated as I go. 

## Viewing the Site 
This project is still very early in its development; thus, it isn't yet deployed to an actual domain. You can view it from Github Pages by following this link: https://imotyashok.github.io/poketable/

If you're interested in running it from your local machine, you can clone this repository, cd into the cloned folder and run the following command from your terminal:
```
[browser-name] index.html 
```
(Replace [browser name] with the name of the browser you're using. For example, if you're using Google Chrome, your browser name would be 'google-chrome'; Mozilla Firefox would be 'firefox', and so on) 

More conveniently, you can view it from Github Pages by following this link: https://imotyashok.github.io/poketable/ 

## Concept and Purpose
Chemistry is a difficult subject, and it can be especially difficult to get students interested in it. After staring at periodic tables for many, many hours during my brief venture into the field of chemistry and biology, I thought "man, how cool would it be if each element was a pokemon creature?" Thus I came up with the idea of making an online periodic table where each element was reimagined into a creature, and the atomic number, weights, electron configurations, and chemical properties correspond to the creature's "stats". 

## To-Do
As of this point in this project's development, the site is fully functional and can be used as a regular periodic table. However, there are several features that need to be developed further or added in order to make the site as smooth and finished as possible. 
- [ ] Having the element information appear in a popup window when the user clicks on it from the periodic table rather than redirecting it to the element page  
- [ ] Make a working search page (allow the user to be taken to the element's page once they find what they need with the search page
**NOTE:** I have realized that this will probably be the most difficult part of setting up the entire site. From what I have discovered through a bit of research (which I'll need to do more of), in order to have a search function on a website, you need
- a search engine script; one possibility is Sphider, which can be downloaded here: ```http://www.sphider.eu/about.php```
- you need to be connected to a web server (which we currently are not, for now)
- allow the button we made to run a proper .php script upon the action event of the user pressing the button
- if I'll be using Sphider, I'll need to figure some things out with MySQL...

- [ ] Design and draw the pokemon creatures using Adobe Photoshop (this will be the most time consuming part)
- [ ] Add a gallery page so users could browse through the illustrations 
- [ ] Allow the user to click on the illustration of the creature to find out some cool facts about the element and about the creature's design 
- [ ] Make the site responsive -- currently, it doesn't look too great when viewed on a mobile phone 
- [ ] Come up with a good domain name and purchase it 
- [ ] Find a web hosting service to host the site on and officially deploy the site 

## Ideas for Future Implementation
The prototype of this project will be just to get a simple online periodic table that users can navigate, with the added bonus of reimagining each element into a pokemon-style creature. However, I have some pretty big ideas as to how this project can be developed further. 
#### Idea 1: Poke-Table Game
Pokemon cards allow players to battle one another using their collection of pokemon cards, which list stats of each creature and their moves and such. So, what if I made a version of this game but using the element cards? The basic idea is that each player could use their cards and the "stats" on the cards (atomic weight, number, element configuration, and chemical properties, etc) to combine the cards to make molecules (perhaps this idea is less so like the pokemon battles, but more so like the alchemy game where you literally combine elements to make something new). For example, if the user has two H cards and one O card, they'll be allowed to combine the three cards (elements) based on the rules of chemistry to form a new element, or creature, called H2O. 

The whole purpose of this would be to help teach students how molecules form based off various chemical properties. I still don't exactly know how this idea could get implemented, and I am certainly not nearly good enough at chemistry to implement it myself. But, I think it would be a really good addition to this website as it will be a great teaching tool.

#### Idea 2: User Profiles
Users will have the choice to make a profile on the site, which will allow them to collect and trade elements and molecules and "battle" other users. I'd have to think more about the logistics of how all that would work out; for example, would user accounts have "levels", where users can gain experience in order to level up their account and therefore unlock more elements to make more molecules with? Where would this experience come from? Perhaps users can start with a few basic elements, like H and O, and once they combine these elements into molecules (like H2O), they gain a certain amount of experience, level up, and unlock new elements to combine into new molecules. It's something to think about, and it could be a really interesting addition to the site.

