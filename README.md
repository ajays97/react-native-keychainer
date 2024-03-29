# react-native-keychainer

## Getting started

`$ npm install react-native-keychainer --save`

or

`$ yarn install react-native-keychainer`

### Mostly automatic installation

`$ react-native link react-native-keychainer`

### Manual installation

#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-keychainer` and add `Keychainer.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libKeychainer.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`

- Add `import com.reactlibrary.KeychainerPackage;` to the imports at the top of the file
- Add `new KeychainerPackage()` to the list returned by the `getPackages()` method

2. Append the following lines to `android/settings.gradle`:
   ```
   include ':react-native-keychainer'
   project(':react-native-keychainer').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-keychainer/android')
   ```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
   ```
     compile project(':react-native-keychainer')
   ```

## Usage

```javascript
import RNKeychainer from 'react-native-keychainer';

// TODO: What to do with the module?
RNKeychainer;
```
