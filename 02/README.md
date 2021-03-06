# [![](../assets/img/logo-readme2.jpg)](https://devmentor.pl) &nbsp; JavaScript: API & FETCH #02

> :loudspeaker: Jeśli chciałbyś więcej tego typu zadań to zapraszam do :moneybag: [wsparcia mojego konta](https://github.com/sponsors/devmentor-pl)!

&nbsp;

W pliku `app.js` ponownie masz przygotowany kod, który ustawia kolor obramowania dla wyszukanych `div`-ów. Tym razem jest on zabezpieczony przed podaniem nieprawidłowego elementu czy braku *callback-a*.

Twoim zadaniem jest przebudować funckję `setBorderColorAsync()` w taki sposób, aby realizowała to samo przy pomocy obietnic (`Promise`) tj. powinna zwracać obiekt utworzony przy pomocy `new Promise( (resolve, reject) => ...)`;

Pamiętaj, że `resolve` to funkcja, która jest uruchamiana w przypadku powodzenia, natomiast `reject` gdy coś jest nie tak.

Po wprowadzeniu tej zmiany musisz również zmienić wykorzystanie tej funkcji zgodnie z jej obecną implementacją. Pamiętaj, że `.then` może być wielokrotnie wykorzystane.

&nbsp;

> :warning: Jeśli nie posiadasz materiałów do tego zadania to znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/p/js-api-and-fetch/)