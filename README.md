# Integration module for Opencart 3.0.x
Epoint integration module version 1.0.0 for Opencart 3.0.x

[![N|Solid](https://epoint.az/images/logo.svg)](https://epoint.az/)

Information about [epoint.az](https://epoint.az) you can find on the website.

## Requirements
- [epoint-opencart-3.0.x.ocmod.zip](https://r2.abbaszade.dev/epoint-opencart-3.0.x.ocmod.zip) is tested on v3.0.3.8, v3.0.3.9

## Installation Steps
1. Download the ZIP File
2. In the admin panel of your Opencart website, navigate "Extensions" -> "Installer" -> Upload -> Select the downloaded file.
3. After installation, in the admin panel, navigate "Extensions" -> "Extensions".
4. In the filter "Choose the extension type", select "Payments"
5. In the list of "Payment Method", find "Epoint.az" and click the "+" button on the right side

## After activation
1. Insert your Public key in the "Public key" field.
2. Insert your Secret key in the "Private key" field.
3. Set the currency to AZN. (If not listed, it should be added in the System -> Localisation -> Currencies).
4. If the currency is selected as USD or EUR, add the exchange rate index for AZN.
5. Select one of the languages: az, en, or ru.
6. Set the status to "Enabled"


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.
