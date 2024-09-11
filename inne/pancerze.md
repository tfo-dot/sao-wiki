# Pancerze

Ta strona opisuje wzajemne zależności między pancerzami i przebiciem.

## Pancerz

Pancerze redukują otrzymane obrażenia zgodnie z formułą poniżej.

$$
o =dmg - (dmg * \frac{100}{100-p})
$$

Gdzie:

* o = to obrażenia wynikowe
* p = pancerz
* dmg = początkowe obrażenia

## Przebicie

Przebicie ignoruje daną wartość pancerza, ale nie redukuje pancerzu na stałe. Gdy wartość zredukowanego pancerza wyniesie mniej niż 0, obrażenia zostaną zwiększone.

## Przebicie procentowe

Przebicie procentowe ignoruje procentową wartość pancerza. Nie ma zastosowania przy pancerzu wynoszącym 0 lub mniej. Innymi słowy przebicie procentowe nie zwiększa obrażeń tak jak robi to przebicie stałe.

## Odporność na magię

Wszystkie mechaniki oraz formuły mają takie same działanie i podlegają takim samym zasadom jak pancerz jak i przebicie pancerza.
