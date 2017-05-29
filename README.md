Pyraminx - seminarski rad iz predmeta programske paradigme, na trecoj godini R smera, na Matematickom fakultetu.


Link ka git-u: https://github.com/ppseminarski/Pyraminx_TamaraMarcetic_MajaStojkovic

Zahtevi:

	Na operativnom sistemu potrebno je imati instaliran programski jezik Python i Tkinter paket.
        Odgovarajuce upustvo za instalaciju paketa moze se naci na linku: https://tkinter.unpythonic.net/wiki/How_to_install_Tkinter
	Odgovarajuce upustvo za instalaciju programskog jezika moze se naci na linku: https://www.python.org/downloads/
 
        Program (dve verzije) i prateci fajlovi se nalaze u zip fajlu pod nazivom "Pyraminx_TamaraMarcetic_MajaStojkovic" i zauzimaju 4,34 MB
memorije


Bildovanje i pokretanje programa:

	linux: chmod +x pyraminx_v0.py
	       ./pyraminx_v0.py
               odnosno:
	       chmod +x pyraminx_v1.py
	       ./pyraminx_v1.py

	windows: klikom na fajl "pyraminxEXE_v0.exe", odnosno "pyraminxEXE_v1.exe" iz podfoldera "dist"


Opis programa:

	Pyraminx je pravilni tetraedar, puzzla dizajnirana u stilu Rubikove kocke 3x3. Izmisljena je 1970. od strane Uwe Meffert.
	
	Ovaj program je pisan u programskom jeziku Python, koriscenjem skript, komponentne i funkcionalne paradigme.
	Postoje dve verzije:
	1) pyraminx_v0.py - boje svakog dela piramide se nasumicno generisu
	2) pyraminx_v1.py - boje svakog dela piramide unosi korisnik
	Napomena: preostale dve verzije, pyraminxEXE_v0.py i pyraminxEXE_v1.py imaju istu svrhu kao pyraminx_v0.py, odnosno pyraminx_v1.py, a postoje kao zasebni fajlovi za potrebe pravljenja izvrsnog fajla (jer umesto exit, da bi izvrsni fajl mogao da se kreira i radi ispravno, mora da stoji sys.exit, sto nije podrzano kada program pokrecemo iz terminala).

	Program ilustruje postupak resavanja pyraminxa korak po korak. U slucaju 1), pocinjemo dugmetom "random" koje mesa boje, dok u slucaju 2) korisnik redom unosi boje svakog dela piramide. Zatim imamo dugme "pocni" - za pocetak prikaza algoritma za resavanje, i dugme "dalje" - koje sluzi za prelaz na sledeci korak, odnosno za prikaz sledeceg (niza) poteza koji treba da se izvrsi. Klikom na dugme "izlaz" u svakom trenutku mozemo da prekinemo izvrsavanje programa.
	Informacije o nazivima strana i potezima koji se primenjuju prilikom resavanja su prikazane na slikama "strane.png" i "potezi.png", koje se nalaze u pomenutom folderu gde i sam program ("Pyraminx_TamaraMarcetic_MajaStojkovic").
	
 

Autori:

	Tamara Marcetic (br. indeksa: 19/2014, mail: mr14019@alas.matf.bg.ac.rs) i Maja Stojkovic (br. indeksa: 317/2014, mail: stojkovic95@gmail.com), studenti trece godine R smera na Matematickom fakultetu u Beogradu.
