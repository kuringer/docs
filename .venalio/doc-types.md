# Typy dokumentov (Diátaxis)

## 1. Prehľad funkcie (Feature Overview)
- **Účel**: Vysvetliť čo funkcia robí a prečo existuje
- **Štruktúra**: Čo to je > Ako to funguje (správanie) > Dôležité vedieť > Súvisiace funkcie
- **Pravidlá**: Popisuj správanie, nie implementáciu. Jeden koncept = jeden dokument.
- **Príklad**: "Kupóny" - čo sú, aké typy existujú, ako sa aplikujú na objednávku

## 2. Návod (How-to)
- **Účel**: Krok-za-krokom ako dosiahnuť konkrétny cieľ
- **Štruktúra**: Cieľ > Predpoklady > Kroky (číslované) > Overenie > Čo ak niečo nefunguje
- **Pravidlá**: Konkrétne kroky. Kde kliknúť. Čo vyplniť. Čo očakávať.
- **Príklad**: "Ako vytvoriť kupón s 10% zľavou na prvú objednávku"

## 3. Referencia (Reference)
- **Účel**: Kompletný prehľad nastavení, polí, možností
- **Štruktúra**: Tabuľka/zoznam s: Názov > Popis > Možné hodnoty > Predvolená hodnota
- **Pravidlá**: Vyčerpávajúca, nie výberová. Každé nastavenie musí byť popísané.
- **Príklad**: "Nastavenia dopravy - všetky polia a ich význam"

## Spoločné pravidlá
- Každý dokument má metadata: source_files, generated_at, venalio_version
- [VERIFY] tag pre čokoľvek čo nie je 100% odvoditeľné z kódu
- Placeholder pre screenshoty: `[SCREENSHOT: popis čo má screenshot ukazovať]`
- Cross-linky cez relatívne cesty, nie inline vysvetlenia
