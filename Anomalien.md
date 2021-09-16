## Anomalien

Die [iban registry](https://www.swift.com/resource/iban-registry-pdf) listet Länder/Regionen und deren IBAN-Formate.

Hier eine Aufzählung der Anomalien nach IBAN-Prefix:
 
**_iban-Prefix_** | **_BIC Land_** | **_Anzahl_** | **_Bemerkung_**
--- | ------ | ------- | -------
DK  | `DK`	 | 3883 
DK  | FO	 | 4   | lt.swift hat Färöer den iban-Prefix FO, offenbar arbeiten 4 Banken mit DK-iban
DK  | GL	 | 3   | lt.swift hat Grönland den iban-Prefix GL, offenbar arbeiten 3 Banken mit DK-iban
FR  | `FR`  | 569 | SEPA country also includes GF, GP, MQ, YT, RE, PM, BL, MF
FR  | GF	 | 1   | lt.swift keine Anomalie
FR  | GP	 | 9   | lt.swift keine Anomalie
FR  | MQ	 | 4   | lt.swift keine Anomalie
FR  | RE	 | 7   | lt.swift keine Anomalie
FR  | PM	 | 2   | lt.swift keine Anomalie
FR  | NC	 | 9   | FR Country code includes other countries/territories
FR  | PF	 | 6   | FR Country code includes other countries/territories
FR  | WF	 | 1   | FR Country code includes other countries/territories
FR  | GB	 | 1   | ROYCGB22XXX
FR  | LU	 | 1   | HAVLLULLXXX
IT  | `IT`  | 835
IT  | CH	 | 1  | CRESCHZHXXX - CREDIT SUISSE AG,	SEDE DI MILANO
IT  | CZ	 | 1  | DEUTCZPXXXX - DEUTSCHE BANK AG, MILANO - warum CZ im BIC?
IT  | DE	 | 3
IT  | FR	 | 1  | CFFRFRPPXXX - CREDIT FONCIER DE FRANCE, TRIESTE
IT  | GB	 | 1  | BYLAGB22XXX - BAYERISCHE LANDESBANK, MILANO - warum GB im BIC?
IT  | SM	 | 10 | lt.swift hat San Marino den iban-Prefix SM, offenbar arbeiten 10 Banken mit IT-iban
KZ  | `KZ`  | 43 | non-SEPA Land Kazakhstan
KZ  | RU     | 2  | 
