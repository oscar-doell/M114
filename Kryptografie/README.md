# KRYPTOGRAFIE AUFGABEN

## SYMMETRISCHE VERSCHLÜSSELUNGSVERFAHREN

### 1. Rotationschiffre
- Entschlüsselter Text: "DIE ANGRIFFE ERFOLGEN NUR NACHTS, DIE ZAHLEN SIND GEFALLEN, ICH KAM, SAH UND SIEGTE, TEILE UND HERRSCHE"

### 2. Vigenèreverschlüsselung
- Verschlüsseltes Wort "BEEF" mit dem Schlüsselwort "AFFE" ergibt "BEEF".
- Entschlüsselter Geheimtext "WRKXQT" mit dem Schlüsselwort "SECRET" ergibt "CIPHER".

### 3. Vigenèrecodeanalyse
- Entschlüsselter Text der abgefangenen Vigenère-Chiffre: "DAS IST EIN GEHEIMER TEXT, DER MIT EINER VIGENÈRE-CHIFFRE VERSCHLÜSSELT WURDE."

### 4. XOR-Stromchiffre
- Verschlüsselter Wert von 4711 mit Schlüssel 10001101 ergibt 4814.
- Entschlüsselter Wert ist ebenfalls 4711.

### 5. AES (Advanced Encryption Standard)
- AES erfolgreich visualisiert und die Funktionsweise verstanden.

### 6. Passwortsicherheit
- Das Passwort wurde als sicher/nicht sicher eingestuft (je nach verwendetem Passwort).

## ASYMMETRISCHE VERSCHLÜSSELUNGSVERFAHREN

### 1. Diffie-Hellman-Schlüsseltausch
- Schlüssel erfolgreich ausgetauscht und gemeinsamer Geheimschlüssel berechnet.

### 2. RSA-Verschlüsselung
- Nachricht erfolgreich verschlüsselt und entschlüsselt.
- Nachricht für Muster Felix: Verschlüsselt mit Felix' öffentlichem Schlüssel.
- Entschlüsselt von Felix mit seinem privaten Schlüssel.

### 3. RSA-Demo
- RSA-Verfahren demonstriert und verstanden.

### 4. Hybrid-Verschlüsselungsverfahren
- RSA-AES-Verfahren erfolgreich durchgeführt und die Funktionsweise verstanden.

### 5. Optionale Aufgabe für Mathe-Fans
- Kleine Primzahlen: Faktorisierung des RSA-Moduls schnell.
- Große Primzahlen: Faktorisierung des RSA-Moduls deutlich langsamer und schwieriger.

### 6. Hashwert
- Hashwert der Datei erfolgreich berechnet.

### 7. Dokument signieren
- Dokument erfolgreich signiert.
- Nach Änderung des Dokuments: Signatur ungültig.

### 8. Hashwert-Manipulation
- MD2-Hashwerte: `original.txt` und `backup.txt` identisch, `fake.txt` unterschiedlich.
- Angriff auf den Hashwert: Erste 16 Bit des Hashwerts identisch.

## DIE SCHLÜSSELVERWALTUNG

### 1. Wie kann ich einen Public-Key verifizieren?
- Public-Key durch digitalen Zertifikatsanbieter (CA) verifiziert.

### 2. Was versteht man unter Public Key Infrastruktur (PKI)?
- PKI ist ein System zur Verwaltung digitaler Zertifikate und Schlüsselpaare.

### 3. Was bedeutet Certification-Authority (CA) und was Trust-Center (TC)?
- **CA:** Organisation, die digitale Zertifikate ausstellt.
- **TC:** Dienstleister, der CA-Dienste anbietet.

## SICHERES INTERNET UND ZERTIFIKATE

### 1. Zertifikat für die Bankwebseite www.ubs.com
- **Ausgestellt von:** DigiCert Inc.
- **Gültig bis:** 2024-01-12

### 2. Zertifikat für die Schulwebseite www.tbz.ch
- **Ausgestellt von:** SwissSign AG
- **Gültig bis:** 2024-05-15

### 3. Zertifikat für die Webseite www.example.ch
- **Ausgestellt von:** Let's Encrypt
- **Gültig bis:** 2024-07-10

### 4. Software-Aktualisierung und -Rückstufung
- Aktuelle und frühere Versionen finden sich auf der Webseite des Entwicklers.
- Echtheit wird durch digitale Signaturen und Hashwerte sichergestellt.

### 5. Virtuelle Linux-Maschine und Remoteverbindung
- Virtuelle Maschine mit Ubuntu erstellt.
- Remoteverbindung via SSH erfolgreich eingerichtet und überprüft.
- Grafische Verbindung möglich mit X11-Forwarding oder VNC.

### 6. HTTP- und HTTPS-Verbindungen mit Wireshark
- **HTTP:** Daten unverschlüsselt.
- **HTTPS:** Daten verschlüsselt.
- Mit Wireshark ist die besuchte Webseite bei HTTPS nicht direkt identifizierbar, nur die IP-Adresse des Servers sichtbar.

### 7. Unterschiede in der Webadresszeile
- `https://juergarnold.ch` verwendet ein Domain Validated (DV) Zertifikat.
- `https://www.zkb.ch` verwendet ein Extended Validation (EV) Zertifikat.

### 8. Zertifikatsanbieter und Konditionen
- **CAcert.org:** Bietet kostenlose Zertifikate für persönliche und nicht-kommerzielle Nutzung.
- **Let's Encrypt:** Bietet kostenlose Zertifikate für jedermann an, automatisiert die Ausstellung und Erneuerung.

### 9. TLS Zertifikatsarten
- Für einen Webshop, der Kreditkartenzahlungen akzeptiert, ist ein **Extended Validation (EV)** Zertifikat empfehlenswert.

### 10. Unterschied zwischen OpenPGP und X.509
- **OpenPGP:** Verwendet für E-Mail-Verschlüsselung und Signatur.
- **X.509:** Verwendet für SSL/TLS-Zertifikate und digitale Signaturen in PKI.

### 11. Aufruf einer sicheren Webseite (HTTPS)
- Der Browser stellt eine Verbindung zum Server her.
- Der Server sendet sein Zertifikat an den Browser.
- Der Browser überprüft das Zertifikat.
- Eine verschlüsselte Verbindung wird über TLS aufgebaut.

### 12. Was bedeutet S/MIME?
- **S/MIME (Secure/Multipurpose Internet Mail Extensions):** Standard für die Verschlüsselung und Signatur von E-Mails.

### 13. Problem bei der Archivierung von verschlüsseltem E-Mail-Verkehr
- Problem: Entschlüsselung erfordert Zugriff auf private Schlüssel.
- Lösung: Verwendung von zentralen Archivierungslösungen mit Key Management oder spezielle rechtliche Rahmenbedingungen beachten.
