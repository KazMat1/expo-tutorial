## develop
### initialize a built-in server
```
npm run start
```

## Trouble shooting
**Q.1 iOSの環境を立ち上げようとすると、エラーが出た。**
<details>
<summary>エラー全文</summary>

```
> stickersmash@1.0.0 start
> expo start
(略)
› Using Expo Go
› Press s │ switch to development build

› Press a │ open Android
› Press i │ open iOS simulator
› Press w │ open web

› Press j │ open debugger
› Press r │ reload app
› Press m │ toggle menu
› Press o │ open project code in your editor

› Press ? │ show all commands
(略)
# iをタイプして、simulatorで起動する
› Opening on iOS...
Error: xcrun simctl boot 0CCF51DF-32DD-4624-ADEB-5715E37F9740 exited with non-zero code: 2
An error was encountered processing the command (domain=NSPOSIXErrorDomain, code=2):
Unable to boot device because we cannot determine the runtime bundle.
No such file or directory
```

</details>
A1. https://zenn.dev/mimototo/articles/c596817e14c12c を参考に修正
