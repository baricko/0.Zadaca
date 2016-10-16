#JMBAG
0108067197

Pitanje 1.
U bin/debug folder konzolne aplikacije je su nadodane dvije 
datoteke formata .dll i .pdb naziva ClassLibrary1.Nakon 
pokretanja .exe datoteke javlja se greška, toènije iznimka, 
gdje je specificirano da se aplikacija ne može pokrenuti zbog 
nemoguænosti pronalaska CLassLibrary asemblija.

Pitanje 2.
Konzolna aplikacija je koristila staru verziju class library
asemblija, jer promjene koje su unesene u novi class library
nisu prevedene, tj. nije formirana novi .dll asemblij.

Pitanje 3.
Ispisao se tekst: Pero:Hello World

Pitanje 4.
PeroClassLibrary asemblij je nadodan u Bin/Debug folder 
konzolne aplikacije.

Pitanje 5.
Aplikacija i dalje radi jer je stvorena kopija .dll biblioteke
unutar Bin/Debug foldera konzolne aplikacije. Tako i prilikom
build-a se asemblij od PeroClassLibrary i dalje može naæi u
Bin/Debug folderu.