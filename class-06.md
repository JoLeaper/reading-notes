# Reading 06 Important Terms JS

## HTML
| Term   | Definition  |
|---|---|
| **object**  |  A term used to describe the grouping together of variables and functions you would see in the real world. Example:  |
```javascript
let hotel = {
    name: 'Quay',
    rooms: 40,
    booked: 25,
    checkAvailabality: function () {
        return this.rooms - this.booked;
    }
}
```
|  |  |
|---|---|
| **property**  |  A property is a variable that is inside of a function. Name, rooms, and booked, are all properties of the object 'hotel.'  |
```javascript
let hotel = {
    name: 'Quay', 
    rooms: 40, 
    booked: 25, 
    checkAvailabality: function () {
        return this.rooms - this.booked;
    }
}
```
|  |  |
|---|---|
| **method**  |  A function that is inside of an object is what is called a 'method.'  |
```javascript
let hotel = {
    name: 'Quay', 
    rooms: 40, 
    booked: 25, 
    checkAvailabality: function () {
        return this.rooms - this.booked;
    }
}
```
|  |  |
|---|---|
| **key**  |  In objects, both properties and methods have what are called 'keys' and 'values.' A key is the name of the property or method (name, rooms, booked, checkedAvailability) and the value is what that key holds. The key name holds the string Quay, rooms holds the number 40, booked holds the number 25, and checkedAvailability holds the function.  |
```javascript
let hotel = {
    name: 'Quay', 
    rooms: 40, 
    booked: 25, 
    checkAvailabality: function () {
        return this.rooms - this.booked;
    }
}
```
|  |  |
|---|---|
| **dot/square notation**  |  To access the values within an object, there are two formats. They are listed below:   |
```javascript
let hotel = {
    name: 'Quay', 
    rooms: 40, 
    booked: 25, 
    checkAvailabality: function () {
        return this.rooms - this.booked;
    }
let hotelName = hotel.name // holds Quay, dot notation
let hotelRooms = hotel[rooms] // holds 40, square notation
}
```
Dot notation accesses the the key in the variable to get the value, while square notation looks inside the object for a key that matches the string inside the brackets.
|  |  |
|---|---|









