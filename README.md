![image](https://github.com/user-attachments/assets/490f33d6-edc5-4214-9177-3fcca5f71407)

Gra Steam :
https://store.steampowered.com/app/860020/EXFIL/

Oficjalny Discord Exfil :
https://discord.gg/playexfil





PL Linux  Ubuntu Jak Postawić Serwer.

Na root zaktualizuj maszynę pod serwer Exfila

sudo add-apt-repository multiverse

sudo dpkg --add-architecture i386

sudo apt update

sudo apt install steamcmd

Następnie utwórz  nowego użytkownika  adduser nick/nazwa
Zalogój się na nowego użytkownika

Użyj komendy steamcmd po zalogowaniu się na użytkownika w celu wywołania steam na linuxie do instalacji.

w steamcmd wpisz :
1.    force_install_dir /home/exfil/serwer  ///podjaj swoją lokalizacje instalacji
2.    login anonymous    ///logowanie się do steam, tutaj nic nie zmieniaj
3.    Normalny Serwer  app_update 3093190 validate   ///komenda na instalację serwera
4.    Demo Serwer   app_update 3093190 -beta demo validate
5.    exit   ///wpisz po zainstalowaniu się serwera

Udaj się do folderu gdzie zainstalowałeś serwer i możesz go już wystartować 
./ExfilServer.sh -queryport=nr portu  "przykładowo  ./ExfilServer.sh -queryport=27015"

Szybkie Komendy Na Instalacje 
 Zwykły Serwer    steamcmd +force_install_dir some_install_directory +login anonymous +app_update 3093190 validate +quit

 Demo Serwer      steamcmd +force_install_dir some_install_directory +login anonymous +app_update 3093190 -beta demo validate +quit  


Pliki CFG/Konfiguracja serwera jak nazwa opis admin itp  przykład /home/exfil/serwer/Exfil/Saved/ServerSettings

Przykładowe pliki CFG :
![image](https://github.com/user-attachments/assets/6064cd8f-7d25-4655-b4b6-522c4895db44)

Podanik By Szogo GL&HF

Mój Discord :

https://discord.gg/szogowaty

Szogowaty YT / Szogo YT / Shogo_Boomer Twitch
