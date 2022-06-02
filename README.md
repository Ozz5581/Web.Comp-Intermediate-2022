# Web.Comp-Intermediate-2022
Solutions for Course: Web.Comp (Intermediate) 2022

# 1.1 - Week 1 Part 1 >

## Pizza Place

#### CSS Code (main.css)

```css
body {
    margin-left: auto;
      margin-right: auto;
width: 400px;
}

h1 {
  text-align: center;
}

h2 {

  text-transform: uppercase;
  background-color: lightsalmon;
  
}

.vego {
  background-color: lightgreen;
}

h3 {
    font-weight: normal;
      font-style: italic;
}

p {
    text-align: right;
}

span {
    font-size: 30px;
}
```

## Vego Pizza

#### HTML Code (index.html)

```html
<link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">
<h1>Pizzas</h1>
<div>
    <h2 class="vego">Margherita <span class="fa fa-leaf"></span></h2>
    <h3>San Marzano tomato, Mozarella, Basil</h3>
    <p>Slice <span>$5</span> | Whole <span>$29</span></p>
</div>

<div>
    <h2>Pepperoni</h2>
    <h3>San Marzano tomato, Mozarella, Pepperoni</h3>
    <p>Slice <span>$6</span> | Whole <span>$32</span></p>
</div>

<div>
    <h2 class="vego">Mushroom <span class="fa fa-leaf"></span></h2>
    <h3>Field Mushrooms, Parmesan, Mozzarella, Porcini, Truffle oil</h3>
    <p>Slice <span>$6</span> | Whole <span>$32</span></p>
</div>
<div>
    <h2 class="vego">Green Pizza <span class="fa fa-leaf"></span></h2>
    <h3>Mozzarella, Goats Cheese, Zucchini, Braised Greens, Spinach</h3>
    <p>Slice <span>$5</span> | Whole <span>$29</span></p>
</div>

<div>
    <h2>Capricciosa</h2>
    <h3>San Marzano Tomato, Mozzarella, Ham, Mushroom, Olives</h3>
    <p>Slice <span>$6</span> | Whole <span>$32</span></p>
</div>
```

#### CSS Code

```css
body {
    margin-left: auto;
      margin-right: auto;
width: 400px;
}

h1 {
  text-align: center;
}

h2 {

  text-transform: uppercase;
  
}

.vego {
    color: green;
}

h3 {
    font-weight: normal;
      font-style: italic;
}

p {
    text-align: right;
}

span {
    font-size: 30px;
}
```

## Pizza Promotion

#### HTML Code (index.html)

```html
<link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">
<h1>Pizzas</h1>
<img alt="Promotion: Thursdays all pizzas 50% off!" src="pizza-promotion.png">
<div>
    <h2 class="vego">Margherita <span class="fa fa-leaf"></span></h2>
    <h3>San Marzano tomato, Mozarella, Basil</h3>
    <p>Slice <span>$5</span> | Whole <span>$29</span></p>
</div>

<div>
    <h2>Pepperoni</h2>
    <h3>San Marzano tomato, Mozarella, Pepperoni</h3>
    <p>Slice <span>$6</span> | Whole <span>$32</span></p>
</div>

<div>
    <h2 class="vego">Mushroom <span class="fa fa-leaf"></span></h2>
    <h3>Field Mushrooms, Parmesan, Mozzarella, Porcini, Truffle oil</h3>
    <p>Slice <span>$6</span> | Whole <span>$32</span></p>
</div>
<div>
    <h2 class="vego">Green Pizza <span class="fa fa-leaf"></span></h2>
    <h3>Mozzarella, Goats Cheese, Zucchini, Braised Greens, Spinach</h3>
    <p>Slice <span>$5</span> | Whole <span>$29</span></p>
</div>

<div>
    <h2>Capricciosa</h2>
    <h3>San Marzano Tomato, Mozzarella, Ham, Mushroom, Olives</h3>
    <p>Slice <span>$6</span> | Whole <span>$32</span></p>
</div>
```

## Pretty Pizza Menu

#### CSS Code (main.css)

```css
body {
  width: 460px;
  margin: auto;
  background-color: rgba(0, 0, 0, 0.5);
  color: white;
   background-image: url("pizza-background.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

h1 {
  text-align: center;
}

h2 {
  text-transform: uppercase;

}

h3 {
  font-weight: normal;
  font-style: italic;
}

p {
  text-align: right;
}

span {
  font-size: 28px;
}

.fa-leaf {
  color: green;
}

div {
  margin-top: 20px;
   margin-bottom: 20px;
  padding:20px;
    background-color: rgba(0, 0, 0, 0.5);
}
```

# 1.2 - Week 1 Part 2 >

## WC Fest

#### CSS Code (main.css)

