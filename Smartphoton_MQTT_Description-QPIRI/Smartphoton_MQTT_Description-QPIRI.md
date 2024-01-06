

|||||
| :- | :- | :- | :- |
|Description des Topic’s MQTT pour QPIRI|
|||||
|||||
|**QPIRI**|Description|Traduction Français|Notes|
|smartphoton/voltronic\_1/qpiri\_0|Grid rating voltage |Tension nominale du réseau |integer ranging from 0 to 9. The units is V |
|smartphoton/voltronic\_1/qpiri\_1|Grid rating current |Courant nominal du réseau |Integer ranging from 0 to 9. The units is A. |
|smartphoton/voltronic\_1/qpiri\_2|AC output rating voltage |Tension nominale de sortie AC |Integer ranging from 0 to 9. The units is V |
|smartphoton/voltronic\_1/qpiri\_3|AC output rating frequency |Fréquence nominale de la sortie AC |Integer ranging from 0 to 9. The units is Hz. |
|smartphoton/voltronic\_1/qpiri\_4|AC output rating current |Courant nominal de sortie AC |Integer ranging from 0 to 9. The unit is A. |
|smartphoton/voltronic\_1/qpiri\_5|AC output rating apparent power |Puissance apparente de la sortie AC |Integer ranging from 0 to 9. The unit is VA. |
|smartphoton/voltronic\_1/qpiri\_6|AC output rating active power |Puissance de sortie AC Puissance active |Integer ranging from 0 to 9. The unit is W. |
|smartphoton/voltronic\_1/qpiri\_7|Battery rating voltage |Tension nominale de la batterie |Integer ranging from 0 to 9. The units is V. |
|smartphoton/voltronic\_1/qpiri\_8|Battery re-charge voltage |Tension de recharge de la batterie |Integer ranging from 0 to 9. The units is V. |
|smartphoton/voltronic\_1/qpiri\_9|Battery under voltage |Sous-tension de la batterie |Integer ranging from 0 to 9. The units is V. |
|smartphoton/voltronic\_1/qpiri\_10|Battery bulk voltage |Tension de la batterie |Integer ranging from 0 to 9. The units is V |
|smartphoton/voltronic\_1/qpiri\_11|Battery float voltage |Tension de flottement de la batterie |Integer ranging from 0 to 9. The units is V. |
|smartphoton/voltronic\_1/qpiri\_12|Battery type |Type de batterie |0: AGM 1: Flooded 2: User |
|smartphoton/voltronic\_1/qpiri\_13|Current max AC charging current |Courant max. Courant de charge CA |P is an Integer ranging from 0 to 9 The units is A. |
|smartphoton/voltronic\_1/qpiri\_14|Current max charging current |Courant Courant de charge max. |Integer ranging from 0 to 9. The units is A. |
|smartphoton/voltronic\_1/qpiri\_15|Input voltage range |Plage de tension d'entrée |0: Appliance 1: UPS |
|smartphoton/voltronic\_1/qpiri\_16|Output source priority |Priorité à la source de sortie |0: Utility first 1: Solar first 2: SBU first |
|smartphoton/voltronic\_1/qpiri\_17|Charger source priority |Priorité à la source du chargeur |0: Utility first 1: Solar first 2: Solar + Utility 3: Only solar charging permitted |
|smartphoton/voltronic\_1/qpiri\_18|Parallel max number |Parallel max number |` `Integer ranging from 0 to 9 |
|smartphoton/voltronic\_1/qpiri\_19|Machine type |Type de machine |00: Grid tie; 01: Off Grid; 10: Hybrid. |
|smartphoton/voltronic\_1/qpiri\_20|Topology |Topologie |0: transformerless 1: transformer |
|smartphoton/voltronic\_1/qpiri\_21|Output mod |Modalité de sortie |00: single machine output 01: parallel output 02: Phase 1 of 3 Phase output 03: Phase 2 of 3 Phase output 04: Phase 3 of 3 Phase output |
|smartphoton/voltronic\_1/qpiri\_22|Battery re-discharge voltage |Tension de décharge de la batterie |Integer ranging from 0 to 9. The unit is V. |
|smartphoton/voltronic\_1/qpiri\_23|PV OK condition for parallel |PV Condition OK pour le parallèle |0: As long as one unit of inverters has connect PV, parallel system will consider PV OK; 1: Only All of inverters have connect PV, parallel system will consider PV OK |
|smartphoton/voltronic\_1/qpiri\_24|PV power balance |Bilan de puissance PV |0: PV input max current will be the max charged current; 1: PV input max power will be the sum of the max charged power and loads power. |
|smartphoton/voltronic\_1/qpiri\_25|Max. charging time at C.V stage |Temps de charge max. à l'étage C.V. |Integer ranging from 0 to 9. The unit is minute. (Only for PIP-MK |
|smartphoton/voltronic\_1/qpiri\_26|Operation Logic(For PIP-MK |Logique de fonctionnement (pour PIP-MK |0: Automatically 1: On-line mode 2: ECO mode (Only for PIP-MK) |


