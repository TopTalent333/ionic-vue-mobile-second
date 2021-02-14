## Drip Footwear mobile app concept

![Netlify Status](https://api.netlify.com/api/v1/badges/fc2b8d51-2242-440c-8f6c-f283e77154c4/deploy-status)

The template is based on [@TheMadute's](https://twitter.com/TheMadute/status/1357581896868364289) mobile app design concept for Drip Footwear.

[Demo](https://ionic-vue-mobile-template-07.netlify.app)

## Project setup
```
npm install
```

### Run on the browser - development
```
npm run serve
```

### Linter
```
npm run lint
```

## Design
![Screenshot|316x500, 75%](/design.jpg "Screenshot")

## Native

Using [Capacitor](https://capacitorjs.com/docs/getting-started) for native builds

### Prepare native builds

## iOS testing and distribution
1. Download latest Xcode
2. `npm run build`
3. `npx cap add ios`
3. `npx cap copy`
4. `npx cap open ios` Xcode takes a few minutes to index the files; keep an eye at the top of Xcode's window for progress.

[Not compulsory] For sanity check click on the play button in top left. This will prepare and run the app in a simulator, if all goes well you should be able to login and click around. If not, create an issue 🤷 and I will have a look.

*Icons and launch images* - Xcode (v11.5) cannot map icons listed in config.xml so this has to be done manually 😞. In the root folder look for Resources and select Images.xcassets. A panel will show up where you can select AppIcon to add app icons or LaunchImage to add launch images.

## Android testing and distribution
1. Download latest Android Studio
2. `npm run build`
3. `npx cap add android`
3. `npx cap copy`
4. `npx cap open android` Android Studio takes a few minutes to index the files, keep an eye at the bottom of Android Studio for progress.
5. Testing - When indexing is complete, look for a green play button. Click the play button and it will launch the app in an emulator ([See here to setup Emulator](https://developer.android.com/studio/run/managing-avds)) or on the phone if a phone is connected via USB.

## Official docs
- [Getting started](https://ionicframework.com/vue)
- [Blog](https://ionicframework.com/blog/announcing-ionic-vue/)
- [Changelog](https://github.com/ionic-team/ionic-framework/blob/master/CHANGELOG.md)

## Subscribe
- [Newsletter](https://mailchi.mp/b9133e120ccf/sqan8ggx22) - Signup to my Ionic Vue newsletter to get templates and other Ionic Vue updates in your inbox!
- [YouTube Channel](https://www.youtube.com/channel/UC5jZ6srZuLwt3O3ZtuM1Dsg) - Subscribe to my YouTube channel.

## Affiliates
I want to keep doing these templates for free for as long as possible. I have joined a few affiliate programmes to help take care of the costs. 
- [Pixeltrue](https://www.pixeltrue.com/?via=simo) - High quality illustrations that will help you build breath-taking websites.
- [Getrewardful](https://www.getrewardful.com/?via=simo) - Create your own affiliate program.

Alternatively, you can buy me a coffee <a href="https://www.buymeacoffee.com/simomafuxwana" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="120px" height="30px" style="height: 30px !important;width: 120px !important;" ></a>

## Credits
- [@TheMadute](https://twitter.com/TheMadute/status/1357581896868364289) - Design

## Contact
- [@dlodeprojuicer](https://twitter.com/dlodeprojuicer) on Twitter
