Šī projekta galvenais uzdevums ir izveidot vienkāršu kalkulatora programmu Python valodā.
Kalkulatoram ir jāspēj veikt četras pamata matemātiskās operācijas: saskaitīšanu, atņemšanu, reizināšanu un dalīšanu. 
Sīkākais uzdevums ir nodrošināt lietotājiem ērtu un saprotamu saskarni, lai tie varētu viegli veikt aprēķinus bez sarežģījumiem.
Izveidojam Matemātiskās Operācijas:

Definējam četras funkcijas: add (saskaitīšana), subtract (atņemšana), multiply (reizināšana) un divide (dalīšana).
Menu Parādīšana:

Izvadām lietotājam pieejamās darbības, izmantojot vienkāršu izvēlni:
"1. Add" - saskaitīšana
"2. Subtract" - atņemšana
"3. Multiply" - reizināšana
"4. Divide" - dalīšana
"5. Exit" - iziešana no kalkulatora
Lietotāja Ievade:

Lietotājam tiek piedāvāts ievadīt izvēlnes punktu (1-5).
Ja ievadītais punkts ir 5, programma beidz izpildi ar ziņojumu par iziešanu no kalkulatora.
Matemātisko Operāciju Veikšana:

Ja lietotājs ievada punktu no 1 līdz 4, tad programma prasa ievadīt divus skaitļus (num1 un num2).
Rezultāta Parādīšana:

Programma izsauc atbilstošo funkciju, lai veiktu izvēlēto matemātisko operāciju.
Rezultāts tiek izvadīts uz ekrāna kopā ar ievadītajiem skaitļiem un izvēlēto operāciju.
Kļūdu Pārvaldīšana:

Programma pārbauda, vai lietotājs ir ievadījis derīgu izvēlnes punktu un vai skaitļi ir derīgi (skaitļu ievadē tika izmantots float).
Tiek pārbaudīts, vai nav mēģināts dalīt ar nulli.
Izpildes Atkārtošana:

Pēc katras operācijas programma atgriežas pie izvēlnes, piedāvājot lietotājam turpināt aprēķinus vai iziet no kalkulatora.

Projekta izstrādes laikā ir izmantotas šādas Python bibliotēkas:
sys - izmantojam, lai nodrošinātu programmas izpildi un izietu no tās, ja nepieciešams.
Markdown - izmantojam, lai izveidotu informatīvu README.md failu. Šī bibliotēka ļauj mums izstrādāt strukturētu un labi formatētu aprakstu, padarot to lasāmāku.


