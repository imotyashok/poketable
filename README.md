# Poke-Table
## Concept 
Chemistry is a difficult subject, and it can be especially difficult to get students interested in it. After staring at periodic tables for many, many hours during my brief venture into the field of chemistry and biology, I thought "man, how cool would it be if each element was a pokemon creature?" Thus I came up with the idea of making an online periodic table where each element was reimagined into a creature, and the atomic number, weights, electron configurations, and chemical properties correspond to the creature's "stats". 

## Approach
#### Step 1: Basic Website Outline
- [x] Create an html outline of what the site's pages might look like 
#### Step 2: Implementing Element Pages
- [x] Make a page for each element that the user will be directed to if they click on it; each page should have a back, home, and next button (also decide if this is necessary to do at all... there are 118 elements, which means making 118 pages)
- [x] Collect information about each element
#### Step 3: Setting up the Table
- [x] Figure out how to make the periodic table (I ended up making a literal table using html)
- [ ] Allow the user to hover over each box 
- [ ] Allow the user to click on the element, which will make a pop-up window of the element's page on the current page
#### Step 4: Implementing the Element List Page
- [x] Make a page that contains a list of all the elements; when the user clicks on one of the elements, they'll be taken to that element's page
- [ ] Possibly allow the user to hover over the elements to get a brief preview of them 
#### Step 5: Implementing the Element Search Page
- [x] Make a search box with a text field and enter button
- [ ] Allow the user to be taken to the element's page once they find what they need 
  
  **NOTE:** I have realized that this will probably be the most difficult part of setting up the entire site. From what I have discovered through a bit of research (which I'll need to do more of), in order to have a search function on a website, you need
- a search engine script; one possibility is Sphider, which can be downloaded here: ```http://www.sphider.eu/about.php```
- you need to be connected to a web server (which we currently are not, for now)
- allow the button we made to run a proper .php script upon the action event of the user pressing the button
- if I'll be using Sphider, I'll need to figure some things out with MySQL...

#### Step 6: Making it Pretty 
- [ ] Use CSS to format the raw html and make it look nicer 
- [ ] Design and draw the pokemon creatures using Adobe Photoshop (this will probably be the most time consuming part)
- [ ] Put it all together; overlay the drawings with the periodic table, etc. 
#### Step 7: Making it Live 
- [ ] Come up with a good domain name and purchase it 
- [ ] Find a web hosting service to host the site on  

## Ideas for Future Implementation
The prototype of this project will be just to get a simple online periodic table that users can navigate, with the added bonus of reimagining each element into a pokemon-style creature. However, I have some pretty big ideas as to how this project can be developed further. 
#### Idea 1: Poke-Table Game
Pokemon cards allow players to battle one another using their collection of pokemon cards, which list stats of each creature and their moves and such. So, what if I made a version of this game but using the element cards? The basic idea is that each player could use their cards and the "stats" on the cards (atomic weight, number, element configuration, and chemical properties, etc) to combine the cards to make molecules (perhaps this idea is less so like the pokemon battles, but more so like the alchemy game where you literally combine elements to make something new). For example, if the user has two H cards and one O card, they'll be allowed to combine the three cards (elements) based on the rules of chemistry to form a new element, or creature, called H2O. 

The whole purpose of this would be to help teach students how molecules form based off various chemical properties. I still don't exactly know how this idea could get implemented, and I am certainly not nearly good enough at chemistry to implement it myself. But, I think it would be a really good addition to this website as it will be a great teaching tool.

#### Idea 2: User Profiles
Users will have the choice to make a profile on the site, which will allow them to collect and trade elements and molecules and "battle" other users. I'd have to think more about the logistics of how all that would work out; for example, would user accounts have "levels", where users can gain experience in order to level up their account and therefore unlock more elements to make more molecules with? Where would this experience come from? Perhaps users can start with a few basic elements, like H and O, and once they combine these elements into molecules (like H2O), they gain a certain amount of experience, level up, and unlock new elements to combine into new molecules. It's something to think about, and it could be a really interesting addition to the site.

## Viewing the Site 
This project is still very early in its development; thus, the only way to run it is to download this repository to your local machine and run it locally. If you're using the Google Chrome browser, enter the following command in your terminal:
```
google-chrome index.html 
```
If you're using the Mozilla Firefox browser, you can view it using this command:
```
firefox index.html 
```
