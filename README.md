# Hubertiming-BeautifulSoup
Za realiziranje ovog projekta, koristila sam Python biblioteku za izvlačenje podataka iz HTML stranice. 
Često se koristi jer je jednostavan u primjeni i štedi dosta vremena. 
BeautifulSoup pomaže da izvučemo određeni sadržaj s web-stranice, uklonimo HTML oznaku i spremimo informacije. 

Ulazni podaci se nalaze na stranici i uz pomoć BeuatifulSoup sam došla do njih. Nakon što se učitao html dokument, ispisala sam naslov(title) stranice. Nakon toga sam dohvatile sve linkove, te poslije toga ulazim u tablicu rezultata na stranici i prolazim liniju po liniju. Nakon što sam dobila listu tih podataka koji mi trebaju, izbacila sam uz replace elemente koji su "višak". Sve je zatim spremljeno u tablicu pod nazivom df(dataframe). Još nedostaju naslovi stupaca, njih sam dohvatila sa soup.find("th") (još jedna od mogućnosti biblioteke BeautifulSoup, gdje možemo šetati po stranici i dohvaćati informacije koje su nam potrebne) i spremila u header_list. Naslovi su "zaljepljeni" na df. Ispisala sam info() svoje df, te na kraju izvezla CVS datoteku s podacima koji su dohvaćeni sa stranice uz pomoć BeautifolSoup-a.
