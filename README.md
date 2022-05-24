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
</div>```
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
```Todo```

## Access Required?
```Todo```

# 3.2 - Week 3 Part 2 >

## Rubbish Goals
```Todo```

## Fix your Bin (Links)
```Todo```

## Side Nav
```Todo```

## Trashy but Stylish
```Todo```

# 4.1 - Week 4 Part 1 >

# 4.2 - Week 4 Part 2 >

Last Updated: 22:18 24/05/2022
