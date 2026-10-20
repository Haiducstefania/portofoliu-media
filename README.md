# portofoliu-media
Teme si proiecte,clasa a XII-a,Productie media,Liceul Tehnologic Grigore C.Moisil Buzau

Test de verificare – GitHub

1. Ce este un depozit și ce conține în plus față de un folder obișnuit?
Un depozit (repository) este un spațiu în care se păstrează fișierele unui proiect și istoricul modificărilor acestora. Față de un folder obișnuit, depozitul înregistrează versiunile fișierelor și commit-urile realizate cu Git.
2. Ce este un commit? Ce informații înregistrează GitHub?
Un commit este o înregistrare a unei modificări aduse proiectului. Acesta conține modificările salvate, un mesaj care explică ce s-a schimbat, autorul, data și un identificator unic.
3. Care sunt regulile GitHub pentru parolă și pentru numele de utilizator?
- Parola: trebuie să respecte cerințele GitHub privind lungimea și combinația de caractere. Este recomandat să fie puternică și unică.
- Numele de utilizator: poate conține litere, cifre și cratime (-), dar nu poate începe sau termina cu o cratimă și nu poate conține spații sau caractere precum _.
4. Care nume de utilizator sunt acceptate?
- ana-ionescu — acceptat, deoarece conține litere și o cratimă între cuvinte.
- -ana- — neacceptat, deoarece începe și se termină cu o cratimă.
- ana ionescu — neacceptat, deoarece conține un spațiu.
- ana_ionescu — neacceptat, deoarece conține caracterul _, care nu este permis în numele de utilizator GitHub.
5. Ce se face pe calculatorul din laborator la sfârșitul orei și de ce?
La sfârșitul orei, se închide sesiunea contului GitHub, se șterg fișierele personale descărcate pe calculatorul laboratorului și se închid programele. Astfel, datele personale sunt protejate, iar calculatorul rămâne pregătit pentru următorul elev.

Notă: aceasta este o recomandare generală; instrucțiunile exacte ale profesorului au prioritate.
6. Prin ce diferă un depozit Public de unul Private? Care se alege pentru portofoliu?
- Public: poate fi vizualizat de oricine.
- Private: poate fi accesat doar de proprietar și de persoanele autorizate.
Pentru un portofoliu care trebuie prezentat profesorului sau viitorilor angajatori se alege, de regulă, un depozit Public, dacă fișierele nu conțin informații personale sau confidențiale.
7. Se rescriu corect numele folderului și al fișierului
- Folder: tema-2-pliant
- Fișier: pliant-final.pdf
Regulă: se folosesc litere mici, fără spații și fără diacritice, iar cuvintele se separă prin cratimă.
8. Care sunt limitele la încărcarea din browser?
- Mărimea maximă a unui fișier: 25 MiB.
- Numărul maxim de fișiere încărcate simultan: 100.
Acestea sunt limitele documentate de GitHub pentru încărcarea fișierelor prin browser. 

GitHub Docs



9. Afișul a fost corectat. Cum se încarcă varianta nouă și ce se întâmplă cu cea veche?
Se încarcă varianta corectată cu același nume și în același folder, înlocuind fișierul existent. Se adaugă un mesaj de commit, de exemplu Corectează afișul. Varianta nouă devine versiunea curentă, iar cea veche rămâne disponibilă în istoricul modificărilor Git.
10. Mesaj de commit pentru înlocuirea fotografiei
Înlocuiește fotografia de pe fața pliantului – tema 2


11. Adresele depozitului, site-ului și fișierului
Pentru utilizatorul maria-stan, depozitul portofoliu-media și fișierul indicat, adresele sunt:
- Adresa depozitului:
  
  https://github.com/maria-stan/portofoliu-media
- Adresa site-ului GitHub Pages:
  
  https://maria-stan.github.io/portofoliu-media/
- Adresa fișierului PDF pe site:
  
  https://maria-stan.github.io/portofoliu-media/tema-02-pliant/pliant.pdf
Adresele site-ului și ale fișierului vor funcționa după activarea GitHub Pages și publicarea cu succes a fișierelor.
12. Care sunt pașii de activare a GitHub Pages? Ce fișier este prima pagină?
1. Se deschide depozitul pe GitHub.
2. Se accesează Settings.
3. Se selectează Pages.
4. La secțiunea Build and deployment, se alege Deploy from a branch.
5. Se selectează ramura main și folderul /(root).
6. Se apasă Save.
7. Se așteaptă publicarea site-ului și se accesează adresa afișată.
Prima pagină a site-ului este, de regulă, fișierul index.html. GitHub Pages poate utiliza și index.md sau README.md, în funcție de configurație. 

GitHub Docs
+1



13. Corectarea fragmentului HTML
Cele patru greșeli sunt: lipsește semnul > de la primul titlu, imaginea folosește o cale locală de pe calculator, imaginea indică un PDF în locul fotografiei PNG, iar calea către PDF are majuscule și nu corespunde numelui real al folderului și fișierului.

Varianta corectă:
<h2>Tema 2 – Pliant</h2>

<img src="tema-02-pliant/pliant-fata.png"
     alt="Fața pliantului">

<p>
  <a href="tema-02-pliant/pliant.pdf">
    Deschide pliantul (PDF)
  </a>
</p>


14. Trei lucruri care nu se publică într-un depozit public
1. Parole și chei secrete de acces.
2. Date personale, precum adresa de domiciliu sau numărul de telefon.
3. Documente private ori confidențiale.
