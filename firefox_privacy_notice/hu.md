# Firefox böngésző Adatvédelmi tájékoztató

2016. június 24.
{: datetime="2014-04-15" }

Fontos számunkra az Ön adatainak védelme. Ha a Firefox adatokat küld a Mozilla (ez minket jelent) számára, akkor [adatvédelmi irányelveink](https://www.mozilla.org/privacy/) írják le ezek kezelésének módját.

## Tudnivalók

A Firefox automatikusan csatlakozik hozzánk és szolgáltatóinkhoz frissítések, biztonsági elemek, kódrészletek, Firefox állapotjelentés és egyéb funkciók biztosítása érdekében.
{: #essential-features }

* **Böngésző és kiegészítők frissítése**
{: #auto-updates }

	Böngészőfrissítések: Naponta egyszer a Firefox a következő adatokat küldi el a Mozillának, amikor az böngészőfrissítéseket keres: az Ön Firefox verziójának adatai, a nyelvi beállítás, az operációs rendszer és annak verziója. Megteheti, hogy [kikapcsolja a frissítéseket a következő utasítások szerint](https://support.mozilla.org/kb/how-stop-firefox-automatically-making-connections#w_auto-update-checking), de ez biztonsági szempontból sérülékenységet jelenthet az Ön számára.

	Letiltott kiegészítők listája: A Firefox naponta egyszer kapcsolatba lép a Mozillával, és egyezteti a kiegészítők adatait, hogy a rosszindulatú kiegészítőket ellenőrizhesse. Ez magában foglalja például a következőket: böngészőverzió, operációs rendszer és verzió, területi beállítás, összes kérés száma, a legutóbbi kérés dátuma, a napon belül az időpont, IP-cím és az Ön által telepített kiegészítők listája. Bármikor megteheti, hogy [kikapcsolja a metaadatok frissítését](https://blog.mozilla.org/addons/how-to-opt-out-of-add-on-metadata-updates/), de ez biztonsági szempontból sérülékenységet jelenthet az Ön számára.

* **Kódrészletek**
{: #snippets }

	A Firefox alapértelmezett kezdőlapja (&lt;about:home&gt;) közvetlenül a keresősáv alatt olyan rövid tájékoztatásokat jelenít meg, amelyeket az Ön számára hasznosnak ítélünk. Ezeket „kódrészleteknek” nevezzük. Körülbelül naponta egy alkalommal a Firefox csatlakozik a Mozillához, és új kódrészleteket nyújt Önnek, ha vannak ilyenek. A Mozilla az alábbi adatokat gyűjtheti össze: milyen gyakran kattintanak rá a kódrészletekre, a kódrészlet nevét, a böngésző területi beállításait és hogy a Firefox melyik verzióját használja. Ezeket az adatokat 60 nap elteltével kizárólag összesített formában őrizzük meg.

	Annak érdekében, hogy megfelelő kódrészleteket jelenítsen meg, a Firefox IP-címe segítségével havonta lekérdezi a Mozillától az Ön országszintű tartózkodási helyét. Utána az országszintű adatokat visszaküldjük a Firefox-nak, amely helyileg tárolja ezeket. A Firefox az Önnek megjelenő kódrészleteket a helyileg tárolt országszintű adat alapján fogja kiválasztani.

	Bizonyos a Mozilla által támogatott kódrészletek interaktív módon működnek és lehetőséget nyújtanak Önnek telefonszámai és e-mail címei megosztására. Például megadhatja a telefonszámát, erre kap egy sms-t, amellyel a Firefox-ot Android alkalmazásra is feltöltheti. Az Ön adatait az Ön e-mail és mobiltelefon szolgáltatója fogja megkapni és kezelni.

* **Firefox állapotjelentés**
{: #health-report .inproduct-link }

	A Firefox állapotjelentés (FHR) célja, hogy az Ön számára rálátást nyújtson saját böngészője stabilitására és teljesítményére, és hogy tippek formájában támogassa Önt, amikor problémát észlel, például gyakori összeomlást vagy lassú indítást. A Mozilla más Firefox felhasználókéval együtt és összesítve gyűjti az Ön adatait, és visszaküldi az Ön saját böngészőjére, hogy Ön láthassa, hogyan változik a Firefox teljesítménye az idő múlásával. Ezek az adatok magukban foglalják például a következőket: hardver eszköz, operációs rendszer, Firefox verzió, kiegészítők (száma és típusa), a böngészési események időzítése, feldolgozás, munkamenet helyreállítása, munkamenet hossza, profil kora, összeomlások száma és az oldalak száma. Az FHR nem tartalmazza az Ön által látogatott oldalak URL címeit.

	Az FHR-en keresztül küldött adatokat arra használjuk, hogy biztosítsuk a felhasználók számára a működőképességet, és hogy megoldjuk böngészője teljesítménnyel kapcsolatos problémáit. Arra is felhasználjuk az FHR adatok alapján leszűrteket, hogy fejlesszük a Firefox-ot. Dönthet úgy, hogy [kikapcsolja az adatmegosztást](https://support.mozilla.org/kb/firefox-health-report-understand-your-browser-perf#w_how-to-turn-data-sharing-on-or-off).

* **Biztonság**
{: #security }

	A Firefox automatikusan ellenőrzi a rosszindulatú vagy hamisított webhelyeket, a sérült kiegészítőket és a harmadik fél által kibocsátott SSL tanúsítványokat.

	Biztonságos webhely tanúsítványok: Ha Ön felkeres egy biztonságos webhelyet (pl. „https”), akkor a Firefox ellenőrzi a webhely tanúsítványát. Ennek része lehet a tanúsítvány által megjelölt állapotszolgáltatóval folytatott kommunikáció. A Firefox elküldi ezeket a harmadik féltől kapott adatokat, amelyek igazolják a webhely [tanúsítványát](https://support.mozilla.org/kb/secure-website-certificate). Lehetősége van [megváltoztatni a beállításait](https://support.mozilla.org/kb/advanced-settings-browsing-network-updates-encryption#w_certificates-tab), de ha kikapcsolja az online hitelesítés funkciót, akkor a Firefox nem képes megerősíteni az Ön által felkeresett webhely azonosítóját. Ennek a funkciónak a kikapcsolása növelheti annak kockázatát, hogy megszerzik a személyes adatait. Ha [nem megbízható kapcsolatot](https://support.mozilla.org/kb/connection-untrusted-error-message)észlel, akkor elküldheti a Mozillának az ahhoz rendelt tanúsítványokat.

	Firefox hamisítás és támadás elleni védelem: Körülbelül óránként kétszer a Firefox letölti a Google SafeBrowsing listáját, ezzel járul hozzá a rosszindulatú vagy hamisított webhelyekhez és letöltésekhez való hozzáférés megakadályozásához (a Google adatvédelmi irányelvei itt érhetők el: <https://www.google.com/policies/privacy/>). Az ezeken a listákon nem szereplő letöltött végrehajtható elemek esetén a Firefox a letöltött fájlhoz kapcsolódó metaadatokat – beleértve az URL-t – elküldheti a SafeBrowsing szolgáltatás részére. Keresse fel a(z) <https://support.mozilla.org/kb/how-does-phishing-and-malware-protection-work> webhelyet, hogy további információkat kapjon a SafeBrowsing szolgáltatásról, vagy hogy kikapcsolja azt. Ha kikapcsolja ezeket a funkciókat, a Firefox nem tudja figyelmeztetni Önt a potenciálisan illegitim vagy rosszindulatú webhelyekre vagy letöltött fájlokra.

* **Használati statisztikák** (más néven „Telemetria” ki nem adott build esetén)
{: #telemetry .inproduct-link}

	A használati statisztikák vagy „Telemetria” a Firefox azon funkciója, amely elküldi a Mozilla használati, teljesítményre és reakcióidőre vonatkozó statisztikáit a felhasználói felület funkcióival, memóriájával és hardverkonfigurációjával összefüggésben. A szokásos webes naplózás részként az Ön IP-címét is gyűjti a rendszer. A használati statisztikákat SSL alkalmazásával továbbítják, és ezek segítenek bennünket a Firefox jövőbeli verzióinak tökéletesítésében. A Mozillához küldést követően a használati statisztikákat összesítik, és fejlesztők széles köre számára teszik hozzáférhetővé, beleértve a Mozilla alkalmazottait és közreműködőit. Amikor a Telemetria be van kapcsolva, bizonyos rövid távú kísérletek adatokat gyűjthetnek a felkeresett webhelyekről.

	Ez a funkció alapértelmezés szerint engedélyezett a Firefox Nightly, Aurora és Beta build változatainál, hogy segítse azokat a felhasználókat, akik visszajelzést adnak a Mozillának. A Firefox általános kiadott változatai esetében alapértelmezett beállításként ez a funkció ki van kapcsolva.

	Itt [tudhat meg többet a telemetriáról](https://support.mozilla.org/kb/send-performance-data-improve-firefox) és annak be- vagy kikapcsolásáról.

* **Csempék**
{: #searchsuggestions }

	A keresési javaslatok funkció segítségével megtalálhatja azokat a gyakori kifejezéseket, amelyekre mások rákerestek. Ezeket a keresési javaslatokat az Ön alapértelmezett keresőprogramja ajánlja fel (például Google, Yahoo stb.), nem a Firefox. Ha engedélyezi ezt a funkciót, és az alapértelmezett keresőprogramja támogatja a javaslatokat, a Firefox elküldheti az intelligens címsorba vagy a keresősávba begépelt kifejezéseket az alapértelmezett keresőprogramjának, hogy javaslatokat kérjen le. Ekkor az alapértelmezett keresőprogram vonatkozó Adatvédelmi szabályzata van érvényben. A [keresési javaslatokról, illetve ezek](https://support.mozilla.org/kb/use-popular-search-suggestions-firefox-search-bar) engedélyezéséről vagy letiltásáról még több információt találhat itt.

* **Alapértelmezett keresés**
{: #thirdparty }

	Annak érdekében, hogy tartózkodási helyén a legjobb alapértelmezett keresőszolgáltatást válassza, a Firefox IP-címe segítségével egyszeri alkalommal lekérdezi a Mozillától az Ön országszintű tartózkodási helyét. Utána az országszintű adatokat visszaküldjük a Firefox-nak, amely helyileg tárolja ezeket. Ezután a helyileg tárolt országszintű adat alapján a Firefox kiválasztja, hogy melyik keresőszolgáltatást használja alapértelmezettként. További információkat [itt](https://support.mozilla.org/kb/send-anonymous-usage-data-firefox-mobile-devices) talál, a kikapcsolással együtt.

---------------------------------------

Az Ön kérésére is csatlakozik a Firefox a Mozillához, hogy Önnek funkciókat biztosítson, például a Sync funkciót, helymeghatározási szolgáltatásokat, összeomlás jelentést és kiegészítőket.
{: #optional-features }

* **Sync**
{: #sync }

	[A Firefox Sync](https://www.mozilla.org/firefox/sync/) olyan szolgáltatás, amelynek révén szinkronizálhatja Firefox könyvjelzőit, böngészési előzményeit, jelszavait és beállításait minden eszközén. Amennyiben használja a Sync szolgáltatást, akkor olvassa el a [Firefox Sync Adatvédelmi tájékoztatót](https://accounts.firefox.com/legal/privacy)

* **Helymeghatározási szolgáltatások**
{: #location-services }

	A Firefox rendelkezik olyan funkcióval, amelynek révén a webhelyek lekérhetik az Ön tartózkodási helyét (pl. azért, hogy ezek a webhelyek feltüntethessék az Ön helyét térképen). Ha egy webhely kéri az Ön tartózkodási helyének adatait, akkor a Firefox az Ön engedélyét kéri, mielőtt meghatározná vagy megosztaná az Ön tartózkodási helyét. Az Ön helyének meghatározása során a Firefox számos adatot felhasználhat, beleértve az Ön operációs rendszerének földrajzi helyének jellemzőit, a WiFi hálózatokat, mobiltornyokat vagy IP-címet. Az Ön tartózkodási helyének megállapítása során előfordulhat, hogy ezen adatok egy részét elküldjük a Google földrajzihely-szolgáltatásához, amely rendelkezik saját [adatvédelmi irányelvvel](https://www.google.com/privacy/lsf.html).

* **Összeomlási jelentés**
{: #crash-reporter .inproduct-link }

	Önnek lehetősége van rá, hogy a Firefox összeomlása után összeomlási jelentést küldjön a Mozillának. Ebben a jelentésben műszaki adatok szerepelnek, amelyek segítségével fejleszthetjük a Firefox-ot, beleértve a Firefox összeomlásának okát, az összeomlás idején aktív URL-t, és a számítógép memóriájának állapotát az összeomlás idején. Az összeomlási jelentés részeként személyes adatok is eljuthatnak hozzánk. Az összeomlási jelentések egyes részeit nyilvánosságra hozzuk itt: <https://crash-stats.mozilla.com/>. Az összeomlási jelentések közzétételét megelőzően lépéseket teszünk a személyes adatok automatikus kivonása érdekében. Nem távolítunk el semmit, amit Ön írt a megjegyzés mezőbe.

* **SSL hibák**
{: #ssl-errors }

	Önnek lehetősége van hibajelentést küldeni a Mozilla részére, ha biztonságos webhellyel szakadt meg a kapcsolat. Ez a jelentés magában foglalja a webhely tanúsítványát, valamint a diagnosztikai hibakódokat. Ezek az adatok segítik a Mozillát a „rögzített“ webhely tanúsítványok hatékonyságának nyomon követésében, és a felhasználói ellen irányuló esetleges adathalászati kísérletek észlelésében.

* **Kiegészítők**
{: #addons }

	A Firefox a kiegészítőkezelő a népszerű kiegészítőket tartalmazó kiegészítők letöltése oldalát ajánlja, és személyes ajánlásokat jelenít meg az Ön által már telepített kiegészítőkre vonatkozóan. A személyes ajánlások megjelenítéséhez a Firefox adatokat küld a Mozillának, beleértve az Ön által telepített kiegészítők listáját, a Firefox verzióadatait és az Ön IP-címét. Erre a közlésre csak akkor kerül sor, ha a Kiegészítők letöltése terület meg van nyitva, és ki lehet kapcsolni a következő [utasításokat követve](https://blog.mozilla.org/addons/how-to-opt-out-of-add-on-metadata-updates/). A Firefox kiegészítőkezelője olyan keresési mezővel rendelkezik, amelyben megadhatja a keresés kulcsszavait, és a Mozilla összegyűjti ezeket a keresési kulcsszavakat, valamint az Ön Firefox verziójának adatait, területi beállításait, és operációs rendszerét, hogy ajánlásokat mutathasson Önnek.

* **Leküldéses értesítések**
{: #push-notifications }

	A leküldéses értesítések engedélyezik az oldalaknak, hogy értesítéseket és frissítéseket küldjenek Önnek, ha engedélyezi ezt az opciót. Annak érdekében, hogy értesítéseket kapjon, a Firefox információt küld a Mozilla számára arról, hogy Ön mely oldalak esetében engedélyezte a leküldéses értesítéseket. Ezt az információt, illetve az egyes oldalak által küldött értesítések számát névtelenül tároljuk. A Mozilla segít a fejlesztőknek a leküldéses értesítések minél hatékonyabb használatában, ezért összesített információkat oszthat meg bizonyos fejlesztőkkel, többek között azt, hogy az oldalukra látogatók közül hányan iratkoztak fel a leküldéses értesítésekre vagy iratkoztak le azokról. A Firefox böngészőben az [alábbi utasítások](https://support.mozilla.org/kb/push-notifications-firefox) betartásával kezelheti a leküldéses értesítéseket.

Egyéb megjegyzés hiányában ez az adatvédelmi tájékoztató a Firefox legfrissebb általánosan kibocsátott verzióira vonatkozik. A kibocsátás előtti verziók (Beta, Aurora/Developer Edition, Nightly és TestFlight) még fejlesztés alatt állnak, ezért új funkciókat tartalmazhatnak és eltérő adatvédelmi jellemzők vonatkozhatnak rájuk. A kibocsátás előtti verziók automatikusan [telemetriai adatokat](https://gecko.readthedocs.io/en/latest/toolkit/components/telemetry/telemetry/index.html) küldenek a Mozillának, amelyek segítenek nekünk a Firefox további fejlesztésében.
{: #pre-release }
