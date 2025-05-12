# cs546-lab-4-mongodb-solved
**TO GET THIS SOLUTION VISIT:** [CS546 Lab 4-MongoDB Solved](https://www.ankitcodinghub.com/product/cs546-lab-4-mongodb-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91602&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS546 Lab 4-MongoDB Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
CS-546 Lab 4 MongoDB

For this lab, we are going to make a few parts of a restaurant database. You will create the first of these data modules, the module to handle a listing of resturants.

You will:

Separate concerns into different modules.

Store the database connection in one module.

Define and store the database collections in another module.

Define your Data manipulation functions in another module.

Continue practicing the usage of async / await for asynchronous code Continuing our exercises of linking these modules together as needed

Packages you will use:

You will use the mongodb (https://mongodb.github.io/node-mongodb-native/) package to hook into MongoDB

You may use the lecture 4 code (https://github.com/stevens-cs546-cs554/CS- 546/tree/master/lecture_04/code) as a guide.

You must save all dependencies you use to your package.json file

How to handle bad data

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>async function divideAsync(numerator, denominator) {
    if (typeof numerator !== "number") throw new Error("Numerator needs to be a number");
    if (typeof denominator !== "number") throw new Error("Denominator needs to be a number");
</pre>
<pre>    if (denominator === 0) throw new Error("Cannot divide by 0!");
</pre>
<pre>    return numerator / denominator;
}
</pre>
<pre>async function main() {
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ttps://sit.instructure.com/courses/50148/assignments/273384 1/9

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Lab 4

</div>
</div>
<div class="layoutArea">
<div class="column">
h

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>    const six = await divideAsync(12, 2);
    console.log(six);
</pre>
<pre>    try {
        const getAnError = await divideAsync("foo", 2);
</pre>
<pre>    } catch(e) {
        console.log("Got an error!");
</pre>
<pre>        console.log(e);
    }
</pre>
} main();

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Would log:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>6
"Numerator needs to be a number"
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Folder Structure

You will use the following folder structure for the data module and other project files. You can use mongoConnection.js, mongoCollections.js and settings.json from the lecture code, however, you will need to modify settings.json and mongoCollections.js to meet this assignment’s requirements.

Database Structure

You will use a database with the following structure:

The database will be called FirstName_LastName_lab4

The collection you use will be called restaurants restaurants

The schema for a restaurant is as followed:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>{
    _id: ObjectId,
</pre>
<pre>    name: string,
    location: string,
    phoneNumber: string (xxx-xxx-xxxx format),
    website: string (must contain full url http://www.patrickseats.com),
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ttps://sit.instructure.com/courses/50148/assignments/273384 2/9

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
h

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273384

</div>
<div class="column">
3/9

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>    priceRange: string (from $ to $$$$),
    cuisines: [strings],
    overallRating: number (from 0 to 5),
    serviceOptions: {dineIn: Boolean, takeOut: Boolean, delivery: Boolean}
</pre>
}

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
The _id field will be automatically generated by MongoDB when a restaurant is inserted, so you do not need to provide it when a restaurant is created.

An example of how The Saffron Lounge would be stored in the DB:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>{
    _id: ObjectId("507f1f77bcf86cd799439011"),
    name: "The Saffron Lounge",
    location: "New York City, New York",
    phoneNumber: "123-456-7890",
    website: "http://www.saffronlounge.com",
    priceRange: "$$$$",
    cuisines: ["Cuban", "Italian" ],
    overallRating: 3
    serviceOptions: {dineIn: true, takeOut: true, delivery: false}
</pre>
}

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
restaurants.js

In restaurant.js, you will create and export five methods:

Remember, you must export methods named precisely as specified. The async keyword denotes that this is an async method.

async create(name, location, phoneNumber, website, priceRange, cuisines, overallRating, serviceOptions);

This async function will return to the newly created restaurant object, with all of the properties listed above.

If name, location, phoneNumber, website, priceRange, cuisines, overallRating, serviceOptions are not provided at all, the method should throw. (All fields need to have valid values);

If name, location, phoneNumber, website, priceRange are not strings or are empty strings, the method should throw.

If phoneNumber does not follow this format: xxx-xxx-xxxx, the method will throw.

If does not contain http://www. and end in a .com , and have at least 5 characters in-between

the and .com this method will throw.

If priceRange is not between ‘ $ ‘ to ‘ $$$$ ‘, this method will throw.

If cuisines is not an array and if it does not have at least one element in it that is a valid string , or are empty strings the method should throw.

</div>
</div>
<div class="layoutArea">
<div class="column">
website

</div>
</div>
<div class="layoutArea">
<div class="column">
http://www.

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
If is not an , the method should throw.

</div>
</div>
<div class="layoutArea">
<div class="column">
If serviceOptions.dineIn, serviceOptions.takeOut, serviceOptions.delivery is not a boolean, the method should throw.

Note: FOR ALL INPUTS: Strings with empty spaces are NOT valid strings. So no cases of ” ” are valid.

For example:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>serviceOptions
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
object

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>const restaurants = require("./restaurants");
</pre>
<pre>async function main() {
    const safrronLounge = await restaurants.create("The Saffron Lounge", "New York City, New York",
</pre>
<pre> "123-456-7890", "http://www.saffronlounge.com", "$$$$", ["Cuban", "Italian"], 3, {dineIn: true, tak
eOut: true, delivery: false});
</pre>
<pre>    console.log(safrronLounge);
}
</pre>
main();

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Would return and log:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>{
    _id: "507f1f77bcf86cd799439011",
    name: "The Saffron Lounge",
    location: "New York City, New York",
    phoneNumber: "123-456-7890",
    website: "http://www.saffronlounge.com",
    priceRange: "$$$$",
    cuisines: ["Cuban", "Italian" ],
    overallRating: 3
    serviceOptions: {dineIn: true, takeOut: true, delivery: false}
</pre>
}

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
This restaurant will be stored in the restaurants collection.

If the restaurant cannot be created, the method should throw.

Notice the output does not have ObjectId() around the ID field and no quotes around the key names, you need to display it as such.

async getAll();

This function will return an array of all restaurants in the collection. If there are no restaurants in your DB, this function will return an empty array

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>const restaurants = require("./restaurants");
</pre>
<pre>async function main() {
    const allResturants = await restaurants.getAll();
</pre>
<pre>    console.log(allResturants);
}
</pre>
main();

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273384

</div>
<div class="column">
4/9

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Would return and log all the restaurants in the database.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>[{
    _id: "507f1f77bcf86cd799439011",
    name: "The Saffron Lounge",
    location: "New York City, New York",
    phoneNumber: "123-456-7890",
    website: "http://www.saffronlounge.com",
    priceRange: "$$$$",
    cuisines: ["Cuban", "Italian" ],
    overallRating: 3
    serviceOptions: {dineIn: true, takeOut: true, delivery: false}
</pre>
}, {

}, {

} ]

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>_id: "306f1f77bcf86cd799431423",
name: "Black Bear",
location: "Hoboken, New Jersey",
phoneNumber: "456-789-0123",
website: "http://www.blackbear.com",
priceRange: "$$",
</pre>
<pre>cuisines: ["Cuban", "American" ],
overallRating: 4
serviceOptions: {dineIn: true, takeOut: true, delivery: true}
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>_id: "204adw77bcf86cd799439011",
name: "Pizza Lounge",
location: "New York City, New York",
phoneNumber: "999-999-9999",
website: "http://www.pizzalounge.com",
priceRange: "$",
</pre>
<pre>cuisines: ["Italian" ],
overallRating: 5
serviceOptions: {dineIn: false, takeOut: true, delivery: true}
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Notice the output does not have ObjectId() around the ID field and no quotes around the key names, you need to display it as such.

async get(id);

When given an id, this function will return a restaurant from the database.

If no id is provided, the method should throw.

If the id provided is not a string , or is an empty string, the method should throw. If the id provided is not a valid ObjectId , the method should throw

If the no restaurant exists with that id , the method should throw.

For example, you would use this method as:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>const restaurants = require("./restaurants");
</pre>
<pre>async function main() {
    const pizzaLounge = await restaurants.get("204adw77bcf86cd799439011");
</pre>
<pre> console.log(pizzaLounge);
}
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ttps://sit.instructure.com/courses/50148/assignments/273384 5/9

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
h

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
main();

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Would return and log Pizza Lounge:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>{
    _id: "204adw77bcf86cd799439011",
    name: "Pizza Lounge",
    location: "New York City, New York",
    phoneNumber: "999-999-9999",
    website: "http://www.pizzalounge.com",
    priceRange: "$",
    cuisines: ["Italian" ],
    overallRating: 5
    serviceOptions: {dineIn: false, takeOut: true, delivery: true}
</pre>
}

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Notice the output does not have ObjectId() around the ID field and no quotes around the key names, you need to display it as such.

Important note: The ID field that MongoDB generates is an ObjectId . This function takes in a string representation of an ID as the id parameter. You will need to convert it to an ObjectId in your function before you query the DB for the provided ID and then pass that converted value to your query.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>//We need to require ObjectId from mongo
let { ObjectId } = require('mongodb');
</pre>
<pre>/*For demo purposes, I will create a new object ID and convert it to a string,
Then will pass that valid object ID string value into my function to check if it's a valid Object ID
(which it is in this case)
I also pass in an invalid object ID when I call my function to show the error */
</pre>
<pre>let newObjId = ObjectId(); //creates a new object ID
let x = newObjId.toString(); // converts the Object ID to string
console.log(typeof x); //just logging x to see it's now type string
//The below function takes in a string value and then attempts to convert it to an ObjectId
function myDBfunction(id) {
</pre>
<pre>  //check to make sure we have input at all
  if (!id) throw 'Id parameter must be supplied';
</pre>
<pre>  //check to make sure it's a string
  if (typeof id !== 'string') throw "Id must be a string";
</pre>
<pre>  //Now we check if it's a valid ObjectId so we attempt to convert a value to a valid object ID,
</pre>
<pre>  //if it fails, it will throw an error (you do not have to throw the error, it does it automaticall
y and the catch where you call the function will catch the error just as it catches your other error
s).
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ttps://sit.instructure.com/courses/50148/assignments/273384 6/9

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
h

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273384

</div>
<div class="column">
7/9

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>  let parsedId = ObjectId(id);
  //this console.log will not get executed if Object(id) fails, as it will throw an error
  console.log('Parsed it correctly, now I can pass parsedId into my query.');
</pre>
}

<pre>//passing a valid string that can convert to an Object ID
try {
</pre>
<pre>  myDBfunction(x);
} catch (e) {
</pre>
<pre>  console.log(e.message);
}
</pre>
<pre>//passing an invalid string that can't be converted into an object ID:
try {
</pre>
<pre>  myDBfunction('test');
} catch (e) {
</pre>
<pre>  console.log(e.message);
}
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
async remove(id)

This function will remove the restaurant from the database.

If no id is provided, the method should throw.

If the id provided is not a string , or is an empty string the method should throw.

If the id provided is not a valid ObjectId , the method should throw

If the restaurant cannot be removed (does not exist), the method should throw.

If the removal succeeds, return the name of the restaurant and the text ” has been successfully deleted!”

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>const resturants = require("./resturants");
</pre>
<pre>async function main() {
    const removeBlackBear = await resturants.remove("306f1f77bcf86cd799431423");
</pre>
<pre> console.log(removeBlackBear);
}
</pre>
main();

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Would return and then log: “Black Bear has been successfully deleted!”.

Important note: The ID field that MongoDB generates is an ObjectId . This function takes in a string representation of an ID as the id parameter. You will need to convert it to an ObjectId in your function before you query the DB for the provided ID. See example above in getId() .

async rename(id, newWebsite)

This function will update the website of the restaurant currently in the database.

If no id is provided, the method should throw.

If the id provided is not a string , or is an empty string the method should throw.

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
If the id provided is not a valid , the method should throw. If newWebsite is not provided, the method should throw.

If newWebsite is not a string , is an empty string, or does not contain http://www. and end in a .com , and have at least 5 characters in-between the http://www. and .com , the method should throw.

If the restaurant cannot be updated (does not exist), the method should throw.

if the newWebsite is the same as the current value stored in the database, the method should throw. If the update succeeds, return the entire restaurant object as it is after it is updated.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
ObjectId

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>const resturants = require("./resturants");
</pre>
<pre>async function main() {
    const renamedSaffronLounge = await resturants.rename("507f1f77bcf86cd799439011", "http://www.the
</pre>
<pre>saffronlounge.com");
</pre>
<pre> console.log(renamedSaffronLounge);
}
</pre>
main();

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Would log the updated restaurant:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>{
    _id: "507f1f77bcf86cd799439011",
    name: "The Saffron Lounge",
    location: "New York City, New York",
    phoneNumber: "123-456-7890",
    website: "http://www.thesaffronlounge.com",
    priceRange: "$$$$",
    cuisines: ["Cuban", "Italian" ],
    overallRating: 3
    serviceOptions: {dineIn: true, takeOut: true, delivery: false}
</pre>
}

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Notice the output does not have ObjectId() around the ID field and no quotes around the key names, you need to display it as such.

Important note: The ID field that MongoDB generates is an ObjectId . This function takes in a string representation of an ID as the id parameter. You will need to convert it to an ObjectId in your function before you query the DB for the provided ID. See example above in getId() .

index.js

For your index.js file, you will:

1. Create a restaurant of your choice.

2. Log the newly created restaurant. (Just that restaurant, not all restaurants) 3. Create another restaurant of your choice.

4. Query all restaurants, and log them all

5. Create the 3rd restaurant of your choice.

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273384

</div>
<div class="column">
8/9

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:46 PM Lab 4

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
async

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
index.js

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>LastName_FirstName_CS546_SECTION.zip (ie.
</pre>
</div>
</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Hill_Patrick_CS546_WS.zip)
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273384 9/9

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
6. Log the newly created 3rd restaurant. (Just that restaurant, not all restaurants) 7. Rename the first restaurant website

8. Log the first restaurant with the updated website.

9. Remove the second restaurant you created.

10. Query all restaurants, and log them all

11. Try to create a restaurant with bad input parameters to make sure it throws errors.

12. Try to remove a restaurant that does not exist to make sure it throws errors.

13. Try to rename a restaurant that does not exist to make sure it throws errors.

14. Try to rename a restaurant passing in invalid data for the parameter to make sure it throws errors. 15. Try getting a restaurant by ID that does not exist to make sure it throws errors.

</div>
</div>
</div>
</div>
