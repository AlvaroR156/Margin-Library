Margin-Library
==============
This project will allow you to add simple and clean class to your development process. 
Avoid adding dirty and nasty code using Margin Library.

Composition
==============
The classes are composed in the below way:

| Element | Value          | Decription          |
| ------------- | ----------- | ----------- |
| Prefix      | ~~None~~ , ~~xs - sm - md - lg ~~ | If you use a prefix it will be applied only to that screen size. |
| Body     | m   | Stands for Margin |
| Side     | t - r - b - l | Stands for the side that you want to apply the margin, top, right, bottom, left |
| Amount   | 0 - 5 - 20 -50 | This are default values, you can customize them in the less file |

NOTE: The screen size is based in the default values of Bootstrap 3.

Examples
==============

mt5 { it will add a margin-top: 5px }

xsmr20 { it will add a margin-right: 20px only for xs screen size.}


How To Use
==============
1. Include the library.
2. Add the class to your elements.


TO DO
=====
- [x] Vars and Mix in Less
- [x] Responsive Tags
- [ ] Add negative values
- [ ] any feedback?
