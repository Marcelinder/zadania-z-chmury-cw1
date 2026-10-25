# Bezpieczeństwo — hasła i klucze w repozytorium

Publiczne repozytorium może przeglądać każdy, są boty w kilka minut wyłapują wrzucone klucze dostępu.

Skradziony klucz pozwala przejąć konto w chmurze lub nabić wysoki rachunek.

Samo usunięcie pliku nie wystarcza, bo Git przechowuje historię zmian i hasło nadal widać w starszym zatwierdzeniu.

Dlatego klucz trzeba natychmiast unieważnić i wygenerować nowy, a sekrety trzymać poza repozytorium.
