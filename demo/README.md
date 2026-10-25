# Nexo IPTV — public reviewer demo / Demostración para revisión

This folder is a **small, optional playlist sample for technical review** of Nexo IPTV, an Android media player. It is **not** a service that provides television channels, playlists, subscriptions, logins, or commercial IPTV content.

## Reviewer links / Enlaces para los revisores

- **M3U playlist / lista M3U:** https://bohdansosnytskyy-crypto.github.io/nexo-iptv-privacy/demo/lista-prueba.m3u
- **XMLTV programme guide / EPG:** https://bohdansosnytskyy-crypto.github.io/nexo-iptv-privacy/demo/guia-prueba.xml
- **Privacy policy / política de privacidad:** https://bohdansosnytskyy-crypto.github.io/nexo-iptv-privacy/

## Usage in the Android app (English)

1. Launch Nexo IPTV. Select the section for adding an M3U playlist from URL.
2. Name it `Nexo demo` (or another non-sensitive local name).
3. Paste the M3U playlist URL above. The `x-tvg-url` header supplies a companion XMLTV sample.
4. Open **Big Buck Bunny · Demo (Blender CC BY 3.0)**, and check that its demo stream starts and playback controls operate.
5. Return to channel browsing to inspect the demonstration EPG. The guide contains two **simulated** program entries per day, with absolute UTC offsets (`+0000`) to avoid DST ambiguity.
6. Open Settings → Privacy policy; the external privacy page should load without login.

**No username or password is required for this M3U test playlist.** Xtream-specific server credentials are not supplied; reviewing full Xtream integration would require a separate lawful, dedicated account provided through Play Console's App access instructions.

## Important limitations / Limitaciones importantes

- **This is a VOD demonstration used as an M3U stream entry, not a genuine linear/live TV broadcast.** It reaches its natural end; it does not transmit a live channel.
- The XMLTV data is **synthetic test data**, not the actual schedule of the streamed film. Do not interpret it as a real TV guide.
- This project does **not** host or redistribute the media bytes. Playback references a third-party test HLS stream published by Mux: https://test-streams.mux.dev/x36xhzz/x36xhzz.m3u8 . The original host controls its availability and may change or disable it. Verify playback from the intended test device before submitting to Google for review.
- The XMLTV schedule covers **24 October 2026 through 31 December 2028**; regenerate it if the review occurs after that period.
- This demo is intended to help reviewers navigate the app, **not** to become a catalog bundled into Nexo IPTV.
- This repo is public. **Do not commit passwords, private playlists, tokens, personal data or support emails** here.

## Film attribution / Atribución

**Big Buck Bunny** (2008) — (c) copyright 2008, Blender Foundation / www.bigbuckbunny.org.

Licensed under the Creative Commons Attribution 3.0 license (CC BY 3.0) for the underlying work:
- https://peach.blender.org/about/
- https://creativecommons.org/licenses/by/3.0/

The Mux public test HLS stream is referenced without copying it. Nexo IPTV is independent from, and is not endorsed by, Blender Foundation or Mux.

## Español — pasos abreviados

1. Abre Nexo IPTV y añade una lista **M3U por URL**.
2. Ponle un nombre, por ejemplo `Nexo demo`, e introduce el enlace de la lista indicado arriba.
3. Reproduce **Big Buck Bunny · Demo** y comprueba los controles. Es una película de prueba, no un canal en directo.
4. La EPG de prueba se declara en el encabezado y muestra datos **simulados**.
5. La app no proporciona cuentas Xtream ni contenido comercial, y esta demostración no incluye credenciales.
