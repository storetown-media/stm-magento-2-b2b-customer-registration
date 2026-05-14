<div align="center">

# 🔐 STM B2B Register für Magento 2

### B2B-Kundenfreischaltung mit Admin-Approval-Workflow

[![Commercial](https://img.shields.io/badge/License-Commercial%20Closed--Source-red?style=flat-square)](#license)
[![Magento](https://img.shields.io/badge/Magento-2.4.x-EE672F?style=flat-square&logo=magento)](#kompatibilit%C3%A4t)
[![PHP](https://img.shields.io/badge/PHP-8.1%E2%80%938.4-777BB4?style=flat-square&logo=php)](#kompatibilit%C3%A4t)
[![Hyvä](https://img.shields.io/badge/Hyv%C3%A4-Compatible-FF6B35?style=flat-square)](https://www.hyva.io/)
[![Reviews](https://img.shields.io/badge/Reviews-4.88%E2%98%85%20%2F%204-yellow?style=flat-square)](https://www.storetown-media.de/stm-b2b-register/)

[🛒 **Kaufen ab 149 €**](https://www.storetown-media.de/stm-b2b-register/) · [🎬 **Demo-Video**](https://www.youtube.com/watch?v=VVz76RxeBNw) · [🖥️ **Live-Demo**](https://magento2-shop.de/b2bregister/account/create/) · [📚 **Hub**](https://www.storetown-media.de/produkt-kategorie/downloads/magento-extensions/)

</div>

> ⚠️ **Commercial Closed-Source Extension.** Dieses Repository enthält Dokumentation und Pre-Sales-Informationen. Der Modul-Quellcode wird ausschließlich nach Kauf über die [Produktseite](https://www.storetown-media.de/stm-b2b-register/) oder den Adobe Commerce Marketplace ausgeliefert.

---

## Das Problem

B2B-Kunden brauchen einen anderen Registrierungsprozess als Endkunden. Firmendaten, Steuernummer, Ansprechpartner und Lieferadresse müssen bereits bei der Registrierung erfasst werden. Gleichzeitig darf **kein Geschäftskunde ohne Prüfung** auf B2B-Preise und -Konditionen zugreifen.

> Ohne eine professionelle Lösung verlieren Sie entweder potenzielle Kunden durch zu hohe Hürden — oder riskieren unkontrollierten Zugang zu Ihrem B2B-Bereich.

## Die Lösung

**STM B2B Register** liefert ein eigenes Registrierungsformular, das alle relevanten Geschäftsdaten erfasst. Der Admin prüft und schaltet frei, der Kunde erhält automatisch die richtige Kundengruppe und wird per E-Mail benachrichtigt. Drei Registrierungsmodi (B2B+B2C, Nur B2B, Nur B2C) decken alle Shop-Setups ab.

🎬 **Demo-Video ansehen:**

[![Demo-Video B2B Register](https://img.youtube.com/vi/VVz76RxeBNw/maxresdefault.jpg)](https://www.youtube.com/watch?v=VVz76RxeBNw)

## Features

- ✅ **Approval-Workflow** — Pending → Approved / Rejected, transparent für Admin und Kunde
- 📧 **E-Mail-Benachrichtigungen** — Registrierung, Admin-Hinweis, Freischaltung, Ablehnung
- 👥 **Kundengruppen-Automatik** — Automatische Zuweisung nach Freischaltung
- 🔄 **3 Registrierungsmodi** — Hybrid B2B+B2C · Nur B2B · Nur B2C
- 🎨 **Design & Felder konfigurierbar** — ColorPicker, Pflichtfeld-Steuerung, eigene Custom Fields
- 🛡️ **Login-Sperre** für nicht freigeschaltete Kunden + reCAPTCHA-Schutz
- 🌐 **7 Sprachen** — DE · EN · FR · ES · IT · NL · PL · PT
- 🔧 **Voll erweiterbar** — Service Interfaces, 6 Events, Plugin-fähig

## Zielgruppe

- B2B-Shops mit Händlerfreischaltung
- Großhandel
- Hybrid-Shops (B2B + B2C parallel)
- Hersteller mit Fachhändler-Portal
- Industriebedarf

## Use-Cases

- **Sanitär-Großhandel** mit Einkaufspreis-Schutz vor unautorisiertem Zugriff
- **Industriebedarf** mit Staffelpreisen und USt-ID-Prüfung
- **B2B-Portale für Fachhändler** mit automatischer Gruppenfreischaltung

## Pricing

| Edition | Für | Preis (inkl. 19 % MwSt.) |
|---|---|---|
| **Community** | Magento Open Source | **149,00 €** |
| **Enterprise** | Adobe Commerce | **299,00 €** |
| **Magento Cloud** | Adobe Commerce Cloud | **349,00 €** |

Alle Editionen: **One-Time Purchase** · 12 Monate Produktaktualisierungen · Pro-Support · **30 Tage Geld-zurück-Garantie**.

→ [**Jetzt kaufen**](https://www.storetown-media.de/stm-b2b-register/)

## Kompatibilität

| Anforderung | Details |
|---|---|
| **Magento** | 2.4.x (Open Source + Adobe Commerce + Cloud) |
| **PHP** | 8.1 · 8.2 · 8.3 · 8.4 |
| **Themes** | Hyvä · Luma · Porto · Ultimo |
| **Installation** | Composer (empfohlen) oder ZIP |

## Installation

> Composer-Installation funktioniert nach Kauf über den ausgelieferten Auth-Token / das ZIP-Paket. Eine öffentliche Packagist-Distribution ist für Q3/2026 geplant.

```bash
# Nach Kauf:
composer require storetown/module-b2b-register
bin/magento module:enable Storetown_B2BRegister
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento setup:static-content:deploy
bin/magento cache:flush
```

Alle Einstellungen anschließend unter **Stores → Configuration → STM → B2B Register**.

## Live ausprobieren

| | |
|---|---|
| **Frontend-Demo** | [magento2-shop.de/b2bregister/account/create/](https://magento2-shop.de/b2bregister/account/create/) |
| **Backend-Demo** | [Auto-Login](https://magento2-shop.de/demorole/autologin?token=demo2024stm) |
| **Demo-Video (1:49)** | [YouTube](https://www.youtube.com/watch?v=VVz76RxeBNw) |

## Support & Pre-Sales

- **Pre-Sales-Fragen:** Issue im [Issues-Tab](../../issues) eröffnen (Template „Pre-Sales Question")
- **Kunden-Support nach Kauf:** Über das Kunden-Konto auf storetown-media.de
- **Installation-Service:** Optional buchbar für 49 €
- **Email:** info@storetown-media.de

> Bitte **keine Bug-Reports oder Support-Anfragen** in GitHub-Issues. Diese werden hier nicht bearbeitet.

## Über Storetown-Media

Seit **2014** Magento-Spezialist im DACH-Raum. 12+ Jahre Praxis in Hyvä, Luma und Adobe Commerce. Mehr unter [storetown-media.de](https://www.storetown-media.de/) oder im [Org-Profil](https://github.com/storetown-media).

## License

**Proprietary / Commercial Closed-Source.** Siehe [LICENSE](LICENSE) sowie die [AGB von Storetown-Media](https://www.storetown-media.de/agb/).
