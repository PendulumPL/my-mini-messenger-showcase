# My Mini Messenger

**Nieoficjalny klient Messengera na Windows. Przeczytaj wiadomość i odpisz z dymka, bez przełączania okna.**

[Zobacz demo (26 s, MP4)](assets/demo-pl.mp4) · [Centrum powiadomień](assets/center-pl.png)

![Dymek wiadomości z polem odpowiedzi, przyciskiem Wyślij i czterema gotowymi odpowiedziami](assets/notification-pl.png)

## Jak to działa

- **Szybka odpowiedź.** Nowa wiadomość pojawia się w rogu ekranu. Możesz wpisać odpowiedź, wybrać gotowy tekst albo otworzyć rozmowę.
- **Centrum powiadomień.** Wiadomości od różnych osób trafiają do jednego miejsca. Możesz przejrzeć historię, zobaczyć podgląd multimediów i dopisać lokalną notatkę do rozmowy.
- **Tryb prywatny.** Rozmywa treść i multimedia w powiadomieniach, gdy udostępniasz ekran.

## Od usterki do poprawki

Po wpisaniu hasła formularz logowania potrafił utknąć na animacji ładowania. Diagnostyka wskazała, że filtr blokujący wyjście z Messengera odcinał też etap weryfikacji dwuetapowej. Dopuściłem konkretną ścieżkę weryfikacji, sprawdziłem reguły w testach automatycznych i potwierdziłem logowanie w aplikacji na Windows.

**Technologie** · Rust, Tauri 2, JavaScript i WebView2. Testy automatyczne obejmują między innymi reguły nawigacji i zachowanie interfejsu powiadomień.

**Stan projektu** · Beta 0.2.8 dla Windows x64, interfejs po polsku i angielsku. Demo pokazuje interfejs na fikcyjnych danych z symulowanym wysyłaniem odpowiedzi.

## English

My Mini Messenger is an unofficial Windows desktop client for Messenger. Reply from a small notification, then get back to what you were doing. A local notification center collects messages, media previews and conversation notes. Built with Rust, Tauri 2, JavaScript and WebView2. The [26-second demo](assets/demo-pl.mp4) shows the Polish interface with fictional messages and simulated replies.

---

Projekt portfolio autorstwa [PendulumPL](https://github.com/PendulumPL). Niezależny od Meta Platforms. Nazwa i znak Messenger należą do ich właściciela.
