# Bachelor Thesis

## Bestehend

Game Engine aus der Vorlesung *Game Engines*.

## Ziel

Erweiterung der Engine um eine Funktion, die Cloud Gaming ermöglicht.

Ein Server kann mehrere Instanzen des selben Spiels halten.
Ein Spieler verbindet sich zu diesem Server,
daraufhin wird für diesen Spieler eine neue Instanz des Spiels erstellt.
Der Server streamt Audio und Video zum Client.
Der Client streamt die Nutzereingaben zum Server.

## Ähnliche Projekte

[GeForce NOW](https://play.geforcenow.com),
[Amazon Luna](https://www.amazon.com/luna/landing-page),
[XBox Cloud Gaming](https://www.xbox.com/en-us/play),
[PlayStation Plus Cloud Gaming](https://blog.playstation.com/2023/10/11/ps5-cloud-streaming-launches-this-month-for-playstation-plus-premium-members/)

Diese Projekte bieten Cloud Gaming für unterschiedliche Spiele an.
Entwickler/Publisher brauchen einen Vertrag mit diesen Anbietern,
damit ihr Spiel dort verfügbar ist.

Wenn der Publisher das Spiel selbst mit einer Cloud Gaming Lösung anbieten kann,
sind diese unabhängig von den Großen Marken.

## C4 Model (unvollständig)

### Layer 1

![Engine](https://github.com/Frank-Mayer/bachelor-thesis/assets/53651857/f2b22740-67bb-4701-a17e-68c681c8a9c5)

### Layer 2

#### Client

![Client](https://github.com/Frank-Mayer/bachelor-thesis/assets/53651857/aae92136-3d03-4938-baf8-a42a2caa6828)

#### Game

![Game](https://github.com/Frank-Mayer/bachelor-thesis/assets/53651857/a767c112-1659-47bf-8d4b-68faf17411bb)
