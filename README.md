# Etrellis Weather

This module contain customization to show weather using openweathermap API.

## INSTALLATION
In magento root directory, execute:

```bash
php bin/magento module:enable Etrellis_Weather
php bin/magento setup:upgrade
php bin/magento setup:di:compile
```

## Usage

goto admin stores->configurations->Etrellis->Weather and add api key and city id, after that weather will show on BASE_URL/weather page.
