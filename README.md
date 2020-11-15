# Lovelace meteofrance weather card Icones

Iconnes supplémentaires pour la carte ![lovelace-meteofrance-weather-card](https://github.com/hacf-fr/lovelace-meteofrance-weather-card).

Récupèrez un ou les dossiers icons_2 et icons_3 (dans le dossiers « dist »).
Copie les dans un dossier de votre www. Ensuite pointer le dossier dans "Icons location":

![](/ajout.png)

Vous pouvez les essayer plus simplement en mettant ces adresses dans "Icons location" (mais ajoutez les en locale si vous les utilisez):

http://axellum.free.fr/Lovelace/icons_2/

http://axellum.free.fr/Lovelace/icons_3/


Les icônes fixe viennent de https://icon-icons.com/fr/pack/The-Weather-is-Nice-Today/1370, création de Laura Reen. J'ai parfois apporté de légère modifications.

Les icônes animés bleus sont issus de https://www.amcharts.com/free-animated-svg-weather-icons/, avec modifications sur certain pour les compléter.

Les icônes animés blancs arrivent de https://github.com/fineemb/lovelace-colorfulclouds-weather-card, avec modifications de positionnement.

### Icones animés bleus:
![](/dist/icons/day.svg)
![](/dist/icons/night.svg)

![](/dist/icons/windy-night.svg)
![](/dist/icons/windy.svg)
![](/dist/icons/fog.svg)
![](/dist/icons/fog1.svg)


![](/dist/icons/cloudy.svg)
![](/dist/icons/cloudy-day-3.svg)

![](/dist/icons/cloudy-night-3.svg)
![](/dist/icons/lightning-rainy.svg)
![](/dist/icons/rainy-5.svg)
![](/dist/icons/rainy-6.svg)


![](/dist/icons/rainy-7.svg)
![](/dist/icons/snowy-6.svg)
![](/dist/icons/snowy-rainy.svg)
![](/dist/icons/thunder.svg)


### Icones animés blancs:
![](/dist/icons_3/day.svg)
![](/dist/icons_3/night.svg)
![](/dist/icons_3/windy-night.svg)
![](/dist/icons_3/windy.svg)

![](/dist/icons_3/fog.svg)
![](/dist/icons_3/cloudy.svg)
![](/dist/icons_3/cloudy-day-3.svg)
![](/dist/icons_3/cloudy-night-3.svg)

![](/dist/icons_3/lightning-rainy.svg)
![](/dist/icons_3/rainy-5.svg)
![](/dist/icons_3/rainy-6.svg)
![](/dist/icons_3/rainy-7.svg)

![](/dist/icons_3/snowy-6.svg)
![](/dist/icons_3/snowy-rainy.svg)
![](/dist/icons_3/thunder.svg)

Note:
Utilisation possible sur d'autres carte avec ces réglages:

   ```yaml
const weatherIconsDay = {
  clear: "day",
  "clear-night": "night",
  cloudy: "cloudy",
  fog: "fog",
  hail: "rainy-7",
  lightning: "thunder",
  "lightning-rainy": "lightning-rainy",
  partlycloudy: "cloudy-day-3",
  pouring: "rainy-6",
  rainy: "rainy-5",
  snowy: "snowy-6",
  "snowy-rainy": "snowy-rainy",
  sunny: "day",
  windy: "windy",
  "windy-variant": "windy",
  exceptional: "!!",
};

const weatherIconsNight = {
  ...weatherIconsDay,
  clear: "night",
  sunny: "night",
  partlycloudy: "cloudy-night-3",
  "windy-variant": "cloudy-night-3",
};
   ```
