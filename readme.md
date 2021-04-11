#### Paulo Dichone's [*The Comprehensive 2021 Android Development Masterclass*](https://www.udemy.com/course/android-development-java-android-studio-masterclass/) course section16(atw<sup>1</sup>): Android Layouts, Constraints & Data Binding Introduction

### vertically centered layouts about me app with a scrollview


### concepts introduced:
* class hierarchy
* extracting styles, fonts, dimensions, paddings etc. as reference values,
* data binding object - *findViewById()* is resource heavy alternative we can utilize DataBindingUtil to  associate an activity with a view allowing us to more readily access widget/component. to do this

    1. add following snippet to android section of *build.gradle(Module: {app_name}.app}*
    	```
    		buildFeatures{
    			dataBinding true
    		}
    	```
    
    1. for a given activity's onCreate function add:
    
    	`binding = DataBindingUtil.setContentView(this, R.layout.activity_main);`

* data binding - in addition one can also bind actual data to the 'binding' allowing you to efficiently access data input from users, from project files, or from within android device

<sup>1</sup>at time of writing