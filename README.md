
**PokemonApp**

**See on live on :** [here](https://pedantic-albattani-ccb9a7.netlify.app/) (https://pedantic-albattani-ccb9a7.netlify.app/)

**How to run in local:**

 - clone this repository
 - run `npm install`
 - run `npm run dev`
 - open in `0.0.0.0:3000` or `localhost:3000`

build with

**Libraries** :

 -   NextJs
    
 -   Graphql and Apollo Client
    
 -   Emotion (css in js library)
    
 -   Swiper Js Carousel library
    
 -   Framer in Motion

**Endpoint** : Pokemon API (https://graphql-pokeapi.vercel.app/)

**How to use It**

First you will see some list of cards , so you can swipe to choose ,
there are 2 button in the below the card 

![enter image description here](https://lh3.googleusercontent.com/pw/AM-JKLXIuOZ0ITXM9NoKfe2_Jrsy0f9XVy5lHgtbJBMrU9M4ZfEvncLRuUgbW6CK9dRJ6kj9adHMzHhhGtOPJoern0MdmCJhQCuQaoHBNvFpp_bhxstqzIq_bciTHPlQGgsJsqOOQI5UomYnPnwvpaL354B5=w542-h578-no?authuser=0)


 - `Look this pokemon button detail` is the button for you to see the detail of currently seen pokemon you see in the card list 
 - `Refresh the cards` is the button if you want to randomize the list of cards

**Detail Page**
once you click the `Look This Pokemon Details` button , you'll soon redirect to detail page, in there you'll see the card contain name, species, moves, and other attributes that pokemon has.

you have to click `catch this pokemon` button and you'll see the result with 50% probabilities you'll catch or either you'll lose.
if you lose you'll see try again button and you'll redirected to the home page and see the cardlist again.

but if you win you'll see the text input that you should put some nickname in it with some of text validations and some nickname validation if you have same pokemon with same nickname.

**Collection Page**
in this page you can see your collection and remove the collection you want just with click the button `remove`

**note :**
you can catch the same pokemon whether you already have inside your collection but you have to give the different nickname from the one or some you already have in your collection. the app will let you know if you giving your pokemon the same nickname with the text alert.

