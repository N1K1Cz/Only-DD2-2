# Only DD2 #2

<b> Podstawowy opis paczki Only DD2 #2 (aby samemu sprawdzić paczkę zgłoś się do właściciela poprzez discorda)
	
## Compatibility
- 1.9-dev+5235 (tylko na tej wersji testowałem)

### Configuration

<details>
  <summary><b>Co należy zrobić po wgraniu paczki na serwer?: </b></summary>

```
1. Musisz zmienic IP swojego serwera w DD2_Silnik i przekompilowac
2. Zmieniasz informacje w Kontakcie o wlascicielu serwera 
3. W razie klopotu pisz do mnie
4. W pluginie DD2_reklama ustaw "amx_reklama_dozwolona" - cvar ustaw tam nazwe swojej sieci i przekompiluj (lub w amxx.cfg)
5. W silniku DD2 ustaw DD2_forum nazwe swojego forum i przekompiluj (lub dodaj na koncu w amxx.cfg DD2_forum "nazwa")
6. Zalecam ustawic czas do wybuchu c4 na 30sek. (licznik wtedy bedzie dobrze dzialal) - mp_c4timer "30" w server.cfg
7. Najpierw prosze wrzucic cala paczke a dopiero potem zmieniac rzeczy w pluginach 
8. W razie problemow z wychodzeniem z spawn z TT (chwilowy lag w jednym miejscu) prosze wylaczyc plugin DD2_ShowEQ. (na niektórych hostingach powoduje ten błąd)
```
</details>

### ScreenShots

<details>
	<summary><b>Zdjęcia przedstawiające podstawowe działanie paczki:</b></summary>
- Wygląd HUD:
	
<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/hud.png"></img>

- Menu główne serwera:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/menu.png"></img>

- Wygląd kontaktu:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/kontakt.png"></img>

- Menu opis VIP:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/menu_motd.png"></img>

- Menu VIP:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/menu_vip.png"></img>

- Powitanie na czacie:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/powitanie_czat.png"></img>

- Powitanie w HUD:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/powitanie_hud.png"></img>

- Sklep MVP:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/sklep_mvp.png"></img>

- Sklep MVP - Kupno:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/sklep_mvp_kup.png"></img>

- Sklep MVP - Ustawianie:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/sklep_mvp_ustaw.png"></img>

- Opis VIP:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/vip_opis.png"></img>

- Opis SVIP:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/svip_opis.png"></img>

- Wiadomość na czacie:

<img src="https://github.com/N1K1Cz/Only-DD2-2/blob/main/zdj/czat.png"></img>

</details>

### Lista pluginów:

<details>
  <summary><b>Lista pluginów na serwerze: </b></summary>

```
;//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
;//=-=-=-=-=           ONLY DD2 2022 by N1K1Cz | AmxxPro.pl /\^-^/\      =-=-=-=-=//
;//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//

;//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
;//=-=-=-=-=             Silnik i najwazniejsze pluginy     /\^-^/\      =-=-=-=-=//
;//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//

DD2_Silnik.amxx               ; Silnik DD2
DD2_SystemVIPSVIP.amxx        ; System VIP & SVIP
DD2_stattrak.amxx             ; StatTrak
DD2_rozgrzewka.amxx           ; Rozgrzewka
DD2_monety.amxx               ; System Monet

;//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
;//=-=-=-=-=                       Pluginy Dodatkowe        /\^-^/\      =-=-=-=-=//
;//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//

DD2_AntyRush.amxx             ; AntyRush
in_game_ads.amxx              ; Potrzebne do dzialania antyrush
DD2_obrazenia.amxx            ; Zadawane obrazenia w DHUD
DD2_bs_limiter.amxx           ; BombSide B od 5 CT
DD2_ad_manager.amxx           ; Reklamy w say (advertisements.ini)
DD2_admin_freelook.amxx       ; Free Look dla Admina
DD2_admin_spec_esp.amxx       ; ESP pomagajace adminowi sprawdzac czy gosciu ma cheaty
DD2_afkbombtransfer.amxx      ; Transfer Paki gdy jestes AFK
DD2_c4.amxx                   ; Licznik C4
DD2_duszek_po_smierci.amxx    ; Duszek po smierci
DD2_grenade_trail.amxx        ; Linia rzucenia granata
DD2_efekt_bron.amxx           ; Efekt ktory pozwala latwiej zobaczyc bron
DD2_flash.amxx                ; Info kto nas oslepil
DD2_logs.amxx                 ; Logi DD2
DD2_granat_info.amxx          ; Info o rzucanym granacie
DD2_inf_smierc.amxx           ; 5sek. Info po smierci
;DD2_Najlepszy.amxx            ; Najlepszy gracz rundy (wylaczone gdyz sklepMVP ma ta funkcje wbudowana)
DD2_parachute.amxx            ; Spadochron
DD2_skiny.amxx                ; Skiny
DD2_sounds.amxx               ; Dzwieki po killu
DD2_vip_dla_steam.amxx        ; VIP dla steam
DD2_ShowEQ.amxx               ; Hajs bronie itp. na poczatku rundy nad glowa graczy
DD2_speclist.amxx             ; Info kto nas obserwuje
DD2_reklama.amxx              ; Blokada Reklam
DD2_shortnade.amxx            ; Rzut granata na krotki dystans pod PPM
DD2_BackWeapon.amxx           ; Bron na plecach
DD2_messenger.amxx            ; Wiadomosci prywatne do innych graczy
DD2_podnoszeniebroni.amxx     ; Podnoszenie broni pod E jak w csgo
DD2_asystaZemsta.amxx         ; Asysta i Zemsta
DD2_SklepMVP.amxx             ; Sklep Muzyk MVP - zastepstwo za roundsound
```
</details>
