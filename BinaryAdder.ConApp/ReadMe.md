# POSE

## POSE

### BinaryAdder, 3ABIF/3AKIF

Lehrziele

- Stringbearbeitung
- Methoden

#### Aufgabenstellung

Ihr Programm liest zwei (beliebig lange) Binärzahlen ein und addiert sie. Die Benutzerführung hat sich an der unten stehenden Vorgabe zu orientieren

![Illustration](Task.002.png)

Wird eine Fehleingabe gemacht, ist entsprechend zu reagieren:

![Illustration](Task.003.png)

**Hinweise:**

- Versuchen  Sie,  gleiche  Abläufe  in  Methoden  zu  strukturieren.  Das  Einlesen  einer  Dualzahl,  bis endlich eine korrekte Dualzahl eingegeben wurde, ist z.B. ein Fixkandidat für eine Methode, die für beide Dualzahlen verwendet werden kann.
- Die Addition wird einfacher, wenn zuvor beide Summanden auf gleiche Länge gebracht werden! Dazu muss der kürzere Summand mit führenden Nullen aufgefüllt werden.

**Erweiterungsoption:** Trennen Sie ganze Bytes bei der Ausgabe der Dualzahlen so, dass nach 8 Bits immer ein Leerzeichen folgt.

**Testvorgaben:**

|**Summand 1**  |**Summand 2**   |**Summe**       |
| -             | -              | -              |
|10101010101010 |101010101010101 |111111111111111 |
|1010           |111             |10001           |
|10110101       |10101           |11001010        |
|1010           |0               |1010            |

## Activity Diagrams

### Program.Main

![Program.Main](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_Main.puml)

### Program.FormatBinary

![Program.FormatBinary](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_FormatBinary.puml)

### Program.AddBinaryNumbers

![Program.AddBinaryNumbers](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_AddBinaryNumbers.puml)

### Program.ShrinkNumber

![Program.ShrinkNumber](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_ShrinkNumber.puml)

### Program.ExpandNumber

![Program.ExpandNumber](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_ExpandNumber.puml)

### Program.ReadBinaryNumber

![Program.ReadBinaryNumber](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_ReadBinaryNumber.puml)

### Program.CheckBinaryNumber

![Program.CheckBinaryNumber](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_CheckBinaryNumber.puml)

### Program.IsBinaryDigit

![Program.IsBinaryDigit](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/leoggehrer/2324-34_ABIF_ACIF_POSE/master/BinaryAdder.ConApp/diagrams/ac_Program_IsBinaryDigit.puml)