```css
body {
  text-align: center;
}

h1 {
  font-size: 160px;
  text-transform: uppercase;
  margin: 0;
  font-weight: 100;
}

h2 {
  font-size: 36px;
  margin-top: 0;
  font-weight: 400;
}

a {
  text-transform: uppercase;
  font-size: 24px;
  color: black;
}

a.main-action {
 display: inline-block;
 border-radius: 2px;
 background-color: black;
 color: white;
 border: 4px;
 text-decoration: none;
 border-style: solid;
 border-color: black;
 font-size: 25px;
 padding-left: 17px;
 padding-right: 17px;
 padding-top: 16px;
 padding-bottom: 16px;
}

div {
  margin: 40px 0;
}
```

## Festival Lineup

#### CSS Code (main.css)

```css
body {
  text-align: center;
}

h1 {
  font-size: 160px;
  text-transform: uppercase;
  margin: 0;
  font-weight: 100;
}

h2 {
  font-size: 36px;
  margin-top: 0;
  font-weight: 400;
}

a {
  text-transform: uppercase;
  font-size: 24px;
  color: black;
}

a.main-action {
 display: inline-block;
  border-radius: 2px;
    background-color: black;
  color: white;
 border: 4px;
  text-decoration: none;
  border-style: solid;
  border-color: black;
    font-size: 25px;
  padding-left: 17px;
    padding-right: 17px;
    padding-top: 16px;
    padding-bottom: 16px;
}

a:hover {
  text-decoration: none;
  background-color: rgb(205, 205, 205);
}

a:main-action:hover {
  color: white;
  background-color: black;
}

div {
  margin: 40px 0;
}
```

## Three Day Festival

#### CSS Code (main.css)

```css
body {
  text-align: center;
}

h1 {
  font-size: 160px;
  text-transform: uppercase;
  margin: 0;
  font-weight: 100;
}

h2 {
  font-size: 36px;
  margin-top: 0;
  font-weight: 400;
}

a {
  text-transform: uppercase;
  font-size: 24px;
  color: black;
}

a.main-action {
 display: inline-block;
  border-radius: 2px;
    background-color: black;
  color: white;
 border: 4px;
  text-decoration: none;
  border-style: solid;
  border-color: black;
    font-size: 25px;
  padding-left: 17px;
    padding-right: 17px;
    padding-top: 16px;
    padding-bottom: 16px;
}

a:hover {
  text-decoration: none;
  background-color: rgb(205, 205, 205);
}

a.main-action:hover {
  color: white;
  background-color: black;
}

div {
  margin: 40px 0;
  display: inline-block;
  vertical-align: top;
  width: 20px;
}
```

## Throw Your Own Festival

#### CSS Code (main.css)

```css
@import url('https://fonts.googleapis.com/css2?family=Quattrocento&family=Arvo&family=Fjalla+One&family=Barrio');

body {
  background-color: lightgray;
  text-align: center;
  font-family: 'Quattrocento';
}

h1 {
  font-size: 160px;
  text-transform: uppercase;
  margin: 0;
  font-weight: 100;
}

h2 {
  font-size: 36px;
  margin-top: 0;
  font-weight: 400;
}

a {
  text-transform: uppercase;
  font-size: 24px;
  color: black;
}

a.main-action {
  display: inline-block;
  border-radius: 2px;
  background-color: black;
  color: white;
  border: 4px;
  text-decoration: none;
  border-style: solid;
  border-color: black;
  font-size: 25px;
  padding-left: 17px;
  padding-right: 17px;
  padding-top: 16px;
  padding-bottom: 16px;
}

a:hover {
  text-decoration: none;
  background-color: rgb(205, 205, 205);
}

a.main-action:hover {
  color: white;
  background-color: black;
}

div {
  margin: 40px 0;
  display: inline-block;
  vertical-align: top;
  width: 20px;
}
```

# 2.1 - Week 2 Part 1 >

## You're Invited!

#### HTML Code (index.html)

```html
<form>
    <h1>RSVP</h1>
    <h2>Big Birthday Bash - 4 May @ 6pm</h2>
    <label for="name">Full name </label>
    <input type="text" id="name" name="name">
</form>
```
## Respond, Please

#### HTML Code (index.html)

```html
<form>
    <h1>RSVP</h1>
    <h2>Big Birthday Bash - 4 May @ 6pm</h2>
    <label for="name">Full name<span>*</span></label>
    <input type="text" name="name" id="name" required>
    <input type="submit" value="Send RSVP">
</form>
```

## No Spam, Please

#### HTML Code (index.html)

```html
<form>
    <h1>RSVP</h1>
    <h2>Big Birthday Bash - 4 May @ 6pm</h2>
    <div>
        <label for="name">Full name<span>*</span></label>
        <input type="text" name="name" id="name" required>
    </div>
    <div>
        <label for="email">Email<span>*</span></label>
        <input type="email" name="email" id="email" required>
    </div>
    <div>
        <input type="submit" value="Send RSVP">
    </div>
</form>
```


## A Fancy Bash

#### HTML Code (index.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h1>RSVP</h1>
    <h2>Big Birthday Bash - 4 May @ 6pm</h2>
    <div>
        <label for="name">Full name<span>*</span></label>
        <input type="text" name="name" id="name" required>
    </div>

    <div>
        <label for="email">Email<span>*</span></label>
        <input type="email" name="email" id="email" required>
    </div>

    <div>
        <input class="button" type="submit" value="Send RSVP">
    </div>
