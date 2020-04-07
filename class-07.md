# Reading 07 Important Terms JS
## HTML
| Term   | Definition  |
|---|---|
| **creating an object with constructor notation**  |  To create an object using constructor notation, you first create an empty object using 'new' and 'Object().' Below is an example of creating an empty object and adding properties/methods to it.  |
```javascript
const hotel = new Object(); // to create an empty object with literal notion, use: const hotel = {};

hotel.name = 'Quay';
hotel.rooms = 40;
hotel.booked = 25;

hotel.checkAvailability = function () {
    return this.room - this.booked;
}

```
|  |  |
|---|---|
| **modifying/adding object properties**  |   |
```javascript
hotel.name = 'Marriot';
// OR
hotel['name'] = 'Marriot'; 

// In this case, either work to modify the value of name. Bracket format cannot be used to update methods. If hotel.name was not an identified property, it would be added to the object.

delete hotel.name; //gets rid of the entire key:value pair, to clear out a property, you use:
hotel.name = '';
```
|  |  |
|---|---|
| **creating multiple objects with constructor notation**  |   |
```javascript
// create a function that takes in relevant parameters. A constructor function is to be named with a capital letter.
function Hotel(name, rooms, booked) {
// using the keyword 'this' makes sure that properties being updated will belong to the object the function creates.
this.name = name;
this.rooms = rooms;
this.booked = booked;
this.checkAvailability = function() {
    return this.rooms - this.booked;
}
}

// store the object as a variable using the 'new' keyword.

const quayHotel = new Hotel('Quay', 40, 25);
const park = new Hotel('Park', 120, 77);
```
|  |  |
|---|---|
| **this (keyword)**  | When this is defined inside of an object, 'this' will refer to the object it is in. When declared gl |
```javascript
const shape = {
    width: 600,
    height: 400,
    getArea: function() {
        return this.width * this.height;
    }
}
// this.width refers to shape, so it would be 600. this.height refers to height, so it would be 400.
```
