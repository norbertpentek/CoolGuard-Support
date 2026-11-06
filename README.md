# CoolGuard – Support

CoolGuard is an iOS app that helps you protect your phone's battery from heat. It shows your phone's current thermal level (Normal / Slightly warm / Hot / Critical), warns you when it's heating up, logs where your phone tends to overheat (Heat Map), and shows the outdoor temperature with a heat-risk forecast for the day.

## FAQ

**Why does CoolGuard ask for location access?**
Two reasons: (1) to fetch the weather (outdoor temperature) for where you are, and (2) with "Always" access, the Heat Map can record where your phone overheated, even in the background. The app does not send your location history to the developer, and Heat Map locations are stored on your device. However, your coordinates do go to the weather provider (Apple WeatherKit from version 1.4, Open-Meteo in version 1.3.1 and earlier), Apple receives them for place-name and country lookups, and device backups may include saved locations. See the [Privacy Policy](PRIVACY.md) for details.

**Why doesn't the widget update instantly?**
iOS refreshes Home Screen widgets on a system-managed schedule. For real-time updates, enable the Heat Map's live display – it shows the current level on the Lock Screen and Dynamic Island.

**The exact temperature isn't shown – why?**
iOS does not expose the phone's internal temperature to apps. Apple provides four official thermal levels, which is what CoolGuard displays.

## Contact

Questions, bug reports, suggestions: **norbert.p83@gmail.com**

---

# CoolGuard – Támogatás (Magyar)

A CoolGuard egy iOS-app, ami segít megvédeni a telefonod akkumulátorát a hőtől: mutatja az aktuális hőszintet, figyelmeztet melegedéskor, naplózza a melegedési helyszíneket (Hőtérkép), és a kinti hőmérséklet alapján előre jelzi a hőségveszélyt.

Kérdés, hibajelzés, javaslat: **norbert.p83@gmail.com**