</form>
```

#### CSS Code (main.css)

```css
button {
  color: black;
}
```

# 2.2 - Week 2 Part 2 >

## Adopt a VirtuPet

#### HTML Code (index.html)

```html
<link rel="stylesheet" href="main.css">
<h1>VirtuPet</h1>
<p>Adopt your first virtual pet today!</p>
<p><a class="button" href="step1.html">Get started</a></p>
```

#### HTML Code (step1.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>1. Your details</h2>
    <div>
        <label for="firstname">First name</label>
        <input type="text" id="firstname" name="firstname">
    </div>

    <div>
        <label for="username">Create a username</label>
        <input type="text" id="username" name="username">
    </div>

    <div>
        <a class="button next" href="step2.html">Next</a>
    </div>
</form>
```

#### HTML Code (step2.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>2. Name your pet</h2>
    <img src="virtupet-hi.png" alt="Drawing of a cute monster saying 'Hi!'">
    <p>You've been matched with this cutie! You'll need to choose a name for your new pet...</p>
    <div>
        <label for="petname">Pet name</label>
        <input type="text" id="petname" name="petname">
    </div>
    <div>
        <a class="button next" href="step3.html">Next</a>
    </div>
</form>
```

#### HTML Code (step3.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>3. Pet personality</h2>
    <p>Pick three words to describe your pet's personality!</p>
    <div>
        <label for="word1">Word 1</label>
        <input type="text" id="word1" name="word1">
    </div>

    <div>
        <label for="word2">Word 2</label>
        <input type="text" id="word2" name="word2">
    </div>

    <div>
        <label for="word3">Word 3</label>
        <input type="text" id="word3" name="word3">
    </div>

    <div>
        <a class="button next" href="index.html">Finish and adopt</a>
    </div>
</form>
```

## Forth and Back

#### HTML Code (step1.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>1. Your details</h2>
    <div>
        <label for="firstname">First name</label>
        <input type="text" id="firstname" name="firstname">
    </div>

    <div>
        <label for="username">Create a username</label>
        <input type="text" id="username" name="username">
    </div>

    <div>
        <a class="button next" href="step2.html">Next</a>
        <a class="button" href="index.html">Back</a>
    </div>
</form>
```

#### HTML Code (step2.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>2. Name your pet</h2>
    <img src="virtupet-hi.png" alt="Drawing of a cute monster saying 'Hi!'">
    <p>You've been matched with this cutie! You'll need to choose a name for your new pet...</p>
    <div>
        <label for="petname">Pet name</label>
        <input type="text" id="petname" name="petname">
    </div>
    <div>
        <a class="button next" href="step3.html">Next</a>
        <a class="button" href="step1.html">Back</a>
    </div>
</form>
```

#### HTML Code (step3.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>3. Pet personality</h2>
    <p>Pick three words to describe your pet's personality!</p>
    <div>
        <label for="word1">Word 1</label>
        <input type="text" id="word1" name="word1">
    </div>

    <div>
        <label for="word2">Word 2</label>
        <input type="text" id="word2" name="word2">
    </div>

    <div>
        <label for="word3">Word 3</label>
        <input type="text" id="word3" name="word3">
    </div>

    <div>
        <a class="button next" href="index.html">Finish and adopt</a>
        <a class="button" href="step2.html">Back</a>
    </div>
</form>
```

#### CSS Code (main.css)

```css
body {
  font-size: 24px;
  width: 500px;
  margin: 60px auto;
}

h1, h2, p { text-align: center; }
h2 { margin-top: 60px; }
div { margin: 20px 0; }

img { 
  display: block;
  margin: auto;
}

input {
  padding: 20px;
  width: 460px;
  border: 2px solid lightgrey;
  border-radius: 10px;
}

.button {
  border: none;
  text-decoration: none;
  display: inline-block;
  padding: 20px 40px;
  background: tomato;
  color: white;
  border-radius: 40px;
}

.button:hover {
  background: orangered;
  color: white;
}

.next {
  float: right;
}
```

## Back in Style

#### HTML Code (step1.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>1. Your details</h2>
    <div>
        <label for="firstname">First name</label>
        <input type="text" id="firstname" name="firstname">
    </div>
    <div>
        <label for="username">Create a username</label>
        <input type="text" id="username" name="username">
    </div>
    <div>
        <a class="button next" href="step2.html">Next</a>
        <a class="button back" href="index.html">Back</a>
    </div>
</form>
```

#### HTML Code (step2.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>2. Name your pet</h2>
    <img src="virtupet-hi.png" alt="Drawing of a cute monster saying 'Hi!'">
    <p>You've been matched with this cutie! You'll need to choose a name for your new pet...</p>
    <div>
        <label for="petname">Pet name</label>
        <input type="text" id="petname" name="petname">
    </div>
    <div>
        <a class="button next" href="step3.html">Next</a>
        <a class="button back" href="step1.html">Back</a>
    </div>
