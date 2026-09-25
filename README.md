<div align="center">

# Lynn Messenger

**Veilige, end-to-end versleutelde chat voor Windows, macOS en Linux.**

Praat, bel en deel bestanden zonder dat iemand kan meelezen. Ook wij niet.

### [Download de nieuwste versie](../../releases/latest)

</div>

---

## Wat is Lynn Messenger?

Lynn Messenger is een moderne desktop-chatapp. Je berichten, spraakberichten, bestanden en videogesprekken zijn volledig end-to-end versleuteld: alleen jij en de persoon met wie je praat kunnen de inhoud lezen. De servers verwerken uitsluitend versleutelde gegevens die ze zelf niet kunnen ontcijferen.

## Downloads

Kies het installatiebestand voor jouw systeem op de [Releases-pagina](../../releases/latest):

| Platform | Bestand |
| :-- | :-- |
| Windows (64-bit) | `Lynn-Messenger-Setup-<versie>.exe` |
| macOS (Apple Silicon) | `Lynn-Messenger-<versie>-arm64.dmg` |
| Linux (64-bit) | `Lynn-Messenger-<versie>.AppImage` |

De Windows-installer is voorzien van een geldig code-signing-certificaat en de macOS-app is ondertekend met een Apple Developer ID en genotariseerd door Apple. Je krijgt dus geen waarschuwing van SmartScreen of Gatekeeper bij het installeren.

## Beveiliging en encryptie

Lynn Messenger is gebouwd rond het bewezen Signal-protocol.

- **Berichten.** Elke chat gebruikt het Signal-protocol (X3DH en PQXDH voor de sleuteluitwisseling, plus de Double Ratchet). Dat levert forward secrecy en post-quantum bescherming. Alleen de deelnemers bezitten de sleutels.
- **Wachtwoord.** Aanmelden verloopt via OPAQUE, een password-authenticated key exchange. Je wachtwoord verlaat nooit je apparaat, de server krijgt het letterlijk nooit te zien.
- **Bestanden, foto's en spraakberichten.** Elk bestand wordt met een eigen willekeurige sleutel versleuteld en als onleesbare blob opgeslagen. De server bewaart alleen versleutelde bytes.
- **Profiel.** Je naam, status en persoonlijk bericht zitten in een versleutelde profiel-blob. De sleutel delen alleen jij en je contacten.
- **Instellingen.** Worden als versleutelde blob gesynchroniseerd. De server ziet de inhoud nooit.
- **Aflever-wachtrij.** Versleutelde envelopes worden na aflevering gewist (crypto-shredding).

De cryptografie leunt op breed gecontroleerde bouwstenen (libsignal en de noble-libraries).

## Functies

- End-to-end versleutelde 1-op-1 gesprekken
- Spraakberichten en versleuteld videobellen
- Bestanden en foto's veilig delen
- Emoticons in gesprekken
- Werkt op Windows, macOS en Linux

## Automatische updates

De app controleert bij het opstarten op nieuwe versies. Updates worden op de achtergrond gedownload en bij een herstart geinstalleerd, zodat je altijd de nieuwste en veiligste versie draait. Nieuwe versies verschijnen op dit release-kanaal.

## Systeemvereisten

- **Windows:** Windows 10 of nieuwer, 64-bit
- **macOS:** macOS 11 (Big Sur) of nieuwer, Apple Silicon (M1 en nieuwer)
- **Linux:** een recente 64-bit distributie (AppImage)

## Vragen of feedback?

Loop je ergens tegenaan of heb je een suggestie? Open gerust een [issue](../../issues) op deze pagina.
