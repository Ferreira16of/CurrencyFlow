# CurrencyFlow

**A free, responsive, open-source currency converter built with HTML, CSS, and vanilla JavaScript.**

CurrencyFlow provides currency conversion, historical lookups, and charts based on real historical observations. It does not require an account, API key, backend, or build step.

## Features
- Currency conversion with the latest available reference rates.
- Historical conversion for supported dates.
- Trend charts based on actual historical data — no fabricated or simulated points.
- Responsive UI and keyboard-operable currency selectors.
- Static hosting on Netlify or GitHub Pages.
- No private API credentials embedded in client-side code.

## Exchange-rate data
The app uses the [Frankfurter API](https://www.frankfurter.app/), which publishes exchange-rate data based on reference rates from the European Central Bank. These are indicative reference rates, not guaranteed bank, cash-exchange, card, or real-time trading prices. Available currencies and dates depend on the upstream provider; weekends and holidays may have no new observation.

## Run locally
Open `index.html` in a browser or use VS Code Live Server. There is no package installation or build step.

## Deploy to Netlify
1. Sign in to Netlify and choose **Add new site → Import an existing project**.
2. Connect GitHub and select `Ferreira16of/CurrencyFlow`.
3. Leave the build command empty and set the publish directory to `.`.
4. Deploy. `netlify.toml` contains the same static publishing configuration.

## Contributing
Issues and pull requests are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) and follow the [Code of Conduct](CODE_OF_CONDUCT.md). For security concerns, see [SECURITY.md](SECURITY.md).

## License
Released under the [MIT License](LICENSE).

## Credits
- Exchange rates: [Frankfurter](https://www.frankfurter.app/)
- Charts: [Chart.js](https://www.chartjs.org/)
- Icons: [Feather Icons](https://feathericons.com/)
- Font: [Montserrat](https://fonts.google.com/specimen/Montserrat)
- Flag images: [FlagCDN](https://flagcdn.com/)

CurrencyFlow is an independent community project and is not affiliated with the European Central Bank, Frankfurter, or Netlify.
