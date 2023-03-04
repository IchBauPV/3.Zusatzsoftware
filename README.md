Hier findet Ihr Zusatzsoftware für das PV Projekt zur Visualisierung und das Kalkulationstool demnächst für die Ertrags-(Amortisationsrechnung)

## A. Visualisierung in Excel  
1.	Makros aktivieren  
Im Datei Explorer Datei rechts-klicken => Eigenschaften => Sicherheit => Zulassen Haken setzen, übernehmen	
2.	Einrichtung	  
		Den ESP32 mit dem Heimnetz verbinden (über den ESP32 Accesspoint)  
		Der ESP32 muss im Heimnetz (z.B. über die Fritzbox) folgenden Namen erhalten: 
3.	Optionale Tests	  
		Jetzt müsstet Du [hier](http://esp32-pv-anlage)  auf die Startseite des ESP-Webservers kommen
		Die Datenseite kannst Du nun wie folgt aufrufen:
		http://esp32-pv-anlage/get?ShowDataPage=1 für heute; [=2](http://esp32-pv-anlage/get?ShowDataPage=2) für dieser Monat; =[3](http://esp32-pv-anlage/get?ShowDataPage=3) für dieses Jahr; [=4](http://esp32-pv-anlage/get?ShowDataPage=4) für Vorjahr
4.	Bedienung des Programms	      
		Tab                                               für Ansicht  Jahr / Monat / Tag wählen    
		Button                                           holt die aktuellen Zahlen vom ESP und stellt sie dar    
		Button                                           stellt Zoomlevel 1 bzw 2 ein     
		Button                                           stellt Vollbildmodus mit dem entspr. Zoomlevel ein     
		Button                                          Navigation Tag/Monat vor oder zurück    
		
6.	Optionale Erweiterung  
 Zugriff aus über das Internet	
		Durch Einrichtung einer Port-Weiterleitung im Router könnte Ihr auch aus dem Web zugreifen   
		Achtung: Es gib hier keine Schutzfunktionen oder Passwörter, jeder kann zugreifen !!!    
		Einziger Schutz ist die Deaktivierung der Konfigurationsmöglichkeit!!!

B. Das Kalkulationstool (kommt demnächst)

