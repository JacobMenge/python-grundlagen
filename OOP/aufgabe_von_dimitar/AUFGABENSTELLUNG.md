*@Aufgabenstellung von Dimitar Boyanov | 2. Juni*

# Python OOP

1. Definiert eine
Klasse, die "Konto" heißt.


2. Definiert die
drei Attributen "Kontoinhaber", "Kontonummer" und
"Kontostand", die durch den Konstruktor gesetzt werden.


3. Definiert eine
Methode, die "einzahlen" heißt. Die Methode muss ein Argument
"betrag" akzeptieren. Beim Aufruf von der Methode wird der Kontostand
entsprechend erhöht.


4. Definiert eine
Methode, die "auszahlen" heißt. Die Methode muss ein Argument
"betrag" akzeptieren. Beim Aufruf von der Methode wird der Kontostand
entsprechend reduziert. Bitte prüft, ob der Kontostand für die Auszahlung
reicht.


5. Definiert eine
Methode, die "ueberweisen" heißt. Die Methode muss 2 Argumente
akzeptieren - "zielkonto" und "betrag". Das Zielkonto wird
auch vom Type Konto sein. Setzt die Methode so um, dass der Kontostand mit dem
Betrag reduziert wird und der Kontostand vom "zielkonto" mit dem
Betrag erhöht wird. Schickt nachher True als Boolean zurück. Bitte prüft, ob
der Kontostand für die Überweisung ausreichend ist. Falls nicht fügt eine
Meldung hinzu, dass der Betrag nicht überwiesen werden konnte, da die Deckung
nicht genügend ist und schickt False zurück.


6. Definiert eine
neue Klasse, die "Sparkonto" heißt und von der Konto-Klasse ableitet.


7. Überschreibt
die Methode "auszahlen", sodass eine Auszahlung nur dann möglich
wäre, wenn das Datum gleich oder größer als 01.01.2024 ist.


8. Überschreibt
die Methode "ueberweisen", dass sie nicht erlaubt ist.


9. Definiert eine
neue Klasse "Kreditkonto", die einen aktiven Kredit bezeichnet und von
der Klasse "Konto" ableitet.


10. Überschreibt
die Methode "auszahlen, sodass eine Auszahlung nicht möglich ist.


11. Überschreibt
die Method "ueberweisen", sodass eine Überweisung nicht möglicht ist.