Hej, je�li aplikacja nie b�dzie mog�a si� ��czy� do serwera to pami�taj wgra� prawid�owy json ze swojej instancji firebase :) 
Wspominam o tym w kursie ale to bardzo popularny problem, wi�c zostawiam Ci tak� notatk� :)
Je�li jeste� zbyt leniwy na postawienie w�asnej bazy zgodnie z lekcj� 12_1 Tworzenie projektu firebase i 12_2	Konfiguracja projektu firebase, mo�esz skorzysta� w mojej zgodnie z jsonem kt�ry za��czy�em, jednak musisz wys�a� mi SHA-1 swojego debug.keystore
po prostu wpisz do konsoli:

keytool -list -v  -alias androiddebugkey -keystore %USERPROFILE%\.android\debug.keystore

je�li nie dzia�a to wprowad� bezpo�redni� �cie�k� u�ytkownika np.

keytool -list -v  -alias androiddebugkey -keystore C:\Users\user1\.android\debug.keystore

Dodanie do bazy tytu�uj w mailu "ADDSHA1" a powinno polecie� z automatu ;)
W tre�ci wstaw tylko ci�g SHA

m�j mail
wrzosdev@gmail.com

Powodzenia!