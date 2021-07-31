# myCustomToast
Custom Toast Library

> Step 1. Add the JitPack repository to your build file 

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  > Step 2. Add the dependency
  
  dependencies {
	        implementation 'com.github.callmearnab:myCustomToast:1.0.0'
	}
  
   > Step 3. Call from your class
   
   myCustomToast.showToast(this, "your Message here");
  
