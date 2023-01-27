SPRAWOZDANIE
# .NET
Project if a web API in C# .NET Razor pages

Niniejszy projekt to aplikacja internetowa w której użytkownik może znaleźć informacje dotyczące popularnych i tradycyjnych dań szeroko pojętej kuchni orintalnej,
jak również dodawać, usuwać i edytować pozycje w bazie danych z poziomu aplikacji. Aplikacja została wykonana w technologii Razor Pages przy użyciu IDE Visual Studio
w wersji 5.

Model Razor Pages wybrałem do utworzenia projktu z kilku powodów. Po pierwsze wydaje się relatywnie prosty do zrozumienia dla deweloprów dopiero zaczynających 
pracę z ASP.NET Core, którego logika jest oparta na stronach, co tym bardziej ułatwia zrozumienie. Wykonanie po stronie klienta oganicza konieczność przesyłu danych 
pomiędzy serwerem a urządzeniwm użytkownika, co w efekcie przyspiesza działanie aplikacji. W tym miejscu wypada przyznać, że jednym z istotnych powodów dla wyboru 
Razor Pages był fakt, że wszystkie próby wykonania aplikacji przy użyciu innych modeli (MVC, Blazor) zakończyły się niepowdzeniem, pomimo posiłkowania się samouczkami
na platformie Microsoft Learn oraz innymi źródłami (kursy internetowe w serwisach YouTube i Udemy, programistyczne forum StackOwerflow). 

Aplikację wykonałem posiłkując się zasoabami samouczka Microsoft Learn. Pierwsze próby kompilacji w tym modelu RP również byly nieudane. Głównym błędem, który popełniłem,
było nazwanie klasy modelu tak samo folderu folderu podstron projektu. Powodowało to konflikt w przestrzeni nazw. W rezultacie po utworzeniu modelu (scaffold) wszytkie 
pliki w nowopowstałym modelu tworzone były od razu z licznymi błędami (około 150-190 błędów). Kolejnym wyzwaniem było prawidłowe utworzenie oraz migracja bazy danych.
Zagadnienie to nie jest, moim zdaniem dostatecznie wyjaśnione w samouczku Microsoft Learn. Po głębszym zapoznaniu się z tematem dowiedziałem się, że prawidłowe utworzenie
i migracja bazy danych wymagają podania dokładego kontekstu w projekcie.

Z powodów ograniczonego czasu i początkowych niepowodzeń nie zdążyłem dodać więcej funkcjonalności i działającego mechanizmiu logowania i dodawania użytkjowników. Tym 
nie mniej opracowanie działającej aplikacji w technologii ASP.NET Core uważam za swój ogromy sukces. To doświadczenie zachęca mnie do dalszego zapoznania się z tą 
technologią w przyszłości.
