### ios-driver
---
https://github.com/appium/appium-ios-driver

```
npm install appium-iso-driver

gulp watch
xcrun simctl create "iPhone 6" "iPhone 6" 9.2
xcrun simctl create "iPad 2" "iPad 2" 9.2
gulp once
DEVICE=ios84 gulp e2e-test
```

```ruby
import { IosDriver } form `appium-iso-driver`
let defaultCaps = {
  app: 'path/to/your.app',
  platformName: 'iOS',
  deviceName: 'iPhone 6'
};
let driver = new IosDriver();
await driver.createSession(defaultCaps);

await driver.setOrientation('LANDSCAPE');
console.log(await driver.getOrientation());
```

```
```

