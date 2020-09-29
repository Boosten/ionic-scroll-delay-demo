# Ionic scroll delay example app

There's a slight delay when focusing an input element that causes the keyboard to push up the content on iOS.
See video:

[![Alt text](https://img.youtube.com/vi/9MiRkBEevn0/0.jpg)](https://www.youtube.com/watch?v=9MiRkBEevn0)
Besides that, you can also see that the accessory bar turns black for a brief moment when changing focus to the next input field.
The input field that shows the accessory bar has the autocomplete attribute set to `autocomplete="current-password"`.

```
npm i
npm run build
npx cap sync
npx cap open ios
# start the app in Xcode
```
