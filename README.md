
# react-native-arena-map

## Getting started

`$ npm install react-native-arena-map --save`

### Mostly automatic installation

`$ react-native link react-native-arena-map`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-arena-map` and add `RNArenaMap.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNArenaMap.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.arena.map.RNArenaMapPackage;` to the imports at the top of the file
  - Add `new RNArenaMapPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-arena-map'
  	project(':react-native-arena-map').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-arena-map/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-arena-map')
  	```


## Usage
```javascript
import RNArenaMap from 'react-native-arena-map';

// TODO: What to do with the module?
RNArenaMap;
```
  