</form>
```

#### HTML Code (step3.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>3. Pet personality</h2>
    <p>Pick three words to describe your pet's personality!</p>
    <div>
        <label for="word1">Word 1</label>
        <input type="text" id="word1" name="word1">
    </div>

    <div>
        <label for="word2">Word 2</label>
        <input type="text" id="word2" name="word2">
    </div>

    <div>
        <label for="word3">Word 3</label>
        <input type="text" id="word3" name="word3">
    </div>

    <div>
        <a class="button next" href="index.html">Finish and adopt</a>
        <a class="button back" href="step2.html">Back</a>
    </div>
</form>
```

#### CSS Code (main.css)

```css
body {
  font-size: 24px;
  width: 500px;
  margin: 60px auto;
}

h1, h2, p { text-align: center; }
h2 { margin-top: 60px; }
div { margin: 20px 0; }

img { 
  display: block;
  margin: auto;
}

input {
  padding: 20px;
  width: 460px;
  border: 2px solid lightgrey;
  border-radius: 10px;
}

.button {
  border: none;
  text-decoration: none;
  display: inline-block;
  padding: 20px 40px;
  background: tomato;
  color: white;
  border-radius: 40px;
}

.button:hover {
  background: orangered;
  color: white;
}

.next {
  float: right;
}
.back {
  float: left;
  background-color: white;
  color: orangered;
  border-color: orangered;
  border: 3px solid;
}
```

## Adoption Celebration

#### HTML Code (success.html)

```html
<link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="success.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">
<h1>(insert some text here idk)</h1>
```

#### HTML Code (step3.html)

```html
<link rel="stylesheet" href="main.css">
<form>
    <h2>3. Pet personality</h2>
    <p>Pick three words to describe your pet's personality!</p>
    <div>
        <label for="word1">Word 1</label>
        <input type="text" id="word1" name="word1">
    </div>

    <div>
        <label for="word2">Word 2</label>
        <input type="text" id="word2" name="word2">
    </div>

    <div>
        <label for="word3">Word 3</label>
        <input type="text" id="word3" name="word3">
    </div>

    <div>
        <a class="button next" href="success.html">Finish and adopt</a>
        <a class="button back" href="step2.html">Back</a>
    </div>
</form>
```

# 3.1 - Week 3 Part 1 >

## Elephant Mountain

#### HTML Code (index.html)

```html
<link href="main.css" rel="stylesheet">
<h2>Camping at Elephant Mountain</h2>
<form>
    <div>
        <label for="arrival-date">Arrival date*</label>
        <input type="date" id="arrival-date" name="arrival-date" required>
    </div>
    <div>
        <label for="departure-date">Departure date*</label>
        <input type="date" id="departure-date" name="departure-date" required>
    </div>
    <div>
        <input class="button" type="submit" value="Find camping">
    </div>
</form>
```

## Party Size

#### HTML Code (index.html)

```html
<link href="main.css" rel="stylesheet">
<h2>Camping at Elephant Mountain</h2>
<form>
    <div>
        <label for="arrival-date">Arrival date*</label>
        <input type="date" id="arrival-date" name="arrival-date" required>
    </div>

    <div>
        <label for="departure-date">Departure date*</label>
        <input type="date" id="departure-date" name="departure-date" required>
    </div>

    <div>
        <label for="size">Party size*</label>
        <input type="number" id="size" name="size" min="1" max="50" value="2" required>
    </div>

    <div>
        <label for="pNumber">Pass number</label>
        <input placeholder="optional" type="text" id="pNumber" name="pNumber" size="8" value="014-994">
    </div>

    <div>
        <input class="button" type="submit" value="Find camping">
    </div>
</form>
```
## Camping or Glamping

#### HTML Code (index.html)
```html
<link href="main.css" rel="stylesheet">
<h2>Camping at Elephant Mountain</h2>
<form>
    <div>
        <label for="arrival-date">Arrival date*</label>
        <input type="date" id="arrival-date" name="arrival-date" required>
    </div>
    <div>
        <label for="departure-date">Departure date*</label>
        <input type="date" id="departure-date" name="departure-date" required>
    </div>
    <div>
        <label for="size">Party size*</label>
        <input type="number" id="size" name="size" min="1" max="50" value="2" required>
    </div>
    <div>
        <label for="pNumber">Pass number</label>
        <input placeholder="optional" type="text" id="pNumber" name="pNumber" size="8" value="014-994">
    </div>
    <div>
        <p>Accommodation type*</p>
        <label><input type="radio" id="check1" name="check1" checked> Campground</label>
        <label><input type="radio" id="check2" name="check1"> Caravan park</label>
        <label><input type="radio" id="check3" name="check1"> Glamping tent</label>
    </div>
    <div>
        <input class="button" type="submit" value="Find camping">
    </div>
</form>
```

## Access Required?

