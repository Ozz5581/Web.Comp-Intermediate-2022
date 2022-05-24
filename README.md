# Web.Comp-Intermediate-2022
Answers for Grok Course: Web.Comp (Intermediate) 2022

# 1.1 >

## Pizza Place

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

#### HTML Code

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

#### HTML Code

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

#### CSS Code

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

# 1.2 >

## WC Fest

#### CSS Code

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

#### CSS Code

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

#### CSS Code

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

#### CSS Code

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

# 2.1 >

## You're Invited!

#### HTML Code

```html
<form>
  <h1>RSVP</h1>
  <h2>Big Birthday Bash - 4 May @ 6pm</h2>

    <label for="name">Full name </label>
  <input type="text" id="name" name="name">
</form>
```
## Respond, Please

#### HTML Code

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

#### HTML Code

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
Last Updated: 11:78AM 24/05/2022
