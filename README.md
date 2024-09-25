Installasjonsveiledning for å sette up Raspberry Pi 4


Hvordan å sette opp OS

1. Installer Raspberry Pi Imager på PCen din fra https://www.raspberrypi.com/software/ og klikk "Download for Windows". (Eller annet noe annet, hvis du ikke bruker Windows.)
2. Legg inn SD kortet fra Raspberry Pien til SD leseren på PCen/Laptopen.
3. Åpne filen du installerte som heter noe som "imager_1.8.5"
4. Etter det har lastet ned, åpne programmet.
5. Når du åpner, så må du velge 3 ting for å fortsette.
6. På "Raspberry Pi Device" velg "Raspberry Pi 4"
7. På "Operating System" bla litt ned til du finner "Other general-purpose OS" og velg Ubuntu (Velg den øverste valget som er 64 bit).
8. På "Choose Storage" velg SD kortet som du satt inn.
9. Klikk "Next" også trykk "Yes".
10. Vent til installasjonen er ferdig.
11. Når installasjonen er ferdig, ta SD kortet ut og legg den inn tilbake til Raspberry Pien.
12. Følg instruksjonene på Pien for å installere ferdig OS.

Hvordan å installere programmer på Ubuntu

1. Åpne terminalen (Ctrl + alt + T)
2. I terminalen skriv i følgende rekkefølge:
   - sudo apt update
   - sudo apt upgrade
   
4. Nå skal vi installere brannmur via terminalen.
5. I terminalen skriv i følgende rekkefølge:
   - sudo apt install ufw
   - sudo ufw enable
   - sudo ufw allow ssh
   - sudo ufw status (Bare for å sjekke om brannmuren er aktivert.)

6. Nå skal vi installere ssh via terminalen.
7. I terminalen skriv i følgende rekkefølge:
   - sudo apt install openssh-server
   - sudo systemctl enable ssh
   - sudo systemctl start ssh
   
