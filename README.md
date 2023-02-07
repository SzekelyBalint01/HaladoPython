# HaladoPython

# Python 3.9
  E feletti verziók már nem támogatják a deep-translator.

# Program funkciója

    Bemeneti szót átfordítja a kívánt nyelvre

# Használt csomagok

    flask
    loguru
    google-cloud-translate
    google-auth
    deep-translator
    
    venv -et használtam (virtual environments)
    venv = saját kornyezetet hoza létre ahova behuzza a szükséges modulokat/packegeket
    venv -en fut a program
# Fügvények
  

    translate_text:
    lefordítja a kapott szót és visszaadja a lefordított szót.
    translate_text(inputtext,source_language, target_language)
    return translated_word
    <img width="1284" alt="Screenshot 2023-02-07 at 2 06 58" src="https://user-images.githubusercontent.com/90506701/217122370-7111af71-a773-43c6-9e8f-         f65f8cae7d18.png">
    

    home: ez fügvény kezeli a requestek (POST, GET).
        Megkapja a lefordítandó szót és a source_language illetve a target_language -t.
        Majd e paraméterek alapján lefordítja a szót amit visszaad a "home.html" templatenek.

# Program használata

    Első kereső mezőbe irja be a fordítani kívánt szót. Majd válassza ki hogy milyen nyelvról fórdítsa milyenre. (Automatikus = automatikusan felismeri a nyelvet).
