# Akhil Sai Kumar Jami 
 My Name is Akhil. I'm 26 years old. I worked as Team lead in Tech mahindra, India. My native place is Vizag. It is located in the state of Andhra Pradesh.<br> I joined NWMSU in the fall intake. Looking forward for the bright career here. 


 ![My picture](/Akhil1.jpg?raw=true)

 # FoodAndDrinks
   The Below Table Give Information of drinks and food available in different places near me at the good price.<br> Please refer below table and select your choice.

   | Food/Drink | Place    | Price  |
   | ---------- | -------- | ------ |
   | Beer       | Walmart  | 5 $    |
   | Milk       | Hivee    | 1 $    |
   | Chicken    | Chfill   | 9 $    |
   | Cashew     | Boom     | 0.5 $  |

   ---

   # PithyQuotes

   > The purpose of our lives is to be happy.     *Dalai Lama*

   > Life is what happens when you're busy making other plans.  *John Lenno*

---

# Geometry Elementary/Polygons

> These algorithms have been used in practice for several decades, and are robust, easy to understand, code, and maintain. And they execute very rapidly in practice, not just in theory. For example, the winding number point in polygon inclusion test, first developed by the author in 2000, is the fastest inclusion algorithm known, and works correctly even for nonsimple polygons. There is also a fast implementation of the Melkman algorithm for the convex hull of a simple polyline. And much more.
[Source](https://geomalgorithms.com/)

```
ftype norm(point2d a) {
    return dot(a, a);
}
double abs(point2d a) {
    return sqrt(norm(a));
}
double proj(point2d a, point2d b) {
    return dot(a, b) / abs(b);
}
double angle(point2d a, point2d b) {
    return acos(dot(a, b) / abs(a) / abs(b));
}
```
[Source](https://cp-algorithms.com/geometry/basic-geometry.html)