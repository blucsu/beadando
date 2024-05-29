# beadando:3
Szia domnanob ebbe vana doga :3


# Placeholder Text


##### Oah Márk , Csonka Zoltán , Bojsza Bulcsú 


## **Feladat**


### ***Call Center alkalmazás***

A feladat során egy olyan alkalmazást kell elkészíteni, ahol egy call centeres operátor rögzíteni tudja a bejövő és kimenő hívásait. Minden hívásnak rögzíteni kell a pontos időpontját, hívó és hívott számot / melléket, ill. a hívás típusát. Egy hívás típus szerint lehet support (pl egy ügyfél panasz), config (pl egy új szolgáltatás rendelés), ill other (pl két kolléga beszélgetése egy ügy kapcsán). A bejövő és kimenő hívások külön-külön pane-eken legyenek megvalósítva! A hívásokról lehessen pdf formátumban jelentést készíteni egy meghatározott időszakra!


### ***Megvalósítás***


#### ***Feladat megosztás***

- Oláh Márk: fxml létrehozása
- Csonka Zoltán: Controller programozása
- Bojsza Bulcsú: Osztályok megcsinálása 

#### ***"Alkalmazás" létrehozása***

##### **Fxml Scene Builder-ben létrehozzuk az alkalmazás grafikus alapját:**

1. "AnchorPane"-t illetve "Splitpane"-t létrehoztunk.

2. Létrehozunk ezekbe "Pane"-eket ezekbe rakuk:
- "Textfield"-eket 
- "Button"-okat
- "Label"-eket
- "TableView"-kat

3. Osztályok létrehozása, illetve ezekbe változókat:
- Date tipusu idopont
- String név
- Enum tipus 

4. Inicializáljuk  ezeket a tipusokat.

5. Külső könvytárak meghívása.

6. Osztályok oszekötése az "FXML" -el, "FxID" segítségével.

7. "Observable" lista létrhozása az elemek tárolására.

8. Gombok programozása.

9. Dokumentáció illetve a prezentáció elkészítése
***

## **Követelmények**



### **Asztali alkalmazás fejlesztés**

>Teljes értékű JavaFX alkalmazás: A hangsúly a funkcionalitáson van, a design másodlagos! Félkész funkciók ne legyenek az alkalmazásban! Ha megakadtok egy funkció fejlesztése közben, az órákon megbeszéljük. A projektben az MVC struktúrát kell alkalmazni (tehát külön-külön fájlokban és osztályokban legyen a nézet, a modell és a kontroller). Az alkalmazásban a nagyon eltérő funkciókat külön-külön Pane-en kell megjeleníteni. Ezeken kívül JDK17-et és Maven csomagolót kell használni!

>Kivétel- és hibakezelés: Az alkalmazásban minden előforduló kivételt és hibát le kell kezelni, ennek előfordulásakor adj vissza hibaüzenetet piros betűszínnel egy Label-be!

>Ha nem történt hiba és sikeresen lefutott egy funkció, adj vissza fekete / zöld betűszínnel egy tájékoztató üzenetet ugyanabban a Label-ben!

>Adatbázis használata JDBC-vel: Az adatbázis funkciókat külön, erre a célra kialakított osztályban kell implementálni. Adatbázishoz való csatlakozás után érdemes rávizsgálni, hogy létezik-e a kívánt adatbázis és táblák. Így ha nem létezik, akkor az alkalmazásból létre is tudjuk hozni őket. Célszerű Derby-t használni, viszont egyéb MySQL megvalósítás is elfogadott.

>Clean code alapelvek használata: A kód legyen letisztult, a különböző részek megfelelően tagolva, indentálva! Figyelni kell, hogy a különböző funkciók külön-külön metódusokba / függvényekbe legyenek tagolva, ne egybe ömlesztve (+ újra felhasználhatóság)! Értelmes változó neveket kell használni, legyenek beszédesek, hogy kitalálható legyen, mire is jók. Célszerű kommentelni is, melyik részegység mire való.

>Szoftver ergonómia: A feliratok jól láthatóak legyenek, a gombok megfelelően kattinthatóak legyenek (ne túl kicsi, ne túl nagy)!
***

### **IKT projektmunka**


>Bemutató készítése az elkészített szoftverhez.

>A bemutatónak legalább 15 diát kell tartalmaznia, mely az alábbi felépítést tartalmazza:

- A szoftver céljának rövid bemutatása
- A szoftver felépítése (menürendszer, képernyőképek, stb.)
- A szoftver használatának bemutatása
- Az elkészített szoftver továbbfejlesztési lehetőségei
- A diákon maximum 28-as betűméret alkalmazható


>Figyelni kell a helyesírásra, nyelvhelyességre (zavaró elírások, helyesírási hibák, stb.PONTLEVONÁST fog jelenteni)

>Az elkészített bemutató előadása
***


### **Szoftvertesztelés**

>Készítsd el a projekted dokumentációjához az osztály diagramot! A diagram tartal-
mazza a megoldás összes osztályát, az osztályok adattagjait és metódusait továbbá a (ha van) jelöld nyilakkal az öröklődéseket (minta).

>A program gyenge pontjain (ahol felhasználótól kérünk adatot), kezelje megfelelően egy tanult módzserrel úgy, hogy ne okozhasson hibát a felhasználó!

>A programban valahol használjon legalább egy saját készítésű kivételt!

>Készítsen tesztelési útmutatót a projektjéhez! Ez egy reademe.md (segédlet) fájl legyen, amiben lépésről lépésre bemutatja az alkalmazás felhasználását. Figyeljen arra,hogy a program minden funkcióját bemutassa vele! 


> *Például:*

1. Indítsuk el az alkalmazást a yxz.java futtatásával.
2. Kattintsunk a “hozzáadás” gombra egy új elem hozzáadásához.
- 2/a. Adjunk meg egy nevet a ... mezőbe, ez lesz a ... neve
- 2/b Adjunk meg egy évszámot a ... mezőbe, ami a ... lesz


>Készítsen Unit teszteket a programhoz! Válasszon ki legalább 2 függvényt, amelyhez elkészíti a Unit teszteteket. Minden függvényhez készítsen egy egyenlőség vizsgálatotlegalább 3 opcióval

1. **Szám esetén:**
- “Nem egyenlő” vizsgálat: túl kicsi opció
- “Egyenlő” vizsgálat: megfelelő opció
- “Nem szám” vizsgálat: rossz bemenet
2. ***Szöveg esetén:***
- “Üres” vizsgálat: üres bemeneti mező
- “Megfelelő” vizsgálat: jó bemenő adat
- “Hibás” vizsgálat: nem megfelelő adat
