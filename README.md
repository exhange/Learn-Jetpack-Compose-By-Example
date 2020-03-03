# Jetpack Compose Playground

Over the course of the last few years Android development has gone
through significant changes in how we structure our apps, the language
we use for development, the tooling & libraries that help us speed up
our development and the improvements in testing our apps. What had not
changed in all these years is the Android UI toolkit. This changes with
Jetpack Compose that aims to re-imagine what Android UI development
would look like using declarative programming principles. It is heavily
influenced by existing web and mobile frameworks such as React, Litho,
Vue & Flutter and would be a paradigm shift in Android UI development as
we know it.

This repository aims to show the Jetpack Compose way of building common
Android UI that we are accustomed to building.

Examples
-----------------

Each example is meant to be self contained and tries to explain all the
concepts that its using with comments. Compose also comes with this
nifty feature that lets you preview each component in the IntelliJ IDE
itself. To do so, go to any of the examples examples and the click on
the preview button in the top right corner. This is possible if your
`@Composable` component has a corresponding `@Preview` method associated
with it. Look at the examples below for all this to make a bit more
sense.

![Jetpack Compose Preview Functionality](screenshots/compose_preview.gif)

### General

|Example|Preview|
|-------|-------|
|[How do I display "Hello World" on the screen using Jetpack Compose?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/SimpleTextActivity.kt)| |
|[How do I make a view clickable and do actions when clicked?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/dialogs/AlertDialogActivity.kt#L36)| |
|[How do I get FrameLayout like functionality to stack views on top of one another?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/stack/StackActivity.kt)| |
|[How do I add padding around a view?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/button/ButtonActivity.kt#L37)| |
|[How do I add a background color to any section of the screen?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/CustomTextActivity.kt#L163)| |


### Text

|Example|Preview|
|-------|-------|
|[How do I style & customize my text?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/CustomTextActivity.kt)| |
|[How do you take text input from a user in Jetpack Compose?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/TextFieldActivity.kt)
|[How can I use a custom text style for a text input?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/TextFieldActivity.kt#L71)| |
|[How can I change the keyboard type to accept numbers?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/TextFieldActivity.kt#L90)| |
|[How can I create a Search bar?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/TextFieldActivity.kt#L104)| |
|[How can I apply a visual transformation to an input text?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/text/TextFieldActivity.kt#L123)| |


### Images

|Example|Preview|
|-------|-------|
|[How do I display an image in Jetpack Compose?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/image/ImageActivity.kt)| |
|[How to load an image from the resource folder?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/image/ImageActivity.kt#L61)| |
|[How to make an image view with rounded corners?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/image/ImageActivity.kt#L73)| |
|[How to load an image over the network using Picasso?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/image/ImageActivity.kt#L85)| |
|[How to load an image over the network using Glide?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/image/ImageActivity.kt#L135)| |


### Lists

|Example|Preview|
|-------|-------|
|[How do I display a list in my app?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/scrollers/VerticalScrollableActivity.kt)| |
|[Is there a RecyclerView equivalent?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/scrollers/VerticalScrollableActivity.kt#L40)| |
|[How can I have a grid layout?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/scrollers/GridLayoutActivity.kt)| |
|[How can I build a horizontally scrollable carousel?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/scrollers/HorizontalScrollableActivity.kt)| |


### Material Design

|Example|Preview|
|-------|-------|
|[How do I add a Button to my screen?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/ButtonActivity.kt)||
|[How do I add a drawer to my screen?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/DrawerAppActivity.kt)| |
|[How do I display an alert dialog/popup modal?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/AlertDialogActivity.kt)| |
|[How do I add a Material Design Card?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L69) <br> [How do I display a linar progress bar?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L127) <br> [What about a circular progress bar?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L147) <br> [How do I add a Snackbar?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L161) <br> [How to add a Material Design Slider?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L173) <br> [How to configure a two/three state checkbox?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L85) <br> [How do I add a radio button group?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/MaterialActivity.kt#L116)| |
|[How do I add a Bottom App Bar? How do I add a Floating Action Button to my screen?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/material/BottomAppBarActivity.kt#L37) | |

### Flexible Layouts
|Example|Preview|
|-------|-------|
|[How do I align the baseline of two views?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L164)| |
|**What's the layout weight equivalent in Jetpack Compose?**<br>[Example with equal weights](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L59) <br>[Example with unequal weights](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L74)| |
|**How do I auto arrange my views similar to FlexBox?**<br>[Add space between views](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L89)<br>[Evenly distribute space](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L104)<br>[Add space around the views](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L119)<br>[Tightly packed centering of views](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ViewLayoutConfigurationsActivity.kt#L134)| |
|[How do I use constraint layouts?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ConstraintLayoutActivity.kt#L47)| |
|[How do I use guidelines with constraint layouts?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ConstraintLayoutActivity.kt#L88)| |
|[How do I add barriers when using constraint layouts?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ConstraintLayoutActivity.kt#L117)| |
|[How do I add bias when using constraint layouts?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/layout/ConstraintLayoutActivity.kt#L157)| |

### Custom Views

|Example|Preview|
|-------|-------|
|[How do I draw using a canvas?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/customview/CustomViewActivity.kt)| |
|[How do I detect touch events in a custom view?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/customview/CustomViewPainActivity.kt)| |


### State Management
|Example|Preview|
|-------|-------|
|[How do I store state information in Jetpack Compose?](https://github.com/vinaygaba/Jetpack-Compose-Playground/blob/master/app/src/main/java/com/example/jetpackcomposeplayground/state/StateActivity.kt)| |


Credits
-----------------
Author: Vinay Gaba (vinaygaba@gmail.com)

<a href="https://twitter.com/vinaygaba">
  <img alt="Follow me on Twitter"
       src="https://github.com/gabrielemariotti/cardslib/raw/master/demo/images/twitter64.png" />
</a>
<a href="https://www.linkedin.com/in/vinaygaba">
  <img alt="Follow me on LinkedIn"
       src="https://github.com/gabrielemariotti/cardslib/raw/master/demo/images/linkedin.png" />
</a>


License
-----------------

    Copyright 2020 Vinay Gaba

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.