# LoggerLibrary
This is logger Library

For getting the logger library


Step 1. Add the JitPack repository to your build file 

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
Step 2. Add the dependency in app folder build file

dependencies {
	        implementation 'com.github.vishalwedowebappps:LoggerLibrary:0.1.2'
	}
