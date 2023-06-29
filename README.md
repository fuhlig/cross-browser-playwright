# Run headed browsers with Playwright
Runs [supported browsers by Playwright](https://playwright.dev/docs/browsers) headed on local machine, e.g. WebKit on Windows.
Head to Playwright documentation for more information.

## Setup
```
npm i
```

## Running browser
```
npm run test:<chrome | firefox | safari>
```

## Update browsers
[Update Playwright](https://playwright.dev/docs/browsers#update-playwright-regularly) 

```
# Update playwright
npm install -D @playwright/test@latest

# Install new browsers
npx playwright install
```

PlayWright and browser version combinations: [Playwright Release Notes](https://playwright.dev/docs/release-notes)