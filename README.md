#appium-dotnet-driver samples

## Run locally

### Download apps (default)

- Start Appium.
- Run the tests in NUnit.

### Use Appium dev apps 

- Clone Appium.
- Build dev version of appium `./reset.sh --android --ios --dev --hardcore`
- `cp samples/env.json.sample samples/env.json`
- Update `samples/env.json` set DEV=true
- Start appium: `node .`
- Run the tests in NUnit.

## Run on Sauce Labs

- `cp samples/env.json.sample samples/env.json`
- Update `samples/env.json` set SAUCE=true, and configure your Sauce credentials.
- Run the tests in NUnit.