#### HTML Code (index.html)
```html
<link href="main.css" rel="stylesheet">
<h2>Camping at Elephant Mountain</h2>
<form>
    <div>
        <label for="arrival-date">Arrival date*</label>
        <input type="date" id="arrival-date" name="arrival-date" required>
    </div>
    <div>
        <label for="departure-date">Departure date*</label>
        <input type="date" id="departure-date" name="departure-date" required>
    </div>
    <div>
        <label for="size">Party size*</label>
        <input type="number" id="size" name="size" min="1" max="50" value="2" required>
    </div>
    <div>
        <label for="pNumber">Pass number</label>
        <input placeholder="optional" type="text" id="pNumber" name="pNumber" size="8" value="014-994">
    </div>
    <div>
        <p>Accommodation type*</p>
        <label><input type="radio" id="check1" name="check1" checked> Campground</label>
        <label><input type="radio" id="check2" name="check1"> Caravan park</label>
        <label><input type="radio" id="check3" name="check1"> Glamping tent</label>
    </div>
    <div>
        <label><input type="checkbox" id="check4" name="check5"> Do you need accessible toilets?</label>
    </div>
    <div>
        <input class="button" type="submit" value="Find camping">
    </div>
</form>
```
#### CSS Code (main.css)

```css
body {
  width: 640px;
  margin: auto;
  font-size: 20px;
  background-image: url('camping.jpeg');
}

div {
  margin: 30px 0;
  background-color: white;
}

label {
  display: block;
  line-height: 1.8;
}

p {
  margin-bottom: 0;
  line-height: 1.8;
}

input {
  padding: 16px;  
}
```

# 3.2 - Week 3 Part 2 >

## Rubbish Goals

#### HTML Code (index.html)
```html
<link rel="stylesheet" href="main.css">

<nav>
    <a class="nav-link" href="index.html">Repair or replace bins</a>
    <a class="nav-link" href="report.html">Report illegal dumping</a>
    <a class="nav-link" href="book.html">Hard waste collection</a>
</nav>

<form>
    <h2>Request a bin repair or replacement</h2>

    <div>
        <p>Nature of request*</p>
        <label>
            <input type="radio" id="request-lid" name="request" value="lid">
            Missing / damaged lid (repair)
        </label>
        <label>
            <input type="radio" id="request-wheels" name="request" value="wheel">
            Missing / damaged wheels (repair)
        </label>
        <label>
            <input type="radio" id="request-bin" name="request" value="bin">
            Missing / damaged bin body (replace)
        </label>
    </div>

    <div>
        <p>Type of bin*</p>
        <label>
            <input type="radio" id="bin-rubbish" name="bin" value="rubbish">
            General rubbish waste (red or dark green lid)
        </label>
        <label>
            <input type="radio" id="bin-recycling" name="bin" value="recycling">
            Recycling (yellow lid)
        </label>
        <label>
            <input type="radio" id="bin-garden" name="bin" value="garden">
            Garden green waste (light green lid)
        </label>
    </div>

    <div>
        <p>Size of bin*</p>
        <label>
            <input type="radio" id="size-120" name="size" value="120">
            120L (small wheelie bin)
        </label>
        <label>
            <input type="radio" id="size-240" name="size" value="240">
            240L (large wheelie bin)
        </label>
        <label>
            <input type="radio" id="size-660" name="size" value="660">
            660L (small skip bin)
        </label>
        <label>
            <input type="radio" id="size-1100" name="size" value="1100">
            1100L (large skip bin)
        </label>
    </div>

    <div>
        <label for="details">Special instructions (optional)</label>
        <input type="text" id="details" name="details" size=40 placeholder="e.g. property hard to find, preferred times">
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```
#### HTML Code (report.html)
```html
<link rel="stylesheet" href="main.css">

<nav>
    <a class="nav-link" href="index.html">Repair or replace bins</a>
    <a class="nav-link" href="report.html">Report illegal dumping</a>
    <a class="nav-link" href="book.html">Hard waste collection</a>
</nav>

<form>
    <h2>Report illegal dumping location</h2>

    <div>
        <label for="address">Street Address*</label>
        <input type="text" id="address" name="address" size=40 required>
    </div>
    <div>
        <label for="suburb">Suburb*</label>
        <input type="text" id="suburb" name="suburb" size=30 required>
    </div>
    <div>
        <label for="postcode">Postcode*</label>
        <input type="text" id="postcode" name="postcode" size=5 required>
    </div>

    <div>
        <label for="date">Date observed*</label>
        <input type="date" id="date" name="date">
    </div>

    <div>
        <label for="details">Details (optional)</label>
        <input type="text" id="details" name="details" size=40 placeholder="Provide any extra details here">
    </div>
    <div>
        <label>
            <input type="checkbox" id="followup" name="followup">
            I want to be contacted about this enquiry.
        </label>
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```
#### HTML Code (book.html)
```html
<link rel="stylesheet" href="main.css">

<nav>
    <a class="nav-link" href="index.html">Repair or replace bins</a>
    <a class="nav-link" href="report.html">Report illegal dumping</a>
    <a class="nav-link" href="book.html">Hard waste collection</a>
</nav>

<form>
    <h2>Book a hard waste collection</h2>
    <div>
        <p>What types of hard rubbish do you intend to put out for collection?</p>
        <label>
            <input type="checkbox" id="type-mattress" name="type-mattress">
            Mattresses
        </label>
        <label>
            <input type="checkbox" id="type-hard" name="type-hard">
            Hard and metal waste (up to 2 square metres)
        </label>
        <label>
            <input type="checkbox" id="type-green" name="type-green">
            Green waste (up to 4 square metres)
        </label>
        <label>
            <input type="checkbox" id="type-other" name="type-other">
            Other (please describe)
        </label>
        <input type="text" id="describe-other" name="describe-other" size=40 placeholder="e.g. furniture items, washing machine, etc.">
    </div>

    <div>
        <p>Where will you leave your hard rubbish collection?*</p>
        <label>
            <input type="radio" id="where-frontyard" name="where" value="frontyard">
            Frontyard
        </label>
        <label>
            <input type="radio" id="where-driveway" name="where" value="driveway">
            Driveway
        </label>
    </div>

    <div>
        <p>By submitting this application for a hard rubbish collection online, all information supplied will be provided directly to Council and its contractor as an interested third party to enable the service to occur.</p>
        <label>
            <input type="checkbox" id="agreement" name="agreement" required>
            I understand and accept the above terms.*
        </label>
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```
#### CSS Code (main.css)
```css
body {
  font-size: 20px;  
}

form {
  width: 450px;
  margin: 30px auto;
}

h2 { 
  text-align: center;
  margin-top: 60px;
}

div { 
  margin: 10px 0;
  display: inline-block;
}

input {
  padding: 15px;
  border: 2px solid lightgray;
}

label {
  display: block;
  line-height: 1.8;
}

.button {
  border: none;
  text-decoration: none;
  display: inline-block;
  padding: 20px 40px;
  background: seagreen;
  color: white;
  border-radius: 4px;
  border: 2px solid seagreen;
}

.button:hover {
  border-color: mediumseagreen;
  background: mediumseagreen;
  color: white;
}

nav {
  padding: 20px;
  background-color: mediumseagreen;
  color: white;
  text-decoration: none;
  text-align: center;
  display: inline-block;   

}

.nav-link {
  padding: 20px;
  background-color: mediumseagreen;
  color: white;
  display: inline-block;   
  text-decoration: none;
  text-align: center;
  display: inline-block;


}body {
  font-size: 20px;  
}

form {
  width: 450px;
  margin: 30px auto;
}

h2 { 
  text-align: center;
  margin-top: 60px;
}

div { 
  margin: 10px 0;
  display: inline-block;
}

input {
  padding: 15px;
  border: 2px solid lightgray;
}

label {
  display: block;
  line-height: 1.8;
}

.button {
  border: none;
  text-decoration: none;
  display: inline-block;
  padding: 20px 40px;
  background: seagreen;
  color: white;
  border-radius: 4px;
  border: 2px solid seagreen;
}

.button:hover {
  border-color: mediumseagreen;
  background: mediumseagreen;
  color: white;
}

```
## Fix your Bin (Links)

