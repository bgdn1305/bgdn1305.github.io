# Willkommen auf der ersten Seite

Hier sind einige gängige HTML-Elemente und ein Code-Beispiel.

### 1. Eine Überschrift
`<h1>Das ist eine Überschrift</h1>`

### 2. Ein Absatz
`<p>Dies ist ein einfacher Textabschnitt.</p>`

### 3. Eine Schaltfläche (Button)
`<button>Klick mich!</button>`

### 4. Code-Beispiel

```java
public class Main {
    public static void main(String[] args) {
        // 1. Thread definieren (was soll er tun?)
        Thread meinThread = new Thread(() -> {
            System.out.println("Thread läuft: " + Thread.currentThread().getName());
        });

        // 2. Thread starten
        meinThread.start();

        // Haupt-Thread läuft weiter
        System.out.println("Haupt-Programm läuft: " + Thread.currentThread().getName());
    }
}
```
---

## Navigation
Hier geht es zur [zweiten Seite](page2.html).
