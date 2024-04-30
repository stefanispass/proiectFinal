# proiectFinal

Pași de urmat:
Se creează o conexiune pentru baza de date.
În interiorul ei, se creează o nouă schemă care va fi setată ca _default schema_.
Se va rula funcția main din clasa _ProiectItFactoryApplication_.
Pentru a popula baza de date, vom folosi http://localhost:8080/inregistrare, care va trimite detaliile direct către baza de date. Câmpurile au anumite constrângeri.
![image](https://github.com/stefanispass/proiectFinal/assets/161347646/130069b2-edac-4159-b958-9cfeecb194dd)
După popularea bazei de date, putem folosi http://localhost:8080/login pentru conectare. De aici, orice utilizator va avea acces la http://localhost:8080/list_users (pagină unde sunt afișați toți utilizatorii), la formularele de Modificare Nume și Modificare Email și la calea "/user_details/{id}", de unde se poate căuta un utilizator în funcție de id-ul inclus în cale. Toate căile necesită ca utilizatorul să fie conectat.
