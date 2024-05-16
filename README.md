# pawcho8
Sprawdzenie czy mamy buildx
<img width="480" alt="Zrzut ekranu 2024-05-14 o 18 37 47" src="https://github.com/Hiubertus/pawcho8/assets/138579706/af9e7130-ec12-4390-8fe2-f0714bd80f2d">
Zalogowanie się do DockerHuba na konsoli i dodanie repo do scouta
<img width="835" alt="Zrzut ekranu 2024-05-14 o 18 36 22" src="https://github.com/Hiubertus/pawcho8/assets/138579706/adcaff86-d83d-45bd-b9a5-83da168efaf9">
Zbudowanie aplikacji i zpushowanie jej do repo
<img width="884" alt="Zrzut ekranu 2024-05-14 o 18 46 58" src="https://github.com/Hiubertus/pawcho8/assets/138579706/e8671b79-9bdf-4ca2-bf89-4c64ebad1842">
Plik Docker przed wprowadzeniem zmian
<img width="355" alt="Zrzut ekranu 2024-05-14 o 18 58 20" src="https://github.com/Hiubertus/pawcho8/assets/138579706/9653170f-5a0e-4573-8504-06cc50dd8a9a">
Plik package.json przed wprowadzeniem zmian
<img width="287" alt="Zrzut ekranu 2024-05-14 o 19 02 42" src="https://github.com/Hiubertus/pawcho8/assets/138579706/24c8db1e-b867-40b7-b79c-03ac8906f561">
Ilość błędow przed wprowadzeniem zmian
<img width="883" alt="Zrzut ekranu 2024-05-14 o 18 48 39" src="https://github.com/Hiubertus/pawcho8/assets/138579706/6cd04a27-4716-4788-9caa-7179f62f2ee2">
Plik Docker po wprowadzeniu zmian
<img width="557" alt="Zrzut ekranu 2024-05-16 o 20 25 07" src="https://github.com/Hiubertus/pawcho8/assets/138579706/dc9b7083-2b52-4c19-b4fe-4c14362c718a">
Zmieniłem na inna wersje alpine, by zmiejszyć liczbę unspecified błędów
Dodałem do npm install -g npm@latest, by obraz zaktualizował node,gdyż
ta wersja alpine miała problem spowodowany przestarzałą paczką tar,
podobnie jak z apt update, by pozbyć się błędów spowodowanych przestarzała
wersją libss w alpine

Plik package.json po zmianach
![image](https://github.com/Hiubertus/pawcho8/assets/138579706/b7563db4-93e6-4f21-a328-7ae61ec86f99)
Dodałem tu nowsze wersje pakietów, które powodowały problemy, wiele z nich było też
zmienione w package-lock.json

Ilość błędów po zaktualizowaniu plików
<img width="652" alt="Zrzut ekranu 2024-05-16 o 20 24 34" src="https://github.com/Hiubertus/pawcho8/assets/138579706/670925a8-d5d4-4877-8693-d66c1a5bd899">
Jak widać, udało się pozbyć każdego problemu.





