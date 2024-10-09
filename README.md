Ohjeista poiketen tehty erillinen config tiedosto API avaimen suojaamista varten ja lisätty kyseinen tiedodosto gitingoreen.

Saadaksesi toimimaan omalla API avaimella laita API avain tiedostoon js\config.example.js sekä poista .example config tiedoston nimestä
Laita avaimesi config.js tiedoston kohtaan API_KEY: 'sinun_api_avaimesi_tähän' 

var config = {
    API_KEY: 'sinun_api_avaimesi_tähän'
  };



Note: API avaimet jotka olivat vahingossa jääneet alkuperäiseen koodiin ja menneet githubiin, on poistettu käytöstä.