# Android JetPack Compose Components

VERY IMPORTANT!

https://www.youtube.com/c/Gibr%C3%A1nGarc%C3%ADa/videos

Carousel Card en Android Jetpack Compose. Cards Slider. Coil. Horizontal Pager. GraphicsLayer: https://www.youtube.com/watch?v=XyEOxwkObJc

Tabs en Android Jetpack Compose: https://www.youtube.com/watch?v=V1NricS6cbo

## 1. Your first User Interface (UI) with Android Jetpack Compose. How to use: Text, Images, Rows and Columns

For step by step tutorial see this youtube video: https://www.youtube.com/watch?v=hfVv4tTOZlI

```kotlin
@Composable
fun Elements(){

Column(
	modifier = Modifier.fillMaxSize(),
	horizontalAligment = Aligment.CenterHorizontally,
	verticalArrangment = Arrangment.Center
      ){
         Image(painter = painterResource(id = R.drawable.picture_256),
            contentDescription = "my first picture")
         Text("My first Text"
	    color = Color.Blue,
	    fontSize = 48.sp	
	 )
	 Text("My second Text")
	 Row(){
             OutlineButton(onClick = { }) {
		Text("My dog")
             }
             Spacer(modifier = Modifier.width(10.dp))
             OutlineButton(onClick = { }) {
		Text("My content")
             }
	}
      }
}
```

![image](https://github.com/luiscoco/Android_Kotlin_lesson6_SomeCompoents/assets/32194879/52809ac2-282b-44d8-8542-1c15cf188d92)

## 2. How to create a SplashScreen using Material 3 and Android Jetpack Compose

For step by step tutorial see this youtube video: https://www.youtube.com/watch?v=vHfdoUqimk4

This is the project folders and files structure

![image](https://github.com/luiscoco/Android_Kotlin_lesson6_SomeCompoents/assets/32194879/366c6208-06ed-49fd-a91d-f14e1891a6b8)

```kotlin

```

![image](https://github.com/luiscoco/Android_Kotlin_lesson6_SomeCompoents/assets/32194879/3ff79df9-a297-4e9d-ae34-91886b973319)


## 3. 



## 4. 


