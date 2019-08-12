# iArdu - iButton Reader

  Liest ein iButton Chip aus und gibt dessen ID an den Computer weiter.
  Die ID kann am Computer mit der mitgelieferten Software eingelesen und für weitere Zwecke verwendet werden.

# Installation

  1. Schließen Sie den Reader an den Computer an und lassen Sie Windows die Treiber dafür installieren.
     Falls Windows die Treiber nicht automatisch installiert, müssen diese manuell nachinstalliert werden:
     
     1. Gehen Sie in den Geräte-Manager(Windows-Suche) und suchen Sie den Eintrag "Arduino Leonardo" bzw "Unbekanntes Gerät" unter "Anschlüsse"
     2. Machen Sie einen Rechtsklick auf den Eintrag und wählen Sie "Treiber aktualisieren"
     3. Wählen Sie "Auf dem Computer nach Treibersoftware suchen" und geben Sie als Pfad den iArdu-Ordner an.
     4. Warten Sie bis die Installation erfolgreich durchgeführt wurde.
     
  2. Starten Sie die Anwendung "setup.exe" und folgen Sie den Anweisungen des Einrichtungsassistenten.
  3. Entfernen Sie kurz den Reader vom Computer und schließen ihn wieder an. 
  4. Starten Sie das Programm "iArdu"
 
# Nutzung

   Textfeld              -> Hier wird die ID des Chips angezeigt. Die ID kann hier markiert und kopiert werden.
   
   Kopieren               -> Kopiert die ID in die Zwischenablage
   
   Löschen                -> Löscht das Textfeld
   
   Automatisch Einfügen   -> Falls dieses Häckchen gestzt wurde wird bei jedem Einlesen eines Chips automatisch dessen ID in das ausgewählte Textfeld kopiert
   
   Vordergrund            -> Das Fenster bleibt dauerhaft im Vordergrund
   
# Fehlerbehebung
 
   Der Reader ist angeschlossen und iArdu wurde gestartet aber es werden keine IDs angezeigt
   
      -> Den Reader neu anschließen und das Programm neu starten
      
   Der Reader wird nicht erkannt beim Startvorgang
   
      -> Der Reader muss im Geräte-Manager(Anschlüsse COM & LPT) als "Arduino ..." bekannt sein.
         Falls das nicht der Fall sein sollte sind die Treiber nicht richtig installiert.
         
# Wichtig

   Schließen Sie den Reader zuerst an den Computer an bevor Sie das Programm starten, da sonst der Reader eventuell nicht erkannt wird.
   
# Credits

  Programmiert und getestet von Reisacher Oliver, 2019
