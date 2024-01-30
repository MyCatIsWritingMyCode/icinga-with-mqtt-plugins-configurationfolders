Diese Datei enthält Erklärungen zu den hochgeladenen Ordnern

/icinga2
dieser Ordner enthält alle Configurationsdateien

/icinga2/conf.d/api-users.conf enthält zwei API benutzer.
Für konfiguration wurde der Benutzer "icingaweb2" verwendet.

/icinga2/features-enabled ist leer, da die features auf den lokalen Station enabled werden müssen.

/icingadb enhält eine Datenbank .yaml Konfigurationsdatei, dort ist der Benutzer "user" angelegt.
Für die Schnittstelle zum Redisserver, wurde dort der Port 6380 festgelegt. 

/icingaweb2
dieser Ordner enthält alle Configurationsdateien für die Icinga Weboberfläche und die verwendeten Module wie den Director

/icingaweb2/enabledModules ist leer, das die Module lokal aktiivert werden müssen

/usr/lib/nagios/plugins enthält die zwei Verwendeten Plugins
Für das Plugin check-mqtt.py muss paho-mqtt installiert sein

Originallinks der Plugins:
https://github.com/check-plugins/check_mqtt
https://github.com/hobbyquaker/check_mqtt

Orignalpfad icinga2, icingadb & icingaweb2: /etc/icinga*
Originalpfad Plugins: /usr/lib/nagios/plugins


In der Textdatei commandlines.txt, befinden sich die benutzten Kommandos, welche über den Icingaweb Director implementiert werden können.
