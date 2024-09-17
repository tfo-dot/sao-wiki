# Komendy

Poniżej znajdziecie rozpiskę wszystkich komend jakie obsługuje bot.

## Ruch

Składnia: `/ruch`

Działanie: przenosi do wybranej lokacji, w obrębie piętra, na którym znajduje się użytkownik.

## Teleport

Składnia: `/tp`

Działanie: przenosi na wybrane piętro, zakładając, że:

* można się teleportować z aktualnej lokacji
* użytkownik ma dostęp do danego piętra
* użytkownik nie jest w walce

## Info

Składnia: `/info`

{% hint style="info" %}
Ta komenda wspiera wybranie użytkownika (jako celu)
{% endhint %}

Działanie: pokazuje informacje o postaci, w szczegółach:

* Nazwa
* Użytkownik, który jest właścicielem postaci
* Lokacja w jakiej znajduje się postać
* Aktualne HP, Mana
* Wybrane statystyki:
  * ATK
  * HP
  * DEF/RES
  * SPD/AGL
* Poziom postaci, doświadczenie
* Czy jest w walce
* Czy jest w party
* Dynamiczne statystyki (w tym: ile daje, z czym rośnie)

## Skill

### Pokaż

Składnia: `/skill pokaż`

Działanie: pokazuje umiejętności posiadane przez gracza, wraz z ich czasem odnowienia i opisem.

Dodatkowo:

* Umiejętności natychmiastowe są **pogrubione**
* Umiejętności, których można użyć w trakcie trwania efektu kontroli tłumu, podkreślone

### Odblokuj

Składnia: `/skill odblokuj`

Działanie: po wybraniu poziomu, pokazuje umiejętności, które możesz odblokować.

### Ulepsz

Składnia: `/skill ulepsz`

Działanie: po wybraniu poziomu, pokazuje ulepszenia umiejętności.

## Plecak

Składnia: `/plecak pokaż`

Działanie: pokazuje ekwipunek użytkownika, wraz z posiadanym przez niego złotem.

## Szukanie

Składnia: `/szukaj`

Działanie: Szuka przeciwnika w danej lokacji.

## Party

### Pokaż

Składnia: `/party pokaż`

Działanie: pokazuje informacje o party w którym jest twoja postać

### Zaproś

Składnia: `/party zapros`

Działanie: Wysyła danemu użytkownikowi zaproszenie do party

{% hint style="warning" %}
Możesz to zrobić tylko i wyłącznie, kiedy jesteś liderem party
{% endhint %}

### Wyrzuć

Składnia: `/party wyrzuć`

Działanie: wyrzucasz danego użytkownika z party

{% hint style="warning" %}
Możesz to zrobić tylko i wyłącznie, kiedy jesteś liderem party
{% endhint %}

### Opuść

Składnia: `/party opuść`

Działanie: Opuszcza party

{% hint style="warning" %}
Nie możesz zrobić tego, jeśli jesteś liderem party. Musisz oddać komuś rolę lidera.
{% endhint %}

### Zmień

Składnia: `/party zmień`

Działanie: Zmienia role użytkownika w party, dając mu bonusy w walce z tego wynikające

{% hint style="warning" %}
Możesz to zrobić tylko i wyłącznie, kiedy jesteś liderem party
{% endhint %}

### Rozwiąż party

Składnia: `/party rozwiąż`

Działanie: Rozwiązuje party

{% hint style="warning" %}
Możesz to zrobić tylko i wyłącznie, kiedy jesteś liderem
{% endhint %}

## Stwórz

Składnia: `/stwórz`

Działanie: tworzy przedmiot korzystając z przedmiotów w twoim ekwipunku

## Furia

### Pokaż

Składnia: `/furia pokaż`

Działanie: pokazuje informacje o Furii, w szczegółach:

* Imię i nazwisko
* Poziom Furii
* Umiejętności
* Statystyki jakie otrzymuje władający
* Informacje o tierze

### Ulepsz

Składnia: `/furia ulepsz`

Działanie: jeśli to możliwe ulepsza furie korzystając ze składników w ekwipunku

## Sklep

Składnia: `/sklep pokaż`

Działanie: pokazuje sklepy w miejscu, w którym znajduje się twoja postać

## Handel

Składnia: `/handel nowy`

Działanie: wysyła użytkownikowi prośbę do wymiany

{% hint style="warning" %}
Komenda może nie działać poprawnie
{% endhint %}
