#Coercion
1: Converting a value from one type to another is often called "type casting," when done explicitly, and "coercion" when done implicitly(forced by the rules of how a value is used).
"explicit coercion" is when it is obvious from looking at the code that a type conversion is intentionally occurring, whereas "implicit coercion" is when the type conversion will occur as a less obvious side effect of some other intentional operation.
var b = a + "";         // implicit coercion
var c = String( a );    // explicit coercion

#Comments
Comments shld not say what only why or how.

#Truthy and Falsy values
All of JavaScript's values can be divided into two categories:
 - [first]  values that will become false if coerced to boolean
 - [sednon] everything else (which will obviously become true)

We get the following as the so-called "falsy" values list:

undefined
null
false
+0, -0, and NaN
""
That's it. If a value is on that list, it's a "falsy" value, and it will coerce to false if you force a boolean coercion on it.

By logical conclusion, if a value is not on that list, it must be on another list, which we call the "truthy" values list. But JS doesn't really define a "truthy" list per se

Functions stored in objects are called methods
box["size"] = {
    "height" : 10,
    "width" : 3
    
}
box.area = function() {
  return box.size.height * box.size.width
}