#### HTML Code (index.html)
```html
<link rel="stylesheet" href="main.css">

<nav>
    <a class="nav-link active" href="index.html">Repair or replace bins</a>
    <a class="nav-link" href="report.html">Report illegal dumping</a>
    <a class="nav-link" href="book.html">Hard waste collection</a>
</nav>

<form>
    <h2>Request a bin repair or replacement</h2>

    <div>
        <p>Nature of request*</p>
        <label>
            <input type="radio" id="request-lid" name="request" value="lid">
            Missing / damaged lid (repair)
        </label>
        <label>
            <input type="radio" id="request-wheels" name="request" value="wheel">
            Missing / damaged wheels (repair)
        </label>
        <label>
            <input type="radio" id="request-bin" name="request" value="bin">
            Missing / damaged bin body (replace)
        </label>
    </div>

    <div>
        <p>Type of bin*</p>
        <label>
            <input type="radio" id="bin-rubbish" name="bin" value="rubbish">
            General rubbish waste (red or dark green lid)
        </label>
        <label>
            <input type="radio" id="bin-recycling" name="bin" value="recycling">
            Recycling (yellow lid)
        </label>
        <label>
            <input type="radio" id="bin-garden" name="bin" value="garden">
            Garden green waste (light green lid)
        </label>
    </div>

    <div>
        <p>Size of bin*</p>
        <label>
            <input type="radio" id="size-120" name="size" value="120">
            120L (small wheelie bin)
        </label>
        <label>
            <input type="radio" id="size-240" name="size" value="240">
            240L (large wheelie bin)
        </label>
        <label>
            <input type="radio" id="size-660" name="size" value="660">
            660L (small skip bin)
        </label>
        <label>
            <input type="radio" id="size-1100" name="size" value="1100">
            1100L (large skip bin)
        </label>
    </div>

    <div>
        <label for="details">Special instructions (optional)</label>
        <input type="text" id="details" name="details" size=40 placeholder="e.g. property hard to find, preferred times">
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```

