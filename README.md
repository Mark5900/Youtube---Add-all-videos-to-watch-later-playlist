Gør følgende for at få det til at virke:
1. add efter linket på en kanal: /videos?disable_polymer=1 
2. Indlæs alle videoerne du vil have tilføjet
3. Skriv følgende i consolen: javascript: function d(){ var el = document.getElementsByClassName('yt-uix-button yt-uix-button-size-small yt-uix-button-default yt-uix-button-empty yt-uix-button-has-icon no-icon-markup addto-button video-actions spf-nolink hide-until-delayloaded addto-watch-later-button yt-uix-tooltip'); if (el.length > 0) { el[el.length-1].click(); setTimeout(d,500); } }
4. Skriv så i consollen og vent: d();

Hvis man ønsker at tilføje alt fra en playlist til en se senere gør følgende:
1. Gå ind på playlisten
2. Skriv følgende til list i linket: &disable_polymer=true
3. Tryk på de 3 lodrette prikker
4. Tryk på: føj alle til...
