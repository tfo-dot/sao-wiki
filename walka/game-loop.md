# Game loop

Każda istota w walce ma swój własny licznik. Iteracją nazwijmy moment, w którym wszystkie jednostki w walce zwiększają licznik o swoją wartość prędkości.

## Tury

W przypadku gdy w trakcie iteracji licznik jednostki wyniesie więcej niż 100, następuje tura jednostki, może ona w tym momencie wykonać akcje. Naturalnie w przypadku ogłuszenia (czy innego efektu z podobnymi właściwościami), tura zostaje pominięta.

Efekty tur są aktywowane po zakończeniu wykonywania akcji przez jednostkę. Do nich zaliczamy:

* Efekty (trucizna, ogłuszenie, itp. )
* Tymczasowe efekty (np. zwiększenie ataku o 10 na jedną turę)

Jedynym wyjątkiem od tej reguły jest zmniejszenie czasów odnowienia, które następuje przez wykonaniem akcji.

### Wykorzystanie akcji

Niektóre umiejętności, akcje nie konsumują akcji przykładem tej mechaniki są umiejętności natychmiastowe. Dopóki akcji nie zostanie wykorzystana będzie to wasza tura.

#### Przykład

Po użyciu umiejętności [poziom-1.md](../gracz/umiejetnosci/obrazenia/poziom-1.md "mention"), wasza akcja nie zostanie wykorzystana. Jeśli chcecie możecie użyć kolejnej umiejętności natychmiastowej a wasza tura dalej będzie trwała. Natomiast w przypadku, gdy zechcecie zrobić coś co konsumuje akcje (np. Atak) wasza tura zakończy się.

## Walka

Walka toczy się aż któraś strona całkowicie nie straci jednostek, poprzez stratę jednostki rozumiemy:

* Śmierć (poniesienie śmiertelnych obrażeń)
* Ucieczka z walki
