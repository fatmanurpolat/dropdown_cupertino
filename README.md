
<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

You can use this widget that can perform any enum selection on iOS and Android devices. Offers a simple aesthetic to your mobile app.




## Features

Select any enum with cupertino style

## Getting started

TODO: List prerequisites and provide or point to information on how to
start using the package.

## Usage

There is an example, you can check it
to `/example` folder. 


```
DropDownCupertino<Person>(
              initialText: "Select a Person :",
              pickList: personMap,
              enumValues: Person.values,
              height: 160,
              onSelectedItemChanged: ((selected) {
                debugPrint("Selected text is: $selected");
              }),
            )
```

  - initialText: Text to be seen before opening the menu.
  - pickList: Dropdown type.
  - enumValues: List of all enums.
  - height: Height of dropdown menu visible in app.
  - onSelectedItemChanged: Prints the selected item to the console.
  
  
```dart
const like = 'sample';
```

## Additional information

Working on more flexible for it.
# dropdown_cupertino
