# Ballon-d-Or-Netzwerk-Codebuch

edgelist

from

Definiert den Sender. Entspricht dem Spieler / der Spielerin codiert mit den Initialien und den letzten zwei Zahlen des Gebusrtsjahrs Beispiel: Ousmane Dembélé = OD97

to

Definiert den Empfänger. Entspricht den Vereinen codiert mit einer jeweiligen Abkürzung des Vereins.

Paris Saint-Germain = PSG

Stade Rennes = STRE

FC Barcelona = FCBC

FC Porto = FCP

FC Liverpool = FCL

FC Basel = FCBA

Vitória Guimarães SC = VGSC

FC Arsenal = FCA

FC Chelsea = FCC

Espanyol Barcelona = EB

relation

Definiert den Beziehungstyp zwischen Spieler / Spielerin und Verein:

played_at = Verein zum Zeitpunkt der Nominierung

trained_at = erster Profivertrag

rank

Definiert den Ballon d'Or-Rang von 1 bis 5. Nur relevant für "played_at".

platz = 1
patz = 2
platz = 3
platz = 4
platz = 5
year

Definiert das Ballon d’Or-Jahr der Nominierung. Nur relevant für "played_at". Abkürzung Ballon d'Or und Jahr der Nominierung = bdo2025 Notiz: Frauen erst ab 2018

nodelist

id

Definiert Name oder Bezeichnung des Knotens. Entspricht den ersten 2 Initialien des Spielers / der Spielerin und den letzten 2 Zahlen des Geburstsjahrs oder allgemeine Abgkürzung des Vereins

name

Entspricht ausgeschrieben dem Name des Spielers / der Spielerin oder des Verein mit Sonderzeichen, eindeutige Identifikation jedes einzelnen Knotens. Beispiele: Ousmane Dembélé, Vitória Guimarães SC

sex

Definiert das Geschlecht des Spielers / der Spielerin: male = 1 female = 2

nationality

Definiert die zugehörige Nationalität des Spielers/Spielerin oder des Vereins

DE = Deutschland

ES = Spanien

IT = Italien

FR = Frankreich

BRA= Brasilien

EGY = Ägypten

GB = Vereinigtes Königreich

PT = Portugal

SUI = Schweiz

AR = Argentinien

BE = Belgien

type

Definiert die Art des Knotens

Spieler / Spielerin = 1

Verein (club) = 2
