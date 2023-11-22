# Python
## Syntax
### Functions syntax
* Def _function_(argument):
* Def + function + (argument) + colon
* Argument can be left empty; Def_function_():
* Argument is the input variable

### Data Types
* Integer is whole number; like ***0, 1, 10, 69***
* Float is number with decimals; like ***12.39, 3.141***. But numbers like ***1.00, 5.0 & 1.*** count as floats
* Boolean is a simple ***True/False***
  - True equals 1, & False equals 0
  - Use **not** to reverse Boolean
  - If Boolean **solid_gold** = True = 1, then **not solid_gold** = False = 0.
  - Vice versa for the reverse
* String is data that is ***Alphabet/Character/Text/Numbers in text format***
  + Numbers can be converted to text by putting " " around it
  + Numbers in text format can be converted to floats by using **float(number)**
  + 

### Condtions & Conditional Statements
Meaning | Symbol |
--- | --- |
equals | == | 
does not equal | != | 
less than | <  | 
less than or equal | <= | 
greater than | >  | 
greater than or equal | >= | 

#### Syntax
* def cost_of_project(engraving, solid_gold):
  * if solid_gold == True:
    * cost = 100 + (len(engraving) * 10)
  * else:
    * cost = 50 + (len(engraving) * 7)

### Lists
* Can be used to store strings, numbers & other data types in an organized format
#### Syntax
* flower_list = [ , , ,]
* flower_list[0]
#### Notes
* Count the length of the list with len()
* Refer & retrieve any item in the list with **Indexing**
* Python uses zero-based indexing, meaning first item is always 0, followed by 1 and so forth
* If List_1 has a length of 8, the first item will be 0, fourth item will be 3, last item will be 7
