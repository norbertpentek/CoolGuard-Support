# CoolGuard – Privacy Policy

_Last updated: 6 November 2026_

This policy covers CoolGuard for iPhone and its Apple Watch app. It does not describe the Android version.

The App Store version and the features available to you may differ:

- **Version 1.4 and later** use Apple WeatherKit and add the optional microphone sleep tracking, Apple Health import and Apple Watch features described below.
- **Version 1.3.1 and earlier** use Open-Meteo for weather and do not ask for microphone or Apple Health access, and have no Apple Watch app.

## In short

CoolGuard has no accounts, no advertising, and no analytics or tracking SDKs. The developer runs no server for the app, and the app does not send your data to the developer automatically.

Most processing happens on your device. That does not mean no data ever leaves it: some features send data to Apple or another provider, as described below, and your device backups may include CoolGuard's data.

## Weather and location

**Weather in version 1.4 and later.** To show the weather, the app and its widget send your coordinates to Apple's WeatherKit service, including during background refreshes. CoolGuard requests low-accuracy location, but iOS decides the actual accuracy, and CoolGuard does not round the coordinates further. The latest forecast and its coordinates are also stored on your device. The app loads Apple's weather attribution logo from Apple. Apple's privacy policy applies to these requests.

**Weather in version 1.3.1 and earlier.** The app sends coordinates rounded to three decimal places, together with the requested weather values, to the Open-Meteo service (open-meteo.com). No account or CoolGuard identifier is included, but like any internet service, Open-Meteo can see the connection's details, such as the IP address. [Open-Meteo's terms and privacy information](https://open-meteo.com/en/terms) apply.

**Place names and maps.** When the app saves a Heat Log location, it asks Apple to convert the coordinates into a street and locality name, and stores the result on your device. The Heat Map uses Apple Maps. In version 1.4 and later, the forecast screen can also look up a place name through Apple.

**Country-dependent features (version 1.4 and later).** Some features, such as Smart Wake and snoring detection, are not available in every country. To decide this, the app uses your App Store country, your device's time zone and region, and the country of your weather location, which it looks up through Apple using the forecast coordinates. The result is stored on your device.

**Heat Log and Heat Map.** The Heat Log can save the date, the heat levels, the coordinates, the place name, and any notes and tags you add. It keeps up to 1,000 events on your device. Saving locations is on by default, and you can turn it off with "Save Location to the Log" in the Heat Log. With Heat Map (Background Monitoring) on and "Always" location access, the app receives low-accuracy location updates in the background. These also keep the monitoring running.

The Delete button in the Heat Log removes the logged events, including their coordinates, place names, notes and tags. It does not remove the hourly heat statistics (kept for up to 2 years) or the heat trend (kept for up to 7 days, and it may include the outdoor temperature). These contain no coordinates. They stay until they expire or you delete the app.

## Microphone (version 1.4 and later)

The app uses the microphone only during Sleep Tracking in Sleep Mode. Sleep Tracking is off by default. Choosing a Smart Wake window on an alarm can ask for microphone access and turn Sleep Tracking on, including for an alarm that the Apple Watch decides.

The sound is analysed in real time on your iPhone. CoolGuard does not save audio recordings and does not send audio anywhere.

The app does save the results on your device: the timing and strength of detected sounds, and per-minute values for movement, noise level, snoring (where available) and breathing rate and regularity. You can delete a night in the Sleep Log, and "Keep Sleep Log" controls how long nights are kept. Even with "Forever" selected, the app keeps at most 90 nights.

## Apple Health (version 1.4 and later)

Reading from Apple Health is optional and off by default. If you allow it, CoolGuard reads sleep analysis and heart rate data, which may come from any source that saves to Apple Health, such as a watch or a ring. CoolGuard writes nothing to Apple Health.

The data is used for the Sleep Log and to fine-tune the microphone-based estimate. The app copies the sleep stages and heart rate for a measured night into that night's file on your device. The app does not send this data to the developer, use it for advertising, or include it in the diagnostic logs described below, apart from the source's name and the number of samples.

Turning the Apple Health connection off stops further reading. Data already imported stays until you delete the night, it passes the "Keep Sleep Log" period, or you delete the app. You can withdraw the permission in the Health app.

## Apple Watch (version 1.4 and later)

The Watch app reads the watch's accelerometer for Smart Wake. If you set it up in the evening, it can ask watchOS to record motion for up to 12 hours, and it also reads motion live near the end of the alarm's window. The motion data is processed on the watch, and the app does not send raw motion data to the iPhone.

The iPhone and the watch exchange alarm times, days and window settings, status, wake-up and stop messages, and diagnostic lines through Apple's WatchConnectivity system. The Watch app does not itself access location or Apple Health, and contains no network requests of its own.

## Diagnostics and contacting the developer

**Logs on your device (version 1.4 and later).** The app keeps a rolling diagnostic log of about 300 KB and a sleep log for up to 30 days. These can include app and measurement events, alarm times and settings, battery level and charging state, the name of the Apple Health source, feature availability, and your App Store country, location country, time zone and region. They do not contain audio, heart rate values, coordinates or the text of alarm labels.

These logs are not sent automatically. "Share Log (for Troubleshooting)" in the Sleep Log hands them to the iOS share sheet, and you choose whether and where to send them.

**Feedback by email.** The Feedback option opens your own email app with a message that includes the app version, iOS version, device model and language. Nothing is sent until you send it. Anything you send by email reaches the developer through the email providers involved.

## Backups and storage

CoolGuard stores its data in its own storage on your device and shared with its widget. It has no iCloud sync of its own. However, it does not exclude its files from iOS device backups. If you use iCloud Backup or back up to a computer, the backup may therefore include your Heat Log with coordinates, your sleep data with imported heart rate and sleep stages, your settings and the diagnostic logs. Your backup settings and the provider of the backup determine how that copy is stored.

CoolGuard relies on the protection built into iOS and adds no encryption of its own.

Deleting the app removes its data from your device. It does not remove copies in backups you already made, or logs and emails you already sent.

## Other features

**Thermal state and battery.** The app reads the thermal level and battery information from iOS and processes them on your device. Battery health values you enter by hand also stay in the app's storage on your device.

**Notifications and alarms.** Notifications are created on your device, and the app uses no push server. Alarms are scheduled through iOS.

**Tips.** Voluntary tips are processed by Apple. The app does not receive your payment details.

**Product links.** The "Active cooling" screen links to an Amazon search for the Amazon marketplace matching your App Store country. Some of these links carry an affiliate tag, so the developer may earn a commission on qualifying purchases at no extra cost to you. Once a link is open, Amazon's privacy policy applies.

**Apple's statistics.** Apple gives developers aggregated App Store statistics, and may provide crash reports if you agreed to share them in your device settings. Apple runs this, not CoolGuard's code.

## What we do not do

- No advertising, analytics or tracking SDKs.
- No accounts.
- No sale of your data.
- No automatic transfer of your location history, audio or Apple Health data to the developer.

## Contact

If you have any questions about this policy: **norbert.p83@gmail.com**

---

# CoolGuard – Adatvédelmi nyilatkozat (Magyar)

_Utolsó frissítés: 2026. november 6._

Ez a nyilatkozat a CoolGuard iPhone-os változatára és az Apple Watch-appjára vonatkozik. Az androidos változatot nem írja le.

Az App Store-ban elérhető verzió és a funkciók eltérhetnek:

- **Az 1.4-es és újabb verziók** az Apple WeatherKitet használják, és lentebb leírt, választható funkcióként mikrofonos alvásmérést, Egészség-importot és Apple Watch-funkciókat kínálnak.
- **Az 1.3.1-es és régebbi verziók** az időjáráshoz az Open-Meteót használják, nem kérnek hozzáférést a mikrofonhoz és az Egészség apphoz, és nincs Apple Watch-appjuk.

## Röviden

A CoolGuardban nincs fiók, nincs reklám, és nincs benne analitikai vagy követő SDK. A fejlesztő nem üzemeltet szervert az apphoz, és az app nem küldi el automatikusan az adataidat a fejlesztőnek.

A feldolgozás nagy része a készülékeden történik. Ez nem jelenti azt, hogy soha semmilyen adat nem hagyja el a készüléket: egyes funkciók adatot küldenek az Apple-nek vagy más szolgáltatónak, ahogy lentebb olvasható, és a készülékmentéseid is tartalmazhatják a CoolGuard adatait.

## Időjárás és helyadatok

**Időjárás az 1.4-es és újabb verziókban.** Az időjárás megjelenítéséhez az app és a widget elküldi a koordinátáidat az Apple WeatherKit szolgáltatásának, a háttérben történő frissítéskor is. A CoolGuard alacsony pontosságú helyadatot kér, de a tényleges pontosságot az iOS határozza meg, és a CoolGuard nem kerekíti tovább a koordinátákat. A legutóbbi előrejelzés és a hozzá tartozó koordináták a készülékeden is tárolódnak. Az app az Apple időjárás-forrásjelző logóját az Apple-től tölti be. Ezekre a kérésekre az Apple adatvédelmi szabályzata vonatkozik.

**Időjárás az 1.3.1-es és régebbi verziókban.** Az app három tizedesre kerekített koordinátákat küld a kért időjárási értékekkel együtt az Open-Meteo szolgáltatásnak (open-meteo.com). A kérés nem tartalmaz fiókot vagy CoolGuard-azonosítót, de mint minden internetes szolgáltatás, az Open-Meteo is látja a kapcsolat adatait, például az IP-címet. Az [Open-Meteo feltételei és adatvédelmi tájékoztatója](https://open-meteo.com/en/terms) érvényesek rá.

**Helynevek és térkép.** Amikor az app helyszínt ment a Hőnaplóba, az Apple-től kéri a koordináták utca- és településnévvé alakítását, és az eredményt a készülékeden tárolja. A Hőtérkép az Apple Térképet használja. Az 1.4-es és újabb verziókban az előrejelzés képernyője is lekérdezhet helynevet az Apple-től.

**Országfüggő funkciók (1.4-es és újabb verziók).** Egyes funkciók, például az Okos ébresztés és a horkolás-felismerés, nem minden országban érhetők el. Ennek eldöntéséhez az app az App Store-országodat, a készülék időzónáját és régióját, valamint az időjárási helyed országát használja, amelyet az előrejelzés koordinátái alapján az Apple-től kérdez le. Az eredmény a készülékeden tárolódik.

**Hőnapló és Hőtérkép.** A Hőnapló mentheti a dátumot, a hőszinteket, a koordinátákat, a helynevet, valamint az általad megadott megjegyzéseket és címkéket. Legfeljebb 1000 eseményt tart meg a készülékeden. A helyszín mentése alapból be van kapcsolva, és a Hőnaplóban a „Helyszín mentése a naplóba” kapcsolóval kikapcsolható. Ha be van kapcsolva a Hőtérkép (háttérfigyelés), és „Mindig” helyhozzáférést adtál, az app a háttérben is kap alacsony pontosságú helyfrissítéseket. Ezek a figyelést is futásban tartják.

A Hőnapló Törlés gombja törli a naplózott eseményeket a koordinátáikkal, helynevükkel, megjegyzéseikkel és címkéikkel együtt. Nem törli az órás hőstatisztikát (legfeljebb 2 évig marad meg) és a hőtrendet (legfeljebb 7 napig marad meg, és tartalmazhatja a kinti hőmérsékletet). Ezekben nincs koordináta. Addig maradnak meg, amíg le nem járnak, vagy amíg nem törlöd az appot.

## Mikrofon (1.4-es és újabb verziók)

Az app csak Alvó módban, az alvásmérés alatt használja a mikrofont. Az alvásmérés alapból ki van kapcsolva. Ha egy ébresztőhöz okos keretet választasz, az app mikrofon-hozzáférést kérhet, és bekapcsolhatja az alvásmérést, akkor is, ha az ébresztésről az Apple Watch dönt.

A hangot az iPhone valós időben elemzi. A CoolGuard nem ment hangfelvételt, és nem küld hangot sehová.

Az eredményeket viszont a készülékeden tárolja: az észlelt hangok időzítését és erősségét, valamint a percenkénti mozgás-, zajszint- és (ahol elérhető) horkolásértékeket, továbbá a légzés ütemét és szabályosságát. Az Alvásnaplóban törölhetsz egy éjszakát, a megőrzési idő pedig „Az alvásnapló megőrzése” beállításnál adható meg. Az app a leghosszabb megőrzési beállítással is legfeljebb 90 éjszakát tart meg.

## Egészség app (1.4-es és újabb verziók)

Az Egészség appból való olvasás választható, és alapból ki van kapcsolva. Ha engedélyezed, a CoolGuard az alvásadatokat és a pulzust olvassa, amelyek bármilyen, az Egészség appba író forrásból származhatnak, például órától vagy gyűrűtől. A CoolGuard semmit nem ír az Egészség appba.

Az adatokat az Alvásnapló és a mikrofonos becslés pontosítása használja. Az app a mért éjszaka alvásfázisait és pulzusát az adott éjszaka fájljába másolja a készülékeden. Az app ezeket nem küldi el a fejlesztőnek, nem használja reklámcélra, és a lent leírt diagnosztikai naplókba is csak a forrás neve és a minták száma kerül.

Az Egészség-kapcsolat kikapcsolása után az app nem olvas tovább. A már importált adatok addig maradnak meg, amíg nem törlöd az éjszakát, le nem jár a megőrzési idő, vagy nem törlöd az appot. Az engedélyt az Egészség appban vonhatod vissza.

## Apple Watch (1.4-es és újabb verziók)

Az óra-app az Okos ébresztéshez az óra gyorsulásmérőjét olvassa. Ha este beállítod, a watchOS-től legfeljebb 12 órányi mozgásrögzítést kérhet, az ébresztési keret vége felé pedig élőben is olvassa a mozgást. A mozgásadatot az óra dolgozza fel, és az app nem küld nyers mozgásadatot az iPhone-ra.

Az iPhone és az óra az Apple WatchConnectivity rendszerén keresztül ébresztési időket, napokat és keretbeállításokat, állapotot, ébresztési és leállítási üzeneteket, valamint diagnosztikai sorokat cserél. Az óra-app önmagában nem fér hozzá a helyadatokhoz és az Egészség apphoz, és nem tartalmaz saját hálózati kérést.

## Diagnosztika és kapcsolatfelvétel

**Naplók a készüléken (1.4-es és újabb verziók).** Az app egy kb. 300 KB-os, folyamatosan felülíródó diagnosztikai naplót és legfeljebb 30 napos alvásnaplót vezet. Ezekbe bekerülhetnek az app és a mérés eseményei, az ébresztési idők és beállítások, az akkuszint és a töltési állapot, az Egészség-forrás neve, a funkciók elérhetősége, valamint az App Store-országod, a helyed országa, az időzónád és a régiód. Nem tartalmaznak hangot, pulzusértéket, koordinátát és az ébresztők címkéinek szövegét.

Ezek a naplók nem kerülnek automatikusan elküldésre. Az Alvásnapló „Napló megosztása (hibakereséshez)” gombja az iOS megosztási ablakát nyitja meg, és te döntöd el, hogy elküldöd-e, és kinek.

**Visszajelzés e-mailben.** A Visszajelzés funkció a saját levelezőappodat nyitja meg egy üzenettel, amely tartalmazza az app és az iOS verzióját, a készülék típusát és a nyelvet. Semmi nem megy el, amíg el nem küldöd. Amit e-mailben elküldesz, az az érintett levelezőszolgáltatókon keresztül jut el a fejlesztőhöz.

## Mentések és tárolás

A CoolGuard az adatait a saját, a widgetjével is megosztott tárhelyén tárolja a készülékeden. Nincs saját iCloud-szinkronja. A fájljait viszont nem zárja ki az iOS készülékmentéseiből. Ha iCloud-mentést vagy számítógépes mentést használsz, a mentésbe ezért bekerülhet a Hőnapló a koordinátákkal, az alvásadatok az importált pulzussal és alvásfázisokkal, a beállítások és a diagnosztikai naplók is. Hogy ez a másolat hogyan tárolódik, azt a mentési beállításaid és a mentés szolgáltatója határozza meg.

A CoolGuard az iOS beépített védelmére támaszkodik, saját titkosítást nem ad hozzá.

Az app törlése eltávolítja az adatokat a készülékedről. A már elkészült mentésekben lévő másolatokat, valamint a már elküldött naplókat és leveleket nem törli.

## További funkciók

**Hőállapot és akkumulátor.** Az app a hőszintet és az akkumulátoradatokat az iOS-től kapja, és a készülékeden dolgozza fel. A kézzel megadott akkuállapot-értékek szintén az app tárhelyén maradnak a készülékeden.

**Értesítések és ébresztők.** Az értesítések a készülékeden jönnek létre, az app nem használ push-szervert. Az ébresztőket az iOS-en keresztül ütemezi.

**Borravalók.** Az önkéntes borravalókat az Apple kezeli, az app nem kapja meg a fizetési adataidat.

**Termékajánlások.** Az „Aktív hűtés” képernyő az App Store-országodhoz illő Amazon-piactér keresési találataira mutat. A linkek egy része partnerazonosítót tartalmaz, így a fejlesztő jutalékot kaphat a minősített vásárlások után, neked többletköltség nélkül. A megnyitott linkre az Amazon adatvédelmi szabályzata vonatkozik.

**Az Apple statisztikái.** Az Apple összesített App Store-statisztikákat ad a fejlesztőknek, és összeomlási jelentéseket is adhat, ha a készülékeden hozzájárultál a megosztásukhoz. Ezt az Apple végzi, nem a CoolGuard kódja.

## Amit nem teszünk

- Nincs reklám, analitikai vagy követő SDK.
- Nincs fiók.
- Nem adjuk el az adataidat.
- Az app nem küldi el automatikusan a fejlesztőnek a helyelőzményeidet, a hangot vagy az Egészség-adataidat.

## Kapcsolat

Kérdés esetén: **norbert.p83@gmail.com**
