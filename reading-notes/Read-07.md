# Class 201 Reading Notes: Read-05
 
## ***Duckett HTML Book***
 
### Chapter 6: “Tables” (pp.126-145)
 
- The table tag is used to create forms using html
- HTML tables are similiar to tables that you would create in a word document or excel file
- After the table tag is used, you would continue creating the table using rows which use the tr (table row) tags
- td (table data) and th (table heading) tags are used to insert information within a table or serve as a column heading. th and td tags also essentially act as the means to add a column. not all rows must have the same amount of td tags as not every row must have the same amount of columns, but an uneven amount of tags will column sizes
- rowspan and colspan can be used to make cells span more than one row or column

**example table format**

&lt;table&gt;

&lt;tr&gt;

&lt;th&gt; Apples &lt;/th&gt;

&lt;th&gt; Oranges &lt;/th&gt;

&lt;/tr&gt;

&lt;tr&gt;

&lt;th&gt; 10 &lt;/th&gt;

&lt;th&gt; 5 &lt;/th&gt;

&lt;/tr&gt;

&lt;/table&gt;

## ***Duckett JS Book***
 
### Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

- Functions are a goup of statements that perform a single task when called. Functions can be used multiple times

*declaring a function*
function add(a,b)
{
  total = a + b;
  return total;
}
This function will allow a user to pass two numbers (a and b) into a function and get the total of the two numbers added together.

*calling a function*
console.log(add(5,5));
This will return a total of 10 to the console.

- Objects are a series of variables and/or functions that represent a model or "real world object"
- For example, a car object would represent a model for "building" a car and would include things such as make, model, year, color, etc.

*Declaring an object*
const car = {
  make: 'Ford',
  model: 'fusion',
  year: 2017,
  color: 'blue'
  horn: function(){
    let soundTheHorn = 'Beep Beep'
    return soundTheHorn;
    }
}

*Calling an object*
console.log(car.make,car.model);
This will return the car object's make and model