#### HTML Code (report.html)
```html
<link rel="stylesheet" href="main.css">

<nav>
    <a class="nav-link" href="index.html">Repair or replace bins</a>
    <a class="nav-link active" href="report.html">Report illegal dumping</a>
    <a class="nav-link" href="book.html">Hard waste collection</a>
</nav>

<form>
    <h2>Report illegal dumping location</h2>

    <div>
        <label for="address">Street Address*</label>
        <input type="text" id="address" name="address" size=40 required>
    </div>
    <div>
        <label for="suburb">Suburb*</label>
        <input type="text" id="suburb" name="suburb" size=30 required>
    </div>
    <div>
        <label for="postcode">Postcode*</label>
        <input type="text" id="postcode" name="postcode" size=5 required>
    </div>

    <div>
        <label for="date">Date observed*</label>
        <input type="date" id="date" name="date">
    </div>

    <div>
        <label for="details">Details (optional)</label>
        <input type="text" id="details" name="details" size=40 placeholder="Provide any extra details here">
    </div>
    <div>
        <label>
            <input type="checkbox" id="followup" name="followup">
            I want to be contacted about this enquiry.
        </label>
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```

#### HTML Code (book.html)
```html
<link rel="stylesheet" href="main.css">

<nav>
    <a class="nav-link" href="index.html">Repair or replace bins</a>
    <a class="nav-link" href="report.html">Report illegal dumping</a>
    <a class="nav-link active" href="book.html">Hard waste collection</a>
</nav>

<form>
    <h2>Book a hard waste collection</h2>
    <div>
        <p>What types of hard rubbish do you intend to put out for collection?</p>
        <label>
            <input type="checkbox" id="type-mattress" name="type-mattress">
            Mattresses
        </label>
        <label>
            <input type="checkbox" id="type-hard" name="type-hard">
            Hard and metal waste (up to 2 square metres)
        </label>
        <label>
            <input type="checkbox" id="type-green" name="type-green">
            Green waste (up to 4 square metres)
        </label>
        <label>
            <input type="checkbox" id="type-other" name="type-other">
            Other (please describe)
        </label>
        <input type="text" id="describe-other" name="describe-other" size=40 placeholder="e.g. furniture items, washing machine, etc.">
    </div>

    <div>
        <p>Where will you leave your hard rubbish collection?*</p>
        <label>
            <input type="radio" id="where-frontyard" name="where" value="frontyard">
            Frontyard
        </label>
        <label>
            <input type="radio" id="where-driveway" name="where" value="driveway">
            Driveway
        </label>
    </div>

    <div>
        <p>By submitting this application for a hard rubbish collection online, all information supplied will be provided directly to Council and its contractor as an interested third party to enable the service to occur.</p>
        <label>
            <input type="checkbox" id="agreement" name="agreement" required>
            I understand and accept the above terms.*
        </label>
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```

#### CSS Code (main.css)
```css
body {
  font-size: 20px;
  padding-top: 60px;
}

form {
  width: 450px;
  margin: 30px auto;
  margin-top: 60px;
}

h2 {
  text-align: center;
}

div {
  margin: 10px 0;
  display: inline-block;
}

input {
  padding: 15px;
  border: 2px solid lightgray;
}

label {
  display: block;
  line-height: 1.8;
}

.button {
  border: none;
  text-decoration: none;
  display: inline-block;
  padding: 20px 40px;
  background: seagreen;
  color: white;
  border-radius: 4px;
  border: 2px solid seagreen;
}

.button:hover {
  border-color: mediumseagreen;
  background: mediumseagreen;
  color: white;
}

nav {
  background-color: mediumseagreen;
  text-align: center;
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
}

.nav-link {
  text-decoration: none;
  color: white;
  display: inline-block;
  padding: 20px;

}

.active {
  background-color: seagreen;
}

.nav-link:hover {
  background-color: seagreen;
}
```

## Side Nav

#### CSS Code (main.css)
```css
body {
  font-size: 20px;
  padding-top: 60px;
  padding-left: 300px;
}

form {
  width: 450px;
  margin: 30px auto;
  margin-top: 60px;
}

h2 {
  text-align: center;
}

div {
  margin: 10px 0;
  display: inline-block;
}

input {
  padding: 15px;
  border: 2px solid lightgray;
}

label {
  display: block;
  line-height: 1.8;
}

.button {
  border: none;
  text-decoration: none;
  display: inline-block;
  padding: 20px 40px;
  background: seagreen;
  color: white;
  border-radius: 4px;
  border: 2px solid seagreen;
}

.button:hover {
  border-color: mediumseagreen;
  background: mediumseagreen;
  color: white;
}

nav {
  background-color: mediumseagreen;
  text-align: left;
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  width: 300px;
  bottom: 0;

}

.nav-link {
  text-decoration: none;
  color: white;
  display: inline-block;
  padding: 20px;
  width: 260px;
}

.active {
  background-color: seagreen;
}

.nav-link:hover {
  background-color: seagreen;
}
```

## Trashy but Stylish

