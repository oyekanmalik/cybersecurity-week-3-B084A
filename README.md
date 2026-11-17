Hands-On Lab: Cracking a Password-Protected PDF with John the Ripper

week 3



As part of my cybersecurity training, I recently completed a hands-on password cracking lab focused on recovering a lost password from an encrypted PDF file — a scenario that mirrors real-world password recovery and penetration testing exercises.



The workflow:



Hash Extraction — Using pdf2john (via OnlineHashCrack's PDF Hash Extractor), I converted the encrypted PDF into a crack-able hash format compatible with John the Ripper.



Tool Setup — Installed John the Ripper (Jumbo version) and configured Johnny, its GUI front-end, pointing it to the correct executable path.



Cracking the Hash — Loaded the extracted hash into Johnny and launched the attack. John the Ripper successfully recovered the password in a matter of seconds, demonstrating just how quickly weak or common passwords can fall to automated tools.



Result: Password successfully cracked and the PDF unlocked.



Key takeaway: This exercise was a great reminder of why strong, unique passwords matter. Tools like John the Ripper are built for legitimate security testing and password recovery — but they also show how fast a weak password can be defeated. Password strength isn't optional; it's a first line of defense.

#CyberSecurity #PasswordCracking #JohnTheRipper #EthicalHacking #InfoSec 

![screenshot]()
