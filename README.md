# Propojení aplikace phyphox a platformy arduino pro fyzikální pokusy na střední škole
Arduino skripty a phyphox konfigurace pro pokusy "Závislost intrenzity osvětlení na vzdálenosti od bodového zdroje světla" a "Závislost tlaku na teplotě při izochorickém ději".

Experimenty jsou popsány v Bákalářské práci:
"https://wstag.jcu.cz/StagPortletsJSR168/PagesDispatcherServlet?pp_destElement=%23ssSouboryStudentuDivId_6314&pp_locale=cs&pp_reqType=render&pp_portlet=souboryStudentuPagesPortlet&pp_page=souboryStudentuDownloadPage&pp_nameSpace=G237010&soubidno=367552"

Bakalářská práce slouží jako:
  1. návod na propojení Arduina a phyphox "hybridní" měření (data pochází z telefonu i arduina)
  2. návod na jednodušší propojení Arduina a phyphox použitelné pouze na "klasické měření" (data pochází pouze z Arduina)
  3. návod na provedení dvou jednoduchýh experimentů

Experimenty jsou navrženy pro Arduino UNO R4 wifi a ESP32 devkit v1.

Pro zprovoznění experimentů je třeba:
  1. nahrát vybraný .ino skript na Arduino/ESP32
  2. nahrát vybraný .phyphox file přímo do mobilního telefonu, alternativně nahrát do phyphox webového editoru a vytvořit QR kód pro nahrání
  3. Zapojit a sestavit experiment dle návodu v bakalářské práci
