# IT-Projekt: Virtuelle Firewall-Infrastruktur mit pfSense

## Überblick
Dieses Projekt demonstriert die Einrichtung einer sicheren Netzwerkumgebung unter Verwendung von **pfSense 2.8.1** als Firewall und **Kali Linux** als Client in einer virtualisierten Umgebung (VirtualBox).

## Technische Details
* **Firewall:** pfSense 2.8.1-RELEASE (amd64).
* **Netzwerk-Konfiguration:** Interne Netzwerk-Schnittstelle namens "LABORATORIO PRIVADO".
* **IP-Adressierung:**
    * pfSense LAN: 192.168.1.1/24.
    * Kali Linux Client: 192.168.1.50 (Statisch konfiguriert).

## Troubleshooting
Während des Projekts wurde ein Verbindungsproblem zwischen Kali Linux und pfSense gelöst, indem die Netzwerkschnittstellen manuell synchronisiert und die IP-Routing-Tabelle in Kali Linux angepasst wurde.
