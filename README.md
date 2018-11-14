# React Native Android Shared Preferences

Android Shared Preferences for React Native

## Install

```bash
npm install @connected-home/react-native-android-shared-preferences --save
# or...
yarn add @connected-home/react-native-android-shared-preferences
```

## Link

```bash
react-native link @connected-home/react-native-android-shared-preferences
```

## Usage

### Import

```javascript
const SharedPreferences = require("react-native-android-shared-preferences");
// or...
import SharedPreferences from "react-native-android-shared-preferences";
```

### Get item

```javascript
SharedPreferences.getItem("file", "key", value => {
  ...
});
```

### Get multiple items

```javascript
SharedPreferences.getItems("file", ["key1", "key2"], values => {
  ...
});
```

### Get keys

```javascript
SharedPreferences.keys("file", keys => {
  ...
});
```

### Get entries

```javascript
SharedPreferences.entries("file", entries => {
  console.log(values);
});
```

### Set Item

```javascript
SharedPreferences.setItem("file", "key", "value");
```

### Delete Item

```javascript
SharedPreferences.deleteItem("file", "key");
```

### Clear all items

```javascript
SharedPreferences.clear("file");
```

### Delete Prefs File

```javascript
SharedPreferences.deleteFile("file");
```
