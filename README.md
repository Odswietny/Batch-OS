# Batch-OS
Batch OS to otwartoźródłowy projekt tekstowego systemu operacyjnego działającego na skryptach wsadowych.

# Jak używać?
To proste - wypakuj plik ZIP i uruchom plik `batchos.bat`.
Możesz wpisać `help` by dowiedzieć się o komendach.
Po pierwszym uruchomieniu zostanie utworzony folder użytkownika o nazwie Twojego użytkownika w systemie Windows (`user\[nazwa]`).

# Problemy
Po użyciu cudzysłowia (") program z jakiegoś powodu ulega awarii. Nie wiem dlaczego tak się dzieje :(

# Wielojęzyczność
Do programu dołączony jest pakiet językowy dla języka angielskiego. Oto jak go zastosować:
1. Skopiuj zawartość folderu `lang\lang eng` do folderu `lang`.
2. Jeśli Batch OS jest uruchomiony, uruchom go ponownie komendą `reboot`.

# Dołączone oprogramowanie
Do programu dołączone są trzy mini-programy:
## 1.0:
1. **Przeglądarka** (`programs\browser`) - Możesz wpisać dowolny adres (lub jeden z trzech dostosowywalnych slotów szybkiego wybierania), a zostanie on otwarty w domyślnej przeglądarce w systemie Windows.
2. **Note Maker** (`programs\notemaker`) - Użyj go do zapisywania notatek. Zostaną one zapisane w folderze `user\[nazwa]\documents`.
3. **Zgadnij liczbę** (`programs\guessnumber`) - Zgadnij liczbę w zakresie 0-32767.
Dodatkowe mini-programy wstaw do folderu `programs`.

# Redystrybucja i modyfikacje
Batch OS jest **w pełni otwartoźródłowym** oprogramowaniem. Podobnie jak w przypadku Linuxa, można stworzyć swoją własną dystrybucję z dowolnymi modyfikacjami. Jeśli się na to zdecydujesz, pamiętaj, by do komendy `ver` i/lub sekcji informacji o systemie (programie) dodać informację o bazowym programie i wersji. Na przykład:
_"Oparte na Batch OS 1.0"_
A gdy zdecydujesz się wstawić swoją dystrybucję na GitHub, pamiętaj, by wstawić gałąź (fork) do **tego** repozytorium.

# Co planuję?
## 1.1
1. Resetowanie do ustawień fabrycznych
2. Zmiany w grafikach tekstowych
3. Naprawa do gry "Zgadnij liczbę"
## 1.2
1. System zgłaszania błędów
2. (Potencjalne) naprawienie problemów z cudzysłowem
3. Zmiany w grafikach tekstowych i animacjach
## 1.3
1. Ułatwiona wielojęzyczność
2. TextAnimPlayer dołączony do Batch OS
3. Kreator transferu danych
(planuję także niedługo wydać Batch OS 1.1 Beta 1)

# Transfer danych
Oto jak przenieść dane do nowszej wersji:
1. Dane użytkowników - skopiuj zawartość folderu `user` do folderu `user` w nowszej wersji.
2. Dane programów - skopiuj pliki konfiguracyjne programów z podfolderów w folderze `programs` do nowszej wersji.
3. Programy - skopiuj programy z folderu `programs` do nowszej wersji.
4. Dołączone programy - zmień nazwę folderów niektórych programów na `[nazwa]_old` i skopiuj je do nowszej wersji.

# Problem?
W razie problemów możesz skontaktować się ze mną:
Email: odswietny@gmail.com
lub na stronie Problemy (Issues) w repozytorium.
