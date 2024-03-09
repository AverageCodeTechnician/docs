---
Title: Dart map.value() method
Description: A brief description of what this method is good for
Subjects: 
  - 'Web design'
  - 'Web development'
Tags: 
  -  'Properties'
  -  'search'
  - 'Values'
---
## Definition of map.values()
  The **values** of a **map** class are iterated when being called by the property **.values()**. value is found within the map class. When called, matching values are returned in the form of a list. The length of the matching values may or may not be as long as the amount of key/value pairs in the searched map. The values of the data being iterated are compared in  ==  ; therefore it's not strict-equals comparison.


## Syntax
```
variable <V> get values;
//Where V stands for the map class used to get is values using the .values() property
```

###### 

## Code example
```
 var vegetables = {'carrot': 1, 'potato': 2, 'rhubarb': 3}; print (vegetables.values); //(1,2,3)
```
## No codebyte examples currently available

## Sources: 

https://api.dart.dev/stable/1.10.1/dart-core/Map/values.html

https://api.dart.dev/stable/3.3.0/dart-core/Map/values.html

https://dart.dev/language/collections

https://www.darttutorial.org/dart-tutorial/dart-map/

https://github.com/Codecademy/docs/blob/main/content/dart/concepts/data-types/data-types.md?plain=1