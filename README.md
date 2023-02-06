# HaladoPython

# Program funkciója

    Bemeneti szót átfordítja a kívánt nyelvre

# Használt csomagok

    flask
    loguru
    deep_translator
    (GoogleTranslator)

# Fügvények

    translate_text:
    lefordítja a kapott szót és visszaadja a lefordított szót.

    translate_text(inputtext,source_language, target_language)

    return translated_word

    home: ez fügvény kezeli a requestek (POST, GET).
        Megkapja a lefordítandó szót és a source_language illetve a target_language -t.
        Majd e paraméterek alapján lefordítja a szót amit visszaad a "home.html" templatenek.

# Program használata

    Első kereső mezőbe irja be a fordítani kívánt szót. Majd válassza ki hogy milyen nyelvról fórdítsa milyenre. (Automatikus = automatikusan felismeri a nyelvet).
