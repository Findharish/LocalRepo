CSS(CASCADING STYLE SHEET)
to give style to webpage we use css
in frontend we use css

inline css it written inside in tags using style attribute
problem write in every tag to overcome we use internal css

internal css written inside in head tag using style tag
advantage write in style tag and it uses for all tags in html file
problem we use it only inside the html file not outside to overcome we use external css

external css written outside the using extension .css source file
once write use any html page to use one tag is used that is link tag

css specificity if all css is given

first priority is inline css
internal and external css are use according to top to bottom approach if internal written first in head tag it run first else external css run and vice versa

selectors:
these are used to select the elements.
we are selectors like

-->tagname selectors
-->class selectors
-->id selectors
-->attribute selectors
-->group selectors
-->universal selectors
-->pseudo-class selectors
-->pseudo-element selectors

class selectors
by using class selectors we can select a group of elements
class selector is represented with (.) operator
syntax-
.classname{
property:value;
}

id selectors
by using id selectors we can apply unique style for html elements
id selectors is represented by using (#) operator
syntax-
#idname{
property:value;
}

css specificity -
if we apply css style for same element with multiple selectors the styles will be applicable based on priority of the selectors.

tagname-1
classname-10
idname-100
inlinecss-1000

attribute selector
applying the style with help of attribute we can call it as attribute selector
attribute selector is represented with ([])

universal selector
BY using universal selector we can apply common style for every html element.
universal selector is represented with (_) symbol
_{
margin:0px;
}

group selector
the combination of more than one selector is known as group selector
group selector is denoted by (,) operator
h1,h2,h3{
property:value;
}

psuedo-class selector
it is used to apply css style for entire html element
it is represented with (:) operator
selector:pseudo-class{
property:value;
}
ex- h1:hover{
color:green;
}

pseudo-element selector
it is used to apply css style for specific part of the html element(some part of html element)
it is represented with (::) operator
selector::pseudo-element{
property:value;
}
ex- h1::first-letter{
color:orange;
}

combinators
it is also a type of selectors
combinators are used whenever there is a parent and child relationship
there are four types of combinators such as

child selector
decendent selector
adjcent selector
general sibling selector

child selector(first generation child)
by using it we can apply the style only for child but not for inherit child
child selector is represented with (>) operator
syntax:
parent element > child element{

<!-- style will be applicable for child only -->

property:value;
}

decendent selector
by using it we can apply the style for direct child as well as indirect childs
child selector is represented with ( ) space.
syntax:
parent child{
property:value;
}

adjcent selector
by using it we can apply the style only for
adjcent selector is represented with (+) operator
syntax:
xus

- {
  property:value;
  }

block level element
which element 100% width of the webpage we can call it as block level element
height, widht,text-align applicable for block level element(but not for inline element)
ex:-header,nav,div etc

inline element
the element which occupies content level space those element we can call it as inline element
ex:- img, a, label, span,input etc

grid

---

it is used to create two dimensional layout which means we can arrange the items in row wise as well as column wise.
parent element called as container
child element called as items

container properties

---

grid-template-columns: this property will decide no of column should be created or width of each column.
grid-template-columns:repeat(4,auto);

grid-template-rows: this property will decide height of each row
grid-template-rows:100px auto 100px;

percentage(%) : always takes the values from parent element
pixcel(px) : always takes the values from screensize

@media-query

in css media-queries is used to add responsive design to the webpage.

syntax:
@media screen and (min-width: 300px) and (max-width: 500px) {
_ {
background-color: lightgreen;
}
}
@media all and (min-width: 500px) and (max-width: 1100px) {
_ {
background-color: lightpink;
}
}

media-type :
screen, all, print
