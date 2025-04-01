Calculator.java – 188 linija – Kod funkcioniše, ali postoje određene preporuke za poboljšanje:
- Fajl nije u imenovanom paketu
- Preporučuje se dodavanje privatnog konstruktora zbog statičke klase
- Metoda `toString` nije redefinisana
- Neka imena metoda ne prate konvenciju imenovanja u Javi (npr. veliko slovo na početku)
- Promenljiva `tempResult` je nepotrebna – može se direktno vratiti vrednost
- Jedan `return` je višak i može se ukloniti


Start.java – 26 linija – Kod je jednostavan i funkcionalan. SonarLint predlaže sledeće promene:
- Fajl nije u imenovanom paketu
- Promenljiva `Expression` bi trebalo da ima ime sa malim početnim slovom (npr. `expression`)
- Preporučuje se korišćenje logger-a umesto `System.out.println`, radi profesionalnijeg pristupa