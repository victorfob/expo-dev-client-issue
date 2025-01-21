1. run `npx create-expo-app@latest --template blank-typescript`
2. run `npx expo install expo-dev-client`
3. put the `runtimeVersion` tag on `app.json` with any string value
4. run `npx expo install expo-updates`
5. run `eas update:configure`
6. change prop `newArchEnabled` to `false` on `app.json`
7. Create a development build with `npx expo run:android`
