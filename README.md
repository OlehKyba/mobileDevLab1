# Mobile Development. Labwork #1
I don't have Apple products. And I don't have a high-performance laptop for virtual MacOS. So, I decided to learn React Native technology in this course because I have worked with React in Frontend development.

### Penaltis:

1. You can find the ***organization identifier*** in [app.json](app.json) by extra.organizationIdentifier key.
2. You can find the ***deployment target*** (SDK version) in [android/build.gradle](android/build.gradle).
3. To add the ***app icon***:
    * From Android 8.0: To change the icon you just need to replace current icons in [mipmap-*](android/app/src/main/res/) folders named ***ic_launcher.png*** and ***ic_launcher_round.png***.
    * For oldest versions (according to Expo [documentation](https://docs.expo.io/guides/app-icons/#android)): you can do so with the android.icon field in [app.json](app.json).
4. Created standard [***gitignore***](.gitignore) file for React Native applications.
