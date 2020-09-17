# QR Code Generator Canvas app with PowerApps

A Canvas app built using [Microsoft PowerApps](https://docs.microsoft.com/en-us/powerapps/) to generate QR Code with a text input.

This is developed as for a use case using PowerApps as the application layer to generate QR Code programmatically using Azure Functions for users within an organziation without the use of a public available QR Code generators for various reasons. Please refer to this repo [QR Code Generator using Azure Functions](https://github.com/jenzushsu/qrcode-generator-azure-functions) for Function App developed for this use case.

You can refer to this medium article Generate QR Code programmatically using Azure Functions + Power Apps for the details on this PowerApps.

## Installation
Refer to this [documentation](https://docs.microsoft.com/en-us/powerapps/maker/common-data-service/import-update-export-solutions) to import this solution to your PowerApps environment.

You will need to deploy the Function App and update the HTTP GET Request URL link in the flow.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Disclaimer
*This app is a sample and may be used with Microsoft Power Apps. You bear the sole risk and responsibility for any use of this app. The innovation and views expressed here are those of my own and do not necessarily state or reflect those of Microsoft Singapore or Microsoft Corporation.
