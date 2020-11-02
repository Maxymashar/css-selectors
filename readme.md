# CSS Selectors

## .classname

Selects all the elements with the class `classname`

## .classname-one.classname-two ...

Selects all the elements with all of the classes `classname-one`,`classname-two` ...

## .classname-one .classname-two

Selects all the elements with the classname `classname-two` and is a descendant of the element with the classname `classname-one`

## #id-name

Selects all the elements with the id `id-name`

## \*

Selects all the elements

## element

Selects all the elements of that type

## element.classname

Selects all the elements of type element that have the classname `classname`

## element-one,element-two

Selects all the elements of type `element-one` and `element-two`

## element-one element-two

Selects all the elements of type element-two that are children of elements of type element-one

## element-one > element-two

Selects all the elements of type element-two whose parents are elements of type element-one

## element-one + element-two

Selects all the element-two elements that are placed imediately after the element-one elements

## element-one ~ element-two

Selects all the element-two elements that are preceded by the element-one elements

## [attribute]

Selects all the elements with the attribute

## [attribute=value]

Selects all the elemets whose attributes=value

# Pseudo Classes

## element:first-child

Selects the element that is the fisrt child of its parents

## element:last-child

Selects the element that is the last child of its parents

## :not(selector)

Selects all that is not selected by the selector