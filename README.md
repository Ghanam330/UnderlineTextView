# UnderlineTextView  [![](https://jitpack.io/v/Ghanam330/UnderlineTextView.svg)](https://jitpack.io/#Ghanam330/UnderlineTextView)
This lib to put line under your text view in your android xml file only

Gradle is the only supported build configuration, so just add the dependency to your project build.gradle file:

    dependencies {
	      implementation 'com.github.Ghanam330:UnderlineTextView:1.0.0'
           }
   

then
Add support JitPack repository in root build.gradle at the end of repositories:


     allprojects {
          repositories {
 
	        maven { url 'https://jitpack.io' }
         }
     }   


  # Implemntation in your XML File
  All you will do
  
    <com.codestomp.textviewunderline.UnderlineTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        android:textSize="30sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

  
