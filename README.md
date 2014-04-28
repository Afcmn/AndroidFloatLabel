# Floating Label Edit Text for Android

![Float label for Android](http://nerds.weddingpartyapp.com/images/posts/float-label-android-cropped.gif)

For more info, see [this blog post](http://nerds.weddingpartyapp.com/tech/2013/12/25/float-label-pattern-for-android/).

# Salient features

1. Simple and clean library (open up the source to see for yourself!)
2. Ability to stretch EditText width to full/half screen
3. Hides input for password fields too, but shows labels
4. Customizable attributes for textSize, hint color (focused/unfocused)
5. *Custom Espresso test matcher for your testing needs!*
6. Maven repo (coming soon...)


# Goals for this project

Having goals for a project, keep a quality check and help with learning. Since I intended this to be a community project, the goals are aligned, keeping that fact in mind. The goals for this project are as follows:

1. Code should be ridiculously readable. Must read as fluently as pseudocode.
2. Code must be tested
3. Git commits should be clean and legible. Try to [follow AngularJs commit types](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#type).
4. Super DRY code! You cannot have two sets of lines repeating within the same file.

# Gotchas

## 1. Overriding the onFocusChangeListener for the EditText

If you're setting an onFocusChange listener directly on the EditText, you might lose the color changes on the hint when chaning focus. Instead set the onFocusChangeListener *directly* on the FloatLabelView itself

# Contributors:

## Credit:

1. [Matt D.Smith for coming up with the concept](http://mattdsmith.com/float-label-pattern/)
2. [Wedding Party for being an amazing organization and encourgaing such indulgences](https://www.weddingpartyapp.com)

## Developers

1. [Kaushik Gopal](http://kaush.co)
2. [Reza](http://www.moallemi.ir) - Gravity support