# Verbruiksdashboard
Grafana-dashboard voor weergave van het energieverbruik van slimme meters. In deze opzet zal Home Assistant de slimme meter uitlezen via dsmr-compoent. Die gegevens worden opgeslagen in InfluxDB. Grafana kan vervolgens deze gegevens visualiseren. Om snel een dashboard op te bouwen kun je dit verbruiksdashboard importeren.

## Importen in Grafana
* Download het bestand verbruiksdashboard.json (https://raw.githubusercontent.com/gjgroen/verbruiksdashboard/master/verbruiksdashboard.json)
* Houd de muis op het icoontje voor **Dashboards** en kies **Manage / Import**. 
* Kies **Upload .json File** en selecteer het gedownloade bestand.
* Selecteer bij **datasource** de bijbehorende datasource (bijvoorbeeld Home Assistant) gevolgd door **Import**.

![Voorbeeld dashboard](https://github.com/gjgroen/verbruiksdashboard/raw/master/demo.png)

## Bron
De basis voor het dashboard is een artikel op Clever Crib. De publieke repository die daar bij hoort kun je vinden op https://gitlab.com/clevercrib/energy-dashboard. 
