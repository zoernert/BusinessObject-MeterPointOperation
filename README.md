# StromDAO-BusinessObject - Messstellenbetrieb

Verwaltung und schreiben von Daten einer Messstelle (=Stromzähler) in der StromDAO Energy Blockchain. 

![Build Status](https://app.codeship.com/projects/0b53dce0-1501-0135-4829-1a2cb8d45999/status?branch=master) [![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/stromdao/BusinessObject)

## Verwendung
```
 stbo-mpo store meter_point_id value
 stbo-mpo retrieve meter_point_id
```

meter_point_id = Zählernummer

Jeder Messtelle wird auf Basis der angegebenen Meter_Point_Id eine eindeutige Adresse in der StromDAO Energy Blockchain zugewiesen. Diese Zuordnung erfoglt durch automatische Generierung eines Schlüsselpaares, welches lokal gespeichert wird. 
