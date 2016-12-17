# Material-Buttons
Styles for the Android Button.

![alt tag](https://raw.githubusercontent.com/fabriciorod/Material-Buttons/master/screenshot.png)

## How to use
Only use the style attribute with any of the next values.

* MaterialButton.Indigo
* MaterialButton.Teal
* MaterialButton.Red
* MaterialButton.Blue
* MaterialButton.Pink
* MaterialButton.Purple
* MaterialButton.DeepPurple
* MaterialButton.GreyBlue
* MaterialButton.Green
* MaterialButton.Brown
* MaterialButton.Cyan
* MaterialButton.DeepOrange

As you already know, the elevation attribute and ripple effect only works on SDK > 21, so, the buttons do not have this effects on pre-lollipop. 

## Installation

* Add jitpack to your root gradle build file:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
* Add the library to your dependencies:

```gradle
dependencies {
   compile 'com.github.fabriciorod:material-buttons:1.0'
}
```

```
Copyright 2016 Fabricio Rodriguez

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
