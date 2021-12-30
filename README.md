# Learning Jetpack Compose
### Tutorial from: https://developer.android.com/jetpack/compose/tutorial  
---
## Lesson 1: Composable functions  
- `@Composable` annotation
- Define app’s UI programmatically
- Composable functions can only be called from other composable functions

## Lesson 2: Layouts
- UI elements are organized in a hierarchy
- Can have nested elements
- `Column` - arranges elements vertically
- `modifiers` - used to configure/decorate composable

## Lesson 3: Material Design
- With `Compose`, Material Design and its UI elements are provided out of the box.
- 3 Pillars of Material Design: Color, Typography, Shape
- `Theme.kt` - File where themes (i.e light, dark) are defined  

## Lesson 4: Lists and animations  
- `LazyRow`, `LazyColumn` - composables that only render visible elements on screen, very efficient for long lists, avoids the complexity of `RecyclerViews` in XML layouts
- `remember` - stores local state in memory
- `mutableStateOf` - a single value holder whose reads and writes are observed by Compose
- [`Recomposition`](https://developer.android.com/jetpack/compose/mental-model#recomposition) - Allows Composables to be redrawn automatically when observing state that changes

## App Demo  
<img src="media/app-demo.gif" alt="Compose App Demo" height="500"></img>
