+-----------------------------------------------------------------------------------------------------------------------+
|															|
|	iArdu														|
|															|
|	Liest einen iButton Chip aus und gibt dessen ID an den Computer weiter.						|
|	Die ID kann am Computer mit der mitgelieferten Software eingelesen und verarbeitet werden.			|
|															|
+-----------------------------------------------------------------------------------------------------------------------+
|															|
|	Installation:													|
|															|
|	1. Schließen Sie den Reader an den Computer an und lassen Sie Windows die Treiber dafür installieren.		|
|	   Falls Windows die Treiber nicht automatisch installiert, müssen diese manuell nachinstalliert werden:	|
|															|
|		1.1	Gehen Sie in den Geräte-Manager(Windows-Suche) und suchen Sie den Eintrag "Arduino Leonardo"	|
			(Eintrag könnte auch Unter "COMXX" oder ähnliches bekannt sein)	
|		1.2	Machen Sie einen Rechtsklick auf den Eintrag und wählen Sie "Treiber aktualisieren"		|
|		1.3	Wählen Sie "Auf dem Computer nach Treibersoftware suchen" und geben Sie als Pfad 		|
|			den iArdu-Ordner an.										|
|		1.4	Warten Sie bis die Installation erfolgreich durchgeführt wurde.					|
|															|
|	2. Starten Sie die Anwendung "setup.exe" und folgen Sie den Anweisungen des Einrichtungsassistent.		|
|	3. Entfernen Sie kurz den Reader von dem Computer und schließen ihn wieder an.					|
|	4. Starten Sie das Programm "iArdu"										|
|															|
+-----------------------------------------------------------------------------------------------------------------------+
|															|
|	Nutzung:													|
|															|
|	Textfeld		->	Hier wird die ID des Chips angezeigt. Die ID kann hier markiert und		|
|					kopiert werden									|
|															|
|	Kopieren		->	Kopiert die ID in die Zwischenablage						|
|															|
|	Löschen			->	Löscht das Textfeld								|
|															|
|	Automatisch Einfügen 	->	Falls dieses Häckchen gesetzt wurde wird bei jedem Einlesen eines Chips		|
|					automatisch dessen ID in das ausgewähltes Textfeld kopiert			|
|															|
|	Vordergrund		->	Das Fenster bleibt dauerhaft im Vordergrund					|
|															|
+-----------------------------------------------------------------------------------------------------------------------+
|															|
|	Fehlerbehebung:													|
|															|
|		Der Reader ist angeschlossen und iArdu wurde gestartet aber es werden keine IDs der Chips angezeigt	|
|															|
|			-> Den Reader neu anschließen und das Programm neu starten					|
|															|
|		Der Reader wird nicht erkannt bei Start									|
|															|
|			-> Der Reader muss im Geräte-Manager(Anschlüsse COM & LPT) als "Arduino ..." bekannt sein.	|
|			   Falls das nicht der Fall sein sollte sind die Treiber nicht richtig installiert.		|
|															|
+-----------------------------------------------------------------------------------------------------------------------+
|															|
|	Wichtig:													|
|															|
|	Schließen Sie den Reader zuerst an den Computer an bevor Sie das Programm starten, da sonst der Reader		|
|	eventuell nicht erkannt wird.											|
|															|
+-----------------------------------------------------------------------------------------------------------------------+
|															|
|	Credits:													|
|															|
|	Programmiert und getestet von Reisacher Oliver, 2019								|
|															|
+-----------------------------------------------------------------------------------------------------------------------+