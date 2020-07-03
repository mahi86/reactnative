## What I learned. 

1. Expo , A framework for universal React app .  It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly on Web and Native. Uses compiler called metro. 

2. Run this by npm run start. 

3. createStackNavigator for navigating between screens. 

4. We could say whats the initial page on loading the app (initialRouteName). Its all again components in react native world too. 

5. Styles are given using  StyleSheet.create . This does validation by default. So , any error straight to the face of user. vs inline style , no impact if there is an error. 

6. FlatList , this is preferred for iterator vs the map function in web react native due to perf reasons. ALso it has lot of other attributes like vertical / horizontal , scroll overflow etc. keyExtractor is used to find key and put to element by default. 

7. Button - Two kinds. Button (SImple and also used to detact a press) and TouchableOpacity (Highly Customizable). TouchableOpacity is not a self closing tag.  and can put anything in it , like a Text or component / ... what so ever that is :)

8. To navigate , we have navigator.navigate option and give the route name specified in the object of stacknavigator. 
