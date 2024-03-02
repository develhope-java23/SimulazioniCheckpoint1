# Traccia 1
Implementare getter, setter, costruttori e metodi aggiuntivi oltre quelli richiesti dove ritenuto necessario.

1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMinimum(): Prende in input un array di interi e restituisce il minimo
- hasPositive(): Prende in input un array di interi e restituisce true se almeno un elemento è positivo, false altrimenti
- isAllNegative(): Prende in input un array di double e restituisce true se tutti gli elementi sono strettamente minori di 0, false altrimenti

2. Implementare una classe Student definita dai seguenti attributi:
- name: String
- bestMark: double
  
3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Student.
- Viene creato un array di interi contenente le lunghezze dei nomi degli studenti
- Viene creato un array di double contenente il miglior voto di ogni studente
- Vengono chiamati i metodi scritti al punto 1 negli array appena creati ed il risultato viene stampato a schermo

# Traccia 2
Implementare getter, setter, costruttori e metodi aggiuntivi oltre quelli richiesti dove ritenuto necessario.

1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMaximum(): Prende in input un array di interi e restituisce il massimo
- hasZero(): Prende in input un array di interi e restituisce true se almeno un elemento è zero, false altrimenti
- hasGreaterThan5(): Prende in input un array di float e restituisce true se almeno un elemento è più grande di 5, false altrimenti

2. Implementare una classe Product definita dai seguenti attributi:
- name: String
- quantity: int
- price: float

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Product.
- Viene creato un array di interi contenente le quantità dei prodotti
- Viene creato un array di float contenente il prezzo di ogni prodotto se maggiore di 0.5, altrimenti lo sostituisce con 0.0
- Vengono chiamati i metodi scritti al punto 1 negli array appena creati ed il risultato viene stampato a schermo

# Traccia 3
1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMaxLength(): Prende in input un array di stringhe e restituisce la lunghezza massima
- getOddMax(): Prende in input un array di interi e restituisce il massimo fra i numeri dispari presenti in esso
- hasEvenInOddIndex(): Prende in input un array di float e restituisce true se è presente almeno un elemento dal valore pari in un indice dispari, false altrimenti

2. Implementare una classe Student definita dai seguenti attributi:
- name: String
- marks: float[]

Implementare getter, setter e costruttore ed un metodo addMark(float) che aggiunge un valore a marks, inizialmente allocato come un array con valori 0 la cui lunghezza è passata al costruttore.

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Student
- Viene creato un array di stringhe contenente i nomi degli studenti
- Viene creato un array di interi contenente le lunghezze dei nomi degli studenti
- Viene creato un array di float contenente le medie dei voti di ogni studente
- Vengono chiamati i metodi scritti al punto 1 negli array appena creati ed il risultato viene stampato a schermo
 
# Traccia 4
1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMinOddLength(): Prende in input un array di stringhe e restituisce la minima fra le lunghezze dispari
- getOddMinMaxSum(): Prende in input un array di interi e restituisce la somma del minimo e del massimo fra i numeri dispari presenti in esso
- getMaxEvenIndex(): Prende in input un array di interi e restituisce l'indice del massimo elemento pari 

2. Implementare una classe Supermarket definita dai seguenti attributi:
- name: String
- averagePrice: double

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Supermarket
- Viene creato un array di stringhe contenente i nomi dei supermercati
- Viene creato un array di interi contenente i prezzi medi dei supermercati, trasformati in interi
- Vengono chiamati i metodi scritti al punto 1 negli array appena creati ed il risultato viene stampato a schermo

# Traccia 5
1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMinIndex(): Prende in input un array di interi e restituisce l'indice del minimo
- getMeanLength(): Prende in input un array di stringhe e restituisce la media delle loro lunghezze
- getMaxDivisibleBy(): Prende in input un array di long ed un parametro "k" e restituisce il massimo elemento divisibile per k 

2. Implementare una classe WarehouseProduct definita dai seguenti attributi:
- name: String
- quantity: int

La variabile "quantity"  viene inizializzata venendo passata al costruttore, ma se il parametro passato è minore di 0 essa viene inizializzata a 0.
Aggiungere un metodo isOutOfStock() che ritorna true se e solo se quantity ha valore uguale a 0.

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti WarehouseProduct
- Viene creato un array di interi contenenti le quantità dei prodotti
- Vengono chiamati i metodi scritti al punto 1 negli array appena creati ed il risultato viene stampato a schermo

# Traccia 6
1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMaxIndex(): Prende in input un array di interi e restituisce l'indice del massimo
- getMean(): Prende in input un array di double e restituisce la media dei valori
- getMaxDivisibleBy5(): Prende in input un array di int e restituisce il massimo elemento divisibile per 5 

2. Implementare una classe Student definita dai seguenti attributi:
- name: String
- bestMark: double
- attendedCourses: int

I seguenti vincoli vanno implementati quando si modificano i valori delle variabili d'istanza nel costruttore e nei setter:
- Il valore di bestMark deve essere compresso fra 0.0 e 5.0
- Il valore di attendedCourses non può essere minore di 0

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Student
- Viene creato un array di double contenente tutti i migliori voti degli studenti maggiori di 3.0
- Viene creato un array di interi contenente tutti i numeri di corsi seguiti dagli studenti
- Vengono chiamati i metodi scritti al punto 1 negli array appena creati ed il risultato viene stampato a schermo

# Traccia 7
1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMinLengthInEvenIndex(): Prende in input un array di stringhe e restituisce la minima lunghezza di una stringa presente in un'indice pari
- getMaxLengthIndex(): Prende in input un array di stringhe e restituisce l'indice della stringa con la massima lunghezza
- getElementWithMinLengthSmallerThan(): Prende in input un array di stringhe ed un parametro "k" e restituisce la stringa più corta fra quelle più corte di "k" caratteri 

2. Implementare una classe Student definita dai seguenti attributi:
- name: String
- averageMark: float

Il campo averageMark va inizializzato nel costruttore, calcolando la media di un array di float passato come parametro al costruttore stesso.

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Student
- Viene creato un array di String contenente tutti i nomi degli studenti
- Vengono chiamati i metodi scritti al punto 1 nell'array appena creato ed il risultato viene stampato a schermo

# Traccia 8
1. Scrivere un programma in Java che contenga i seguenti metodi:

- getMinInOddIndex(): Prende in input un array di double e restituisce il minimo fra gli elementi presenti in un'indice dispari
- getMaxInEvenIndex(): Prende in input un array di double e restituisce il massimo fra gli elementi presenti in un'indice pari
- getShorterEvenString(): Prende in input un array di stringhe e restituisce la stringa più corta fra quelle con un numero pari di caratteri

2. Implementare una classe Student definita dai seguenti attributi:
- name: String
- averageMark: double

I seguenti vincoli vanno implementati quando si modificano i valori delle variabili d'istanza nel costruttore e nei setter:
- La stringa "name" non può essere vuota
- Il valore di averageMark dev'essere compreso fra 0.0 e 5.0

3. Scrivere un metodo main in cui si effettuano le seguenti operazioni:
- Viene inizializzato un array di 3 oggetti Student
- Viene creato un array di String contenente tutti i nomi degli studenti
- Viene creato un array di double contenente tutti i voti medi degli studenti
- Vengono chiamati i metodi scritti al punto 1 nell'array appena creato ed il risultato viene stampato a schermo




