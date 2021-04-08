<h1>MINE FIELD</h1>

App Mockup

<h2>O HŘE</h2>

* Hra je dostupná na systémech IOS a Windows
* Je určena pro krátkodobé zaměstnání a zabavení uživatele
* Je určena pro nenáročné uživatele
* Hra je inspirována starou klasikou Minesweeper

* Pro vstup do aplikace je důležité přihlášení pomocí emailové adresy nebo facebooku
* Hráč má možnost vybrat si uživatelské jméno
* Hra zaznamenává každé dosažené skóre do tabulky výsledků

<h2>PRAVIDLA HRY</h2>

* Hra je rozdělena do tří obtížností
* Rozdíl v jednotlivých obtížnostech spočívá v počtu životů, počtu min rozsetých v herním minovém poli, ale velikost minového pole zůstává stejná
* <b>Nováček</b> => 3 životy, 10 min, pole 10x10
* <b>Pokročilý</b> => 2 životy, 18 min, pole 10x10
* <b>Zkušený</b> => 1 život, 25 min, pole 10x10

* Hra spočívá v postupném odkrývání všech políček na poli
* Existuje několik možností, co je na políčku ukryto
* <b>1. možnost</b> => políčko je prázdné => 0 bodů
* <b>2. možnost</b> => políčko ukrývá hodnotu => X bodů (X = hodnota, kolik min je v okolí daného pole, směrem nahoru, vlevo, vpravo a dolů)
* <b>3. možnost</b> => políčko ukrývá minu => -5 bodů -1 život (v případě obtížnosti "zkušený" znamená první odkrytí miny konec hry a neodčítají se žádné body)

* Skóre z dané hry se definuje sčítáním získaných bodů
* Pokud hráči dojdou životy, hra končí a jeho dosavadní získaný počet bodů tak udává jeho skóre
* Za minu, která ukončí hráčovu hru, se neodčítají žádné body
* V případě odkrytí všech políček, krom políček s minou, hra končí a hráč získává plný počet bodů pro danou obtížnost v daném poli, stává se tedy vítězem

<h2>ORIENTACE VE HŘE</h2>

* Minové pole bude mít vždy čtvercový obrys a bude ohraničeno rámem
* Každé zakryté políčko bude mít čtvercový obrys, světlý odstín barvy a bude ohraničeno rámečkem
* Každé odkryté políčko bude mít stejný obrys a rámeček, ale jeho barva se změní
* Při odkrytí prázdného pole, se odstín změní na tmavý
* Při odkrytí bodovaného pole, se odstním změní na tmavý a objeví se ikona hodnoty daného pole (číslo 1/2/3/4)
* Při odkrytí miny, se barva změní na rudou a objeví se ikona miny

* V pravé straně od minového pole, by se nacházela takzvaná výdleková tabule
* Tabule bude ukazovat současně dosažené skóre v dané hře
* Bude se zde nacházet tabulka s pěti historicky nejlepšími výsledky uživatele z dané obtížnosti

* Bude zde také prostor pro nápis, který se bude měnit
* V případě prázdného pole se objeví nápis "Kousek vedle"
* V případě bodovaného pole se objeví nápis "Skvělý tah"
* V případě pole s minou se objeví nápis "Šlápl jsi na minu"
* V případě pole s minou v situaci, kdy hráči zbývá poslední život se objeví nápis "Konec hry"

* V pravém dolním rohu, uvidí na jakou obtížnost zrovna hraje
* Také zde má tlačítka pro resetování hry a nebo změny obtížnosti