#### HTML Code (index.html)
```html
<link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">

<nav>
    <a class="nav-link active" href="index.html"><span class="fa fa-name"></span>Repair or replace bins</a>
    <a class="nav-link" href="report.html"><span class="fa fa-name"></span>Report illegal dumping</a>
    <a class="nav-link" href="book.html"><span class="fa fa-name"></span>Hard waste collection</a>
</nav>

<form>
    <h2>Request a bin repair or replacement</h2>

    <div>
        <p>Nature of request*</p>
        <label>
            <input type="radio" id="request-lid" name="request" value="lid">
            Missing / damaged lid (repair)
        </label>
        <label>
            <input type="radio" id="request-wheels" name="request" value="wheel">
            Missing / damaged wheels (repair)
        </label>
        <label>
            <input type="radio" id="request-bin" name="request" value="bin">
            Missing / damaged bin body (replace)
        </label>
    </div>

    <div>
        <p>Type of bin*</p>
        <label>
            <input type="radio" id="bin-rubbish" name="bin" value="rubbish">
            General rubbish waste (red or dark green lid)
        </label>
        <label>
            <input type="radio" id="bin-recycling" name="bin" value="recycling">
            Recycling (yellow lid)
        </label>
        <label>
            <input type="radio" id="bin-garden" name="bin" value="garden">
            Garden green waste (light green lid)
        </label>
    </div>

    <div>
        <p>Size of bin*</p>
        <label>
            <input type="radio" id="size-120" name="size" value="120">
            120L (small wheelie bin)
        </label>
        <label>
            <input type="radio" id="size-240" name="size" value="240">
            240L (large wheelie bin)
        </label>
        <label>
            <input type="radio" id="size-660" name="size" value="660">
            660L (small skip bin)
        </label>
        <label>
            <input type="radio" id="size-1100" name="size" value="1100">
            1100L (large skip bin)
        </label>
    </div>

    <div>
        <label for="details">Special instructions (optional)</label>
        <input type="text" id="details" name="details" size=40 placeholder="e.g. property hard to find, preferred times">
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```

#### HTML Code (report.html)
```html
<link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">

<nav>
    <a class="nav-link" href="index.html"><span class="fa fa-name"></span>Repair or replace bins</a>
    <a class="nav-link active" href="report.html"><span class="fa fa-name"></span>Report illegal dumping</a>
    <a class="nav-link" href="book.html"><span class="fa fa-name"></span>Hard waste collection</a>
</nav>

<form>
    <h2>Report illegal dumping location</h2>

    <div>
        <label for="address">Street Address*</label>
        <input type="text" id="address" name="address" size=40 required>
    </div>
    <div>
        <label for="suburb">Suburb*</label>
        <input type="text" id="suburb" name="suburb" size=30 required>
    </div>
    <div>
        <label for="postcode">Postcode*</label>
        <input type="text" id="postcode" name="postcode" size=5 required>
    </div>

    <div>
        <label for="date">Date observed*</label>
        <input type="date" id="date" name="date">
    </div>

    <div>
        <label for="details">Details (optional)</label>
        <input type="text" id="details" name="details" size=40 placeholder="Provide any extra details here">
    </div>
    <div>
        <label>
            <input type="checkbox" id="followup" name="followup">
            I want to be contacted about this enquiry.
        </label>
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```

#### HTML Code (book.html)
```html
<link rel="stylesheet" href="main.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css">

<nav>
    <a class="nav-link" href="index.html"><span class="fa fa-name"></span>Repair or replace bins</a>
    <a class="nav-link" href="report.html"><span class="fa fa-name"></span>Report illegal dumping</a>
    <a class="nav-link active" href="book.html"><span class="fa fa-name"></span>Hard waste collection</a>
</nav>

<form>
    <h2>Book a hard waste collection</h2>
    <div>
        <p>What types of hard rubbish do you intend to put out for collection?</p>
        <label>
            <input type="checkbox" id="type-mattress" name="type-mattress">
            Mattresses
        </label>
        <label>
            <input type="checkbox" id="type-hard" name="type-hard">
            Hard and metal waste (up to 2 square metres)
        </label>
        <label>
            <input type="checkbox" id="type-green" name="type-green">
            Green waste (up to 4 square metres)
        </label>
        <label>
            <input type="checkbox" id="type-other" name="type-other">
            Other (please describe)
        </label>
        <input type="text" id="describe-other" name="describe-other" size=40 placeholder="e.g. furniture items, washing machine, etc.">
    </div>

    <div>
        <p>Where will you leave your hard rubbish collection?*</p>
        <label>
            <input type="radio" id="where-frontyard" name="where" value="frontyard">
            Frontyard
        </label>
        <label>
            <input type="radio" id="where-driveway" name="where" value="driveway">
            Driveway
        </label>
    </div>

    <div>
        <p>By submitting this application for a hard rubbish collection online, all information supplied will be provided directly to Council and its contractor as an interested third party to enable the service to occur.</p>
        <label>
            <input type="checkbox" id="agreement" name="agreement" required>
            I understand and accept the above terms.*
        </label>
    </div>
    <div>
        <input class="button" type="submit" value="Submit">
    </div>
</form>
```

# 4.1 - Week 4 Part 1 >

# 4.2 - Week 4 Part 2 >

Last Updated: 10:11 27/05/2022
