# Stuhl kontrolliert Fernseher via Drucksensor
## Idee
Mein Fernseher/Dashboard soll angehen wenn ich mich an meinen Platz setze. Der Fernseher wird via [Switchbot](https://www.youtube.com/watch?v=BrtP_cZjAX0) angesteuert und am Stuhl ist ein Drucksensor an einem Fenstersensor angeschlossen. 
Als Server dient Home Assistant!
Inspiriert wurde das ganze von [Flotomation](https://www.youtube.com/c/Flotomation). Dankeschön!

In der Ausschaltautomation ist eine Bedingung für einen weiteren Sensor der erkennt ob ich am Tisch sitze oder stehe.

Alles weitere erkläre ich in diesem Video: https://youtu.be/YzVEAGddLZY

## Umsetzung
### Hardware
Der Drucksensor wird an die beiden Kontakte des Kontaktsensors angelötet. Kann Parallel zum Reedkontakt angeschlossen werden.
Der Sensor wird unter das Stuhlkissen gelegt und der Kontaktsensor an den Stuhl geklebt.
### Software
Zwei Home Assistant Automatisierungen die das Einschalten und Ausschalten steuern. Beide Yaml Dateien sind in diesem Projekt. Es müssen nur einige Stellen selbst ausgefüllt werden.
