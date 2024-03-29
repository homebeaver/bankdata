## Anomalien

Die [iban registry](https://www.swift.com/resource/iban-registry-pdf) listet Länder/Regionen und deren IBAN-Formate.

Hier eine Aufzählung der Banken und Anomalien pro IBAN-Prefix:
 
**_iban-Prefix_** | **_BIC Land_** | **_Anzahl_** | **_Bemerkung_**
--- | :---:  | ---: | -------
AT  | `AT`	 | 874 
AT  | DE	 |   2 | FFBKDEFFAUT , TEAMDE71TAT
BE  | `BE`	 | 845
BE  | FR	 |	 1 | CPBIFRPPXXX
BE  | LU	 |	 1 | FETALULLBEL
CH  | `CH`	 | 1587
CH  | div    | 106 | viele auswärtige Banken, darunter 26 aus DE
CH  | LT	 |   1 | [`VIPULT22`](https://thebanks.eu/emis/via-payments-354733)
CH  | SE	 |   1 | [`ESSESESS`](https://thebanks.eu/banks/17570)
DK  | `DK`	 | 3883 
DK  | FO	 | 4   | lt.iban-registry hat Färöer den iban-Prefix FO, offenbar arbeiten 4 Banken mit DK-iban
DK  | GL	 | 3   | lt.iban-registry hat Grönland den iban-Prefix GL, offenbar arbeiten 3 Banken mit DK-iban
FR  | `FR`  | 569 | SEPA country also includes GF, GP, MQ, YT, RE, PM, BL, MF
FR  | GF	 | 1   | lt.iban-registry keine Anomalie
FR  | GP	 | 9   | lt.iban-registry keine Anomalie
FR  | MQ	 | 4   | lt.iban-registry keine Anomalie
FR  | RE	 | 7   | lt.iban-registry keine Anomalie
FR  | PM	 | 2   | lt.iban-registry keine Anomalie
FR  | NC	 | 9   | FR Country code includes other countries/territories
FR  | PF	 | 6   | FR Country code includes other countries/territories
FR  | WF	 | 1   | FR Country code includes other countries/territories
FR  | GB	 | 1   | [ROYCGB22XXX](https://thebanks.eu/banks/14413/bank_identifiers)
FR  | LU	 | 1   | HAVLLULLXXX - Banque Havilland
IE  | `IE`  | 1505
IE  | GB     | 613
IT  | `IT`  | 835
IT  | CH	 | 1  | CRESCHZHXXX - CREDIT SUISSE AG,	SEDE DI MILANO
IT  | CZ	 | 1  | DEUTCZPXXXX - DEUTSCHE BANK AG, MILANO - warum CZ im BIC?
IT  | DE	 | 3
IT  | FR	 | 1  | CFFRFRPPXXX - CREDIT FONCIER DE FRANCE, TRIESTE
IT  | GB	 | 1  | BYLAGB22XXX - BAYERISCHE LANDESBANK, MILANO - warum GB im BIC?
IT  | SM	 | 10 | lt.iban-registry hat San Marino den iban-Prefix SM, offenbar arbeiten 10 Banken mit IT-iban
SM  | `SM`	 | 76 | ... und es gibt 76 korrekte SM iban-Einträge
KZ  | `KZ`  | 43 | non-SEPA Land Kazakhstan
KZ  | RU     | 2  | 
PL  | `PL`  | 3109
PL  | null   | 25 | einige Institute haben keine BIC
SK  | `SK`  | 33
SK  | CZ     | 3
