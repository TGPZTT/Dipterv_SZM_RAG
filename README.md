# Dipterv_SZM_RAG

A projekt állományai a vektoradatbázisok és a felhasznált PDF dokumentumok miatt nem fértek fel a repoba.
Ezen a linken letölthetőek: [google drive](https://drive.google.com/drive/folders/1le6lw988GPmSxG6p3hbPoaQ0Ps7f7smF?usp=sharing) 
A RAG_OpenAI változaton készítettem az eval-t, a másik egy kísérleti változat volt, amiről szó esik a dolgozatban.

Az alábbi futtatandó (opcionális venv környezetben):
pip install langchain langchain-community langchain-openai chromadb python-dotenv voyageai gradio

Mindkét könyvtárba elhelyezendő egy .env fájl az API kulcsokkal. Ezt nem töltöttem fel, de külön elküldtem a dolgozattal együtt.

A vektoradatbázis a document_loader.py futtatásával építhető. A próbálgatások miatt most úgy van beállítva, hogy törli a régit és felépíti az újat.
A main.py futtatásával pedig kipróbálható a felület. Jelenleg be van kapcsolva, hogy globálisan is elérhető legyen a telefonos tesztelés miatt, de ez szükség esetén kikapcsolható.


