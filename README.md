Misija Nexus - Analiza kratera Jezero
Ovo je moj završni inženjerski projekt u sklopu Misije Nexus. U ovoj simulaciji preuzimam ulogu analitičara podataka i navigacijskog inženjera za rover koji istražuje Mars.
🚀 Ciljevi projekta
Generiranje podataka: Korištenje generatora za stvaranje jedinstvenih setova mjerenja.
Obrada podataka: Korištenje biblioteke Pandas za učitavanje, spajanje i čišćenje podataka od senzorskih anomalija (pogrešne temperature i pH vrijednosti).
Vizualizacija: Izrada 5 naprednih grafova, uključujući mapiranje putanje preko satelitskih snimaka kratera Jezero.
Slanje naloga: Kreiranje složenog JSON naloga i slanje HTTP zahtjeva na nadzorni poslužitelj.
📁 Kako pokrenuti projekt
Pokretanje generatora: Prvo pokrenite skriptu generator.py kako biste dobili CSV datoteke s podacima u mapi moji_mars_podaci.
Analiza i čišćenje: Pokrenite glavnu skriptu koja će očistiti podatke od kvarova na senzorima (npr. temperature od +150°C).
Slanje rezultata: Skripta će automatski poslati nalog na server. Dobivanje statusa 200 znači da je misija uspješno završena.
📊 Tehnologije
Python (glavni programski jezik)
Pandas (za manipulaciju tabličnim podacima)
Matplotlib / Seaborn (za izradu grafova i mapa)
Requests (za komunikaciju sa serverom putem HTTP-a)
📍 Područje istraživanja
Istraživanje se odvija u krateru Jezero (Neretva Vallis Delta), gdje rover traga za tragovima vode i organskih molekula na temelju očitanja metana i vlage.
