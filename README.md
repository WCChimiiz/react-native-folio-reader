
# react-native-folio-reader by WCChimiiz


| **Android: [FolioReader/FolioReader-Android](https://github.com/FolioReader/FolioReader-Android)** |


| **iOS: [FolioReader/FolioReaderKit](https://github.com/FolioReader/FolioReaderKit)** |

## Getting started

`$ npm install wcchimiiz-react-native-folio-reader --save`

### Mostly automatic installation

`$ react-native link wcchimiiz-react-native-folio-reader`

### Manual installation

#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `wcchimiiz-react-native-folio-reader` and add `RNReactNativeFolioReader.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeFolioReader.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeFolioReaderPackage;` to the imports at the top of the file
  - Add `new RNReactNativeFolioReaderPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':wcchimiiz-react-native-folio-reader'
  	project(':wcchimiiz-react-native-folio-reader').projectDir = new File(rootProject.projectDir, 	'../node_modules/wcchimiiz-react-native-folio-reader/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':wcchimiiz-react-native-folio-reader')
  	```

## Usage
```javascript
import RNReactNativeFolioReader from 'wcchimiiz-react-native-folio-reader';

// TODO: What to do with the module?
RNReactNativeFolioReader;
```
  