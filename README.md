
# Inhaltsverzeichnis

- [Primitive Datentypen](#primitive-datentypen)
  - [Integer (int)](#integer-int)
  - [Float (float)](#float-float)
  - [String (str)](#string-str)
  - [Boolean (bool)](#boolean-bool)
  - [None](#none)
- [Arrays](#arrays)
- [Listen](#listen)
  - [Hinzufügen eines Elements zur Liste](#hinzufügen-eines-elements-zur-liste)
  - [Entfernen des Elements aus der Liste](#entfernen-des-elements-aus-der-liste)



# Primitive Datentypen

Primitive Datentypen in Python sind grundlegende Arten von Daten, mit denen wir arbeiten können. Stell dir sie wie verschiedene Arten von Bausteinen vor, die wir verwenden, um Informationen in unseren Programmen darzustellen.

In Python gibt es mehrere primitive Datentypen:

- [Integer (int)](#integer-int) -
Der Datentyp "Integer" repräsentiert ganze Zahlen ohne Dezimalstellen. Wir können ihn verwenden, um zum Beispiel das Alter einer Person oder die Anzahl der Bücher in einer Bibliothek darzustellen.

- [Float (float)](#float-float) -
Der Datentyp "Float" repräsentiert Zahlen mit Dezimalstellen, also Kommazahlen. Damit können wir zum Beispiel Gewicht, Größe oder Temperatur mit hoher Genauigkeit darstellen.

- [String (str)](#string-str) - Der Datentyp "String" repräsentiert Zeichenketten oder Text. Wir können damit Namen, Sätze oder beliebigen Text speichern und verarbeiten.

- [Boolean (bool)](#boolean-bool) - Der Datentyp "Boolean" repräsentiert Wahrheitswerte. Er kann entweder "True" (wahr) oder "False" (falsch) sein. Wir verwenden ihn oft für bedingte Aussagen und logische Operationen.

- [None](#none) - Der Datentyp "None" repräsentiert das Fehlen eines Werts. Er wird verwendet, wenn wir noch keinen Wert haben oder eine Variable leer ist.

Diese primitiven Datentypen ermöglichen es uns, verschiedene Arten von Daten in unseren Programmen darzustellen und mit ihnen zu arbeiten. Indem wir die passenden Datentypen verwenden, können wir sicherstellen, dass unsere Daten korrekt und effizient verarbeitet werden.


## Integer (int)

Die Verwendung des Datentyps Integer ermöglicht es uns, mit ganzen Zahlen zu arbeiten und sie in unseren Programmen zu verwenden.

- [integer_bsp.py](./primitive-datentypen/interger_bsp.py)
- Darstellung ganzer Zahlen ohne Dezimalstellen
- Beispiele: -5, 0, 42

In diesem Beispiel wird der Wert 25 verwendet, aber du kannst den Wert der Variable `age` ändern und das Programm wird den neuen Wert anzeigen.
`````
# Beispiel für Integer (int):
age: int = 25
print("Das Alter beträgt:", age)
`````
In diesem Codebeispiel wird der Datentyp Integer (ganze Zahl) in Python verwendet. Es wird eine Variable `age` erstellt und mit dem Wert 25 initialisiert. Die ": int" am Ende der Zeile gibt an, dass der Datentyp der Variable `age` ein Integer ist. Danach wird der Befehl `print()` verwendet, um eine Nachricht auszugeben. In diesem Fall wird die Nachricht "Das Alter beträgt:" zusammen mit dem Wert der Variable `age` auf dem Bildschirm angezeigt. Der Wert von "age" wird dabei automatisch in die Nachricht eingefügt.

Das bedeutet, dass die Ausgabe des Programms folgendermaßen aussieht:
"Das Alter beträgt: 25"


<a name="float-float"></a>
## Float (float)

Die Verwendung des Datentyps Float ermöglicht es uns, mit Dezimalzahlen zu arbeiten und sie in unseren Programmen zu verwenden. 

- [float_bsp.py](./primitive-datentypen/float_bsp.py)
- Darstellung von Zahlen mit Dezimalstellen
- Beispiele: 3.14, -0.5, 1.0

In diesem Beispiel wird der Wert 3.14 verwendet, aber du kannst den Wert der Variable `pi` ändern und das Programm wird den neuen Wert anzeigen.
`````
# Beispiel für Float (float):
pi: float = 3.14
print("Der Wert von Pi ist:", pi)
`````
In diesem Codebeispiel wird der Datentyp Float (Dezimalzahl) in Python verwendet. Es wird eine Variable `pi` erstellt und mit dem Wert 3.14 initialisiert. Die `: float` am Ende der Zeile gibt an, dass der Datentyp der Variable `pi` ein Float ist, also eine Dezimalzahl. Danach wird der Befehl `print()` verwendet, um eine Nachricht auszugeben. In diesem Fall wird die Nachricht "Der Wert von Pi ist:" zusammen mit dem Wert der Variable `pi` auf dem Bildschirm angezeigt. Der Wert von `pi` wird dabei automatisch in die Nachricht eingefügt.

Das bedeutet, dass die Ausgabe des Programms folgendermaßen aussieht:
"Der Wert von Pi ist: 3.14"



## String (str)

- [string_bsp.py](./primitive-datentypen/string_bsp.py)
- Darstellung von Zeichenketten oder Text
- Beispiele: "Hallo", 'Welt', "123"

Die Verwendung des Datentyps String ermöglicht es uns, mit Text oder Zeichenketten zu arbeiten und sie in unseren Programmen zu verwenden. In diesem Beispiel wird der Name "John Doe" verwendet, aber du kannst den Wert der Variable "name" ändern und das Programm wird den neuen Wert anzeigen.
`````
# Beispiel für String (str):
name: str = "John Doe"
print("Der Name ist:", name)
`````
In diesem Codebeispiel wird der Datentyp String (Zeichenkette) in Python verwendet. Es wird eine Variable `name` erstellt und mit dem Wert "John Doe" initialisiert. Die ": str" am Ende der Zeile gibt an, dass der Datentyp der Variable `name` ein String ist, also eine Zeichenkette. Danach wird der Befehl `print()` verwendet, um eine Nachricht auszugeben. In diesem Fall wird die Nachricht "Der Name ist:" zusammen mit dem Wert der Variable `name` auf dem Bildschirm angezeigt. Der Wert von "name" wird dabei automatisch in die Nachricht eingefügt.

Das bedeutet, dass die Ausgabe des Programms folgendermaßen aussieht:
"Der Name ist: John Doe"

## Boolean (bool)

- [boolean_bsp.py](./primitive-datentypen/boolean_bsp.py)
- Darstellung von Wahrheitswerten (True oder False).
- Beispiele: True, False

Die Verwendung des Datentyps Boolean ermöglicht es uns, Wahrheitswerte in unseren Programmen zu verwenden. In diesem Beispiel wird der Wert True verwendet, um anzuzeigen, dass es regnet. Du kannst den Wert der Variable `is_raining` auf False setzen, um anzuzeigen, dass es nicht regnet, und das Programm wird den neuen Wert entsprechend anzeigen.
`````
# Beispiel für Boolean (bool):
is_raining: bool = True
print("Regnet es?", is_raining)
`````
In diesem Codebeispiel wird der Datentyp Boolean (Wahrheitswert) in Python verwendet. Es wird eine Variable `is_raining` erstellt und mit dem Wert True initialisiert. Die `: bool` am Ende der Zeile gibt an, dass der Datentyp der Variable `is_raining` ein Boolean ist, also entweder wahr (True) oder falsch (False). Danach wird der Befehl `print()` verwendet, um eine Nachricht auszugeben. In diesem Fall wird die Frage "Regnet es?" zusammen mit dem Wert der Variable `is_raining` auf dem Bildschirm angezeigt. Der Wert von `is_raining` wird dabei automatisch in die Nachricht eingefügt.

Das bedeutet, dass die Ausgabe des Programms folgendermaßen aussieht:
"Regnet es? True"

## Complex (complex)

- [complex_bsp.py](./primitive-datentypen/complex_bsp.py)
- Darstellung von komplexen Zahlen
- Beispiele: 2 + 3j, -1 + 2j

Die Verwendung des Datentyps Complex ermöglicht es uns, mit komplexen Zahlen zu arbeiten und sie in unseren Programmen zu verwenden. In diesem Beispiel wird die komplexe Zahl `2 + 3j` verwendet, aber du kannst den Wert der Variable `z` ändern und das Programm wird den neuen Wert anzeigen.

`````
# Beispiel für Complex (complex):
z: complex = 2 + 3j
print("Die komplexe Zahl ist:", z)
`````
In diesem Codebeispiel wird der Datentyp Complex (komplexe Zahl) in Python verwendet. Es wird eine Variable `z` erstellt und mit dem Wert `2 + 3j` initialisiert. Das `: complex` am Ende der Zeile gibt an, dass der Datentyp der Variable `z` eine komplexe Zahl ist. Eine komplexe Zahl besteht aus zwei Teilen: dem Realteil und dem Imaginärteil. Im Codebeispiel ist der Realteil `2` und der Imaginärteil `3j`, wobei `j` die imaginäre Einheit darstellt. Danach wird der Befehl `print()` verwendet, um eine Nachricht auszugeben. In diesem Fall wird die Nachricht `Die komplexe Zahl ist:` zusammen mit dem Wert der Variable `z` auf dem Bildschirm angezeigt. Der Wert von `z` wird dabei automatisch in die Nachricht eingefügt.

Das bedeutet, dass die Ausgabe des Programms folgendermaßen aussieht:
"Die komplexe Zahl ist: (2+3j)"

## None

- [none_bsp.py](./primitive-datentypen/none_bsp.py)
- Ein spezieller Datentyp, der das Fehlen eines Wertes oder eine leere Variable darstellt
- Beispiel: None

Die Verwendung des Werts None ermöglicht es uns, anzugeben, dass eine Variable leer ist oder keinen bestimmten Wert enthält. In diesem Beispiel wird der Wert der Variable `value` explizit auf None gesetzt, aber du kannst den Wert ändern und das Programm wird den neuen Wert entsprechend anzeigen.
`````
# Beispiel für None:
value: None = None
print("Der Wert ist:", value)
`````
In diesem Codebeispiel wird der spezielle Wert None in Python verwendet. Es wird eine Variable `value` erstellt und mit dem Wert None initialisiert. None wird verwendet, um anzuzeigen, dass die Variable keinen bestimmten Wert enthält. Danach wird der Befehl `print()` verwendet, um eine Nachricht auszugeben. In diesem Fall wird die Nachricht "Der Wert ist:" zusammen mit dem Wert der Variable `value` auf dem Bildschirm angezeigt. Da der Wert von "value" None ist, wird dies entsprechend in der Nachricht angezeigt.

Das bedeutet, dass die Ausgabe des Programms folgendermaßen aussieht:
"Der Wert ist: None"

# Arrays

- [arrays_bsp.py](./arrays/arrays_bsp.py)
- Arrays sind spezielle Datenstrukturen, welche eine festgelegte Größe haben
- Elemente in einem Array sind in einer festen Reihenfolge angeordnet und können durch Indizes abgerufen werden

Ein Array ist eine Datenstruktur, die es uns ermöglicht, eine Sammlung von Werten in einer einzigen Variable zu speichern. Stell dir das Array vor wie eine Reihe von Behältern, in denen wir verschiedene Dinge aufbewahren können.

![Alt-Text](/img/array.png)

Jeder Behälter im Array hat eine bestimmte Position, die wir mit einer Zahl, dem sogenannten Index, identifizieren. Der Index beginnt in den meisten Programmiersprachen bei 0. Das heißt, der erste Behälter hat den Index 0, der zweite Behälter den Index 1, der dritte den Index 2 und so weiter. Wir können Werte in die Behälter des Arrays legen, indem wir sie anhand ihres Indexes ansprechen. Wenn wir beispielsweise das Element an Position 2 des Arrays abrufen möchten, verwenden wir den Index 2. Jedes Element im Array hat also eine eindeutige Position, die wir verwenden können, um auf den entsprechenden Wert zuzugreifen.

`````
# Beispiel für Array:
integer_array = [2, 3, 5, 7, 11, 13, 17]
print(integer_array[0])
print(integer_array[2])
`````
In diesem Codebeispiel wird ein Array in Python verwendet. Ein Array ist eine Datenstruktur, die es uns ermöglicht, mehrere Werte in einer einzigen Variablen zu speichern. In diesem Fall wird ein Array mit ganzzahligen Werten erstellt. Das Array `integer_array` enthält die Zahlen 2, 3, 5, 7, 11, 13 und 17. Jede Zahl wird durch ein Komma getrennt und in eckige Klammern eingeschlossen.

Der Code verwendet den Indexoperator `[]`, um auf die einzelnen Elemente des Arrays zuzugreifen. Der Index beginnt bei 0, sodass `integer_array[0]` das erste Element (2) und `integer_array[2]` das dritte Element (5) des Arrays zurückgibt.

Die Ausgabe des Programms sieht folgendermaßen aus:
`````
2
5
`````
Das bedeutet, dass die erste Zeile "2" und die zweite Zeile "5" auf dem Bildschirm ausgibt. Der Code zeigt, wie man auf bestimmte Elemente in einem Array zugreift, indem man den Index verwendet. Du kannst den Index ändern, um auf andere Elemente des Arrays zuzugreifen und das Programm wird den entsprechenden Wert anzeigen.

# Listen

- [listen_bsp.py](./listen/listen_bsp.py)
- Flexible Datenstruktur für unterschiedliche Datentypen
- Listen können verändert werden und ermöglichen das Hinzufügen, Entfernen und Ändern von Elementen
- Elemente in einer Liste sind in einer festen Reihenfolge angeordnet und können durch Indizes abgerufen werden

Eine Liste in Python ist eine Datenstruktur, mit der wir eine geordnete Sammlung von Elementen speichern können. Stelle dir die Liste wie eine Einkaufsliste vor, auf der du verschiedene Dinge notierst. In Python können wir unterschiedliche Arten von Elementen in einer Liste speichern, wie zum Beispiel Zahlen, Texte, Wahrheitswerte und vieles mehr. Listen sind im Gegensatz zu Arrays sehr flexibel, da wir Elemente hinzufügen und entfernen können.

![Alt-Text](/img/liste.png)

Jedes Element in der Liste hat eine bestimmte Position, die wir mit Hilfe des Index identifizieren. Der Index beginnt in Python bei 0, was bedeutet, dass das erste Element den Index 0 hat, das zweite den Index 1, das dritte den Index 2 und so weiter. Wir können auf die Elemente in der Liste zugreifen, indem wir den Index verwenden. Wenn wir beispielsweise das erste Element abrufen möchten, verwenden wir den Index 0. Wenn wir das zweite Element möchten, verwenden wir den Index 1 und so weiter. 
`````
# Beispiel für Liste:
my_list = [23, "Techstarter", 3.14, True, None, None, None]
print(my_list[0])
print(my_list[1])
`````
In der Liste `my_list` sind verschiedene Elemente enthalten. Es gibt eine Zahl `23`, einen Text `Techstarter`, eine Dezimalzahl `3.14`, einen Wahrheitswert `True` und einige None-Werte. Jedes Element wird durch ein Komma getrennt und in eckige Klammern eingeschlossen. Der Code verwendet den Indexoperator `[]`, um auf die einzelnen Elemente der Liste zuzugreifen. Der Index beginnt bei 0, sodass `my_list[0]` das erste Element `23` und `my_list[1]` das zweite Element ("Techstarter") der Liste zurückgibt.

Die Ausgabe des Programms sieht folgendermaßen aus:
`````
23
Techstarter
`````
Das bedeutet, dass die erste Zeile `23` und die zweite Zeile `Techstarter` auf dem Bildschirm ausgibt. Der Code zeigt, wie man auf bestimmte Elemente in einer Liste zugreift, indem man den Index verwendet. Du kannst den Index ändern, um auf andere Elemente der Liste zuzugreifen, und das Programm wird den entsprechenden Wert anzeigen.

## Hinzufügen eines Elements zur Liste

In diesem Codebeispiel wird ein Element zu einer Liste in Python hinzugefügt. Die Liste, auf die das Element hinzugefügt wird, wird als `my_list` bezeichnet.
`````
# Hinzufügen eines Elements zur Liste
my_list.append("Moin!")
`````
Der Befehl `append()` wird verwendet, um ein Element am Ende der Liste hinzuzufügen. In diesem Fall wird das Element `Moin!` zur Liste hinzugefügt.

Das bedeutet, dass die Liste nach Ausführung des Codes ein zusätzliches Element enthält. Das Element `Moin!` wird am Ende der Liste platziert.

Beispiel vor der Ausführung des Codes:
`````
[23, "Techstarter", 3.14, True, None, None, None]
`````
Beispiel nach der Ausführung des Codes:
`````
[23, "Techstarter", 3.14, True, None, None, None, "Moin!"]
`````
Die Verwendung von `append()` ermöglicht es uns, neue Elemente zur Liste hinzuzufügen und die Liste dynamisch zu erweitern.

![Alt-Text](/img/listehinzu.png)

## Entfernen des Elements aus der Liste

In diesem Codebeispiel wird ein Element aus einer Liste in Python entfernt. Die Liste, aus der das Element entfernt wird, wird als `my_list` bezeichnet.
`````
# Entfernen des Elements aus der Liste
removed_element = my_list.pop(7)
`````
Der Befehl `pop()` wird verwendet, um ein Element aus der Liste zu entfernen. In diesem Fall wird das Element an der Position 7 entfernt. Der Index 7 gibt an, dass das achte Element der Liste entfernt wird. Beachte, dass der Index bei 0 beginnt, also das erste Element den Index 0 hat, das zweite den Index 1 und so weiter.


Beispiel vor der Ausführung des Codes:
`````
[23, "Techstarter", 3.14, True, None, None, None, "Moin!"]
`````
Beispiel nach der Ausführung des Codes:
`````
[23, "Techstarter", 3.14, True, None, None, None]
`````
