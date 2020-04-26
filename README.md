# esx_vehicleshop

## What can this do?

* He is almost the same as the original author, except that I modified the functions of the two professions so that their bosses can come here to buy their company vehicles.

## Requirements

* Auto mode (everyone can buy vehicles from the dealer)
  * No need to download another resource

* Player management (the car dealer job): billing, boss actions and more!
  * [esx_society](https://github.com/ESX-Org/esx_society)
  * [esx_billing](https://github.com/ESX-Org/esx_billing)
  * [esx_addonaccount](https://github.com/ESX-Org/esx_addonaccount)
  * [esx_addoninventory](https://github.com/ESX-Org/esx_addoninventory)
  * [cron](https://github.com/ESX-Org/cron)

## Download & Installation
### Manually
- Download https://github.com/ESX-Org/esx_vehicleshop/archive/master.zip
- Put it in the `[esx]` directory

## Installation
- Import `esx_vehicleshop.sql` in your database
- Add this in your `server.cfg`:

```
start esx_vehicleshop
```
- If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
