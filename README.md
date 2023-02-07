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
    
# Tuple

  Itt lehet hozzáadni kivenni nyelveket és az alapértelmezett source/target nyelvet beállítani.
 <img width="1284" alt="Screenshot 2023-02-07 at 2 06 36" src="https://user-images.githubusercontent.com/90506701/217124510-faf5a5d4-2af9-48d0-926a-98e4df9681d2.png">


# Fügvények
  

    translate_text:
    lefordítja a kapott szót és visszaadja a lefordított szót.
    translate_text(inputtext,source_language, target_language)
    return translated_word
   
    
[<img width="1284" alt="Screenshot 2023-02-07 at 2 06 58" src="https://user-images.githubusercontent.com/90506701/217123681-3d0cc11e-8b5a-49a0-a712-238120f5d7fe.png">](https://user-images.githubusercontent.com/90506701/217123681-3d0cc11e-8b5a-49a0-a712-238120f5d7fe.png)

    home: ez fügvény kezeli a requestek (POST, GET).
        Megkapja a lefordítandó szót és a source_language illetve a target_language -t.
        Majd e paraméterek alapján lefordítja a szót amit visszaad a "home.html" templatenek.
   
<img width="1175" alt="Screenshot 2023-02-07 at 2 27 25" src="https://user-images.githubusercontent.com/90506701/217125034-a3290e5c-1928-4a6a-98bb-9610057717dd.png">


# Program használata

    Első kereső mezőbe irja be a fordítani kívánt szót. Majd válassza ki hogy milyen nyelvról fórdítsa milyenre. 
    (Automatikus = automatikusan felismeri a nyelvet).
