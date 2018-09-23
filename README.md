Setup code push
1. code-push register : log into app center , "logout"
2. install react-native-code-push : npm install —save react-native-code-push
3. Link react native code push into app: react-native link react-native-code-push
4. Create sign key: https://facebook.github.io/react-native/docs/signed-apk-android
5. Build react native app: cd android && ./gradlew assembleRelease; cd ..
6. Troubleshoot: Failed to capture snapshot of input files for task ‘Remove node_module and run “npm install”
7. Code-push: code-push release-react codepushApp android
8. code-push Api: https://github.com/Microsoft/react-native-code-push/blob/master/docs/api-js.md#codepushsync
