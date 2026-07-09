# SWAT+ Wasserhaushaltsmodell

Dieses Repository enthält ein statisches Webtool für ein vereinfachtes, SWAT+-orientiertes Wasserhaushaltsmodell. Es läuft vollständig im Browser und benötigt keinen Server.

## Funktionen

- Eingabe zentraler Standort- und Modellparameter
- CSV-Import für Tageswerte
- SCS-Curve-Number-Oberflächenabfluss
- Bodenwasserspeicher, reale Evapotranspiration, lateraler Abfluss, Perkolation und Grundwasserbasisabfluss
- Schneespeicher und einfache Schneeschmelze
- Ergebniskennzahlen, Diagramme, Tabelle und CSV-Export
- optionale Gütemaße bei beobachtetem Abfluss: NSE, RMSE und PBIAS

## CSV-Format

```csv
date,p_mm,et0_mm,irrig_mm,tmean_c,q_obs_mm
2026-04-01,3.2,2.1,0,8,
2026-04-02,0,2.4,0,10,
2026-04-03,18,2.0,0,7,2.8
```

## Fachliche Einordnung

Das Tool ist keine offizielle SWAT+-Ausführung. Es bildet nur die wichtigsten Wasserhaushaltskomponenten in einer transparenten Tagesbilanz ab. Für belastbare SWAT+-Projekte sind SWAT+ Editor, QSWAT+, räumliche HRU-Diskretisierung, Managementdaten, Routing, Kalibrierung und Validierung notwendig.
