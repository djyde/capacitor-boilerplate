# capacitor boilerplate


## Includes

- TypeScript
- SolidJS
- TailwindCSS

## Usage

### Change app identity

In `capacitor.config.json`, change `appId` and `appName` to your own:

```diff
{
- "appId": "com.example.capacitor",
- "appName": "capacitor-boilerplate",
  "bundledWebRuntime": false,
  "webDir": "dist",
  "plugins": {
    "SplashScreen": {
      "launchShowDuration": 0
    }
  }
}
```