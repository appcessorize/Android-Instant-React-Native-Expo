This is an example of an Android Instant app built in React Native Expo

I followed [this guide](https://medium.com/@punitkapoor050795/instant-app-for-react-native-96085edd2c9e) from Punit Kapoor

n.b: there is a small typo

this command 

    react-native bundle — platform android — dev false — entry-file index.js — bundle-output android/app/src/main/assets/index.android.bundle — assets-dest android/app/src/main/res

should be

    react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res
    

