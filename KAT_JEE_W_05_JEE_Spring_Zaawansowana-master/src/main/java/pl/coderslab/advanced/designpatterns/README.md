![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/152855/73064373-5ed69780-3ea1-11ea-8a71-3d370a5e7dd8.png)


## Zadanie 1 - rozwiązywane z wykładowcą

1. Utwórz implementację klasy `AppConfig`, której zadaniem będzie przechowywanie danych konfiguracyjnych.
2. Uzupełnij odpowiednie elementy klasy tak, by spełniała wymagania wzorca Singleton.



## Zadanie 2 - rozwiązywane z wykładowcą

1. Utwórz interfejs o nazwie `Product`, a następnie jego implementacje w postaci klas:
    * SimpleProduct
    * AdvancedProduct
    * VirtualProduct
2. Utwórz implementację wzorca Fabryki.

## Zadanie 3

1. Utwórz implementację klasy `AtmApi` udostępniającą API dla bankomatów zgodnie z wzorcem Fasady.
2. Klasa ta ma umożliwiać wywołanie:
    * metody `deposit` klasy `BankAccount`
    * metody `payOut` klasy `BankAccout`
    * metody `transferMoney` klasy `Transfer`
    * metody `recharge` klasy `PhoneCard`
    * metody `getLoan` klasy `Loan`
3. Utwórz wymagane klasy oraz ich metody

## Zadanie 4

Dla zadanego interfejsu `Observer`:
```
public interface Observer {
    void update(String title);
}
```
oraz `Subject`
```
public interface Subject {

    void attach(Observer observer);
    void detach(Observer observer);
    void notifyObservers();

}
```
1. Utwórz klasę `Post` implementującą `Subject`, która będzie dodatkowo zawierać pola:
````
private String content;
private String title;
````
oraz metodę:
````
public void share() {
    System.out.println("UPDATE OBSERVERS");
    notifyObservers();
}

````
2. Utwórz implementacje interfejsu `Observer` w postaci klas:
     
  * FacebookObserver - klasy imitującej umieszczenie postu na portalu Facebook
  * TwitterObserver - klasy imitującej powiadomienie subskrybentów o pojawieniu się nowego postu.

3. Uzupełnij implementacje zgodnie z wzorcem Obserwator.
4. Przykładowe wywołanie w metodzie testującej:
````
public static void main(String[] args) {
    Post post = new Post();
    post.setTitle("Some title");
    post.setContent("Some content");

    post.attach(new FacebookObserver());
    post.attach(new TwitterObserver());
    post.share();

}

````
