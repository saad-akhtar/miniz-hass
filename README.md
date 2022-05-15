# miniz-hass
Miniz Miner Home-Assistant Dashboard Using REST/JSON API Calls

This integration will require running Home-Assistant (www.home-assistant.io) on a device. I use HASS for many other automations around my house so this (POW) is one of few other tabs that control hundreds of other sensors, devices around my home.

Setting up and running HASS is beyond the scope of this instruction set as such there are hundreds of online guides, HASS website itself has a pretty awesome howto as well as many youtube videos of HASS users. This is a whole ecosystem made for your home which allows for an infinite numbers of customizations. I could literally write pages upon pages explaining why i love HASS, good for me that i love coding more ;-)

Using a file editor plugin in HASS, edit your configuration.yaml and add code under sensors: section (be sure to remove the "sensors:" from copy/paste if you already have a section for it). if you dont have a sensors section in your configuration just yet then just copy paste complete contents to your configuation.yaml.

Using file editor again now edit ui-lovelace.yaml (this controls the UI or display part of things). Paste code from the ui-lovelace.yaml file. If you already have other itegrations/UI components in your ui-lovelace.yaml then be sure to copy paste the contents of resources: under resources: and remove the title: / views: section (since you already have one).

Following integrations are required and can easily be installed via HACS (lookup HACS setup on home-assistant.io)
  * Lovelace Clock Card (https://github.com/Villhellm/lovelace-clock-card)
  * Gauge Card (https://www.home-assistant.io/dashboards/gauge/)
  * Vertical Stack In Card (https://github.com/ofekashery/vertical-stack-in-card)
  * Apex-Charts Card (https://github.com/RomRider/apexcharts-card)

I can provide some further help if needed. open a new issue in project.

![hass-ui](https://github.com/saad-akhtar/miniz-hass/raw/main/hass-ui.png)
