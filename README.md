# Polestar API

This is not an official Home Assistant integration affiliated with Polestar.

## Use your Polestar ID

This is the account that you use to log in to the Polestar website, which is not necessarily the same account you use in the Polestar iOS or Android app.

Log in at https://polestarid.eu.polestar.com/Account/login to check if your car is listed.

If it is not listed, refer to [Adding a new car to your Polestar ID](https://www.polestar.com/manual/polestar-2/2026/article/631aa0693e35cfbac0a801516233a047/) in the manual to add your car to your Polestar account, or contact [Polestar support](https://www.polestar.com/support/contact/) (eg, if the car is a fleet or leased vehicle)

 ## Prerequisites

 * HACS (Home Assistant Community Store) must be installed. If you haven't installed HACS yet, follow the [official HACS installation guide](https://hacs.xyz/docs/use/#getting-started-with-hacs).

## Add in HA Integration

* Search for integration 'polestar_api' in HACS
* Download the integration in HACS
* Go to Settings, Integrations in Home Assistant
* Add the "Polestar API" integration

### Fill the information

Email (Polestar ID) and password are the credentials you use to login in to your Polestar account.

![image](https://github.com/pypolestar/polestar_api/assets/1487966/30645415-ce93-4c73-ad60-6cbff78e691a)

Result:
![image](https://github.com/pypolestar/polestar_api/assets/1487966/fe8d08d8-9d0d-424c-a7a8-ce702679a567)

## Missing or Unknown sensors

There are currently several sensors that report no information for some or all models.
Unfortunately there is nothing the developers of this integration can do about this, but we do recommend you contact [Polestar support](https://www.polestar.com/support/contact/) and express your support for a public API for integration with Home Assistant and similar systems.

## Translation

Translations are managed via [Crowdin](https://crowdin.com/project/polestar-home-assistant) - please join the project and contribute!
