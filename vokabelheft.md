# Vokabelheft für Datentypen und Operatoren in Dart

## Datentypen
| Datentyp       | Beschreibung                           | Beispiel 1                 | Beispiel 2                   |
|----------------|----------------------------------------|----------------------------|------------------------------|
| `int`          | Ganzzahl                               | `int x = 5;`               | `int y = -3;`                |
| `double`       | Gleitkommazahl                         | `double x = 3.14;`         | `double y = -2.7;`           |
| `String`       | Zeichenkette                           | `String x = "Hallo";`      | `String y = 'Welt';`         |
| `bool`         | Wahrheitswert                          | `bool x = true;`           | `bool y = false;`            |
| `List`         | Liste                                  | `List<int> x = [1, 2, 3];` | `List<String> y = ['a', 'b', 'c'];` |
| `Map`          | Wörterbuch                             | `Map<String, int> x = {"a": 1, "b": 2};` | `Map<String, String> y = {"name": "John"};` |
| `Set`          | Menge                                  | `Set<int> x = {1, 2, 3};`  | `Set<String> y = {'a', 'b', 'c'};`          |

## Arithmetische Operatoren
| Operator       | Beschreibung                            | Beispiel 1                          | Beispiel 2                          |
|----------------|----------------------------------------|-------------------------------------|-------------------------------------|
| `+`            | Addition                                | `int x = 5 + 3;`                    | `double y = 2.5 + 4.1;`             |
| `-`            | Subtraktion                             | `int x = 5 - 3;`                    | `double y = 4.1 - 2.5;`             |
| `*`            | Multiplikation                          | `int x = 5 * 3;`                    | `double y = 2.5 * 4;`               |
| `/`            | Division                                | `double x = 10 / 2;`                | `double y = 7.5 / 2.5;`             |
| `%`            | Modulo (Rest)                           | `int x = 10 % 3;`                   | `int y = 9 % 4;`                    |
| `~`            | Ganzzahl-Division                       | `int x = 10 ~/ 3;`                  | `int y = 7 ~/ 2;`                   |

## Relationale Operatoren
| Operator       | Beschreibung                            | Beispiel 1                          | Beispiel 2                          |
|----------------|----------------------------------------|-------------------------------------|-------------------------------------|
| `==`           | Gleichheit                              | `bool x = (5 == 5);`                | `bool y = (x == y);`                |
| `!=`           | Ungleichheit                            | `bool x = (5 != 3);`                | `bool y = (x != y);`                |
| `>`            | Größer als                              | `bool x = (5 > 3);`                 | `bool y = (x > y);`                 |
| `<`            | Kleiner als                             | `bool x = (3 < 5);`                 | `bool y = (x < y);`                 |
| `>=`           | Größer oder gleich                      | `bool x = (5 >= 3);`                | `bool y = (x >= y);`                |
| `<=`           | Kleiner oder gleich                     | `bool x = (3 <= 5);`                | `bool y = (x <= y);`                |

## Logische Operatoren
| Operator       | Beschreibung                            | Beispiel 1                          | Beispiel 2                          |
|----------------|----------------------------------------|-------------------------------------|-------------------------------------|
| `&&`           | Logisches UND                           | `bool x = (true && false);`         | `bool y = (x && y);`                |
| `||`           | Logisches ODER                          | `bool x = (true || false);`         | `bool y = (x || y);`                |
| `!`            | Logische Negation                       | `bool x = !(true);`                 | `bool y = !x;`                      |
