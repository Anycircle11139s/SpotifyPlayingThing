# SpotifyPlayingThing
My Spotify Display is a small desktop device that shows the current song playing on my Spotify account. It runs on an ESP32-S3 Nano and uses a 1.8” ILI9341 LCD screen. I added my own feature which is a coloured playback status bar that lights up when music is playing, and a small front design on the case. I made this beause I love small devices and I love music, and this was a combination of them both.

# Features:

- Shows current track info (song name, artist, maybe album).

- Connects to Wi‑Fi and talks to the Spotify API.

- Playback status bar that changes based on whether music is playing.

- 3D‑printed case that holds the screen and ESP32.

Images:
Ok so basically it wont let me drag and drop images into github, so after troubleshooting for an hour i gave up, can u pls just check the images folder, im dieing
<img width="1104" height="875" alt="Screenshot 2026-03-11 at 12 22 24 am" src="https://github.com/user-attachments/assets/b6c059e1-c506-47e5-bf7c-3d077d9a605b" />

## Bill of Materials

| #  | Name                     | Purpose                              | Cost (USD) | Qty | Total (USD) | Distributor | Link |
|----|--------------------------|--------------------------------------|-----------:|----:|------------:|------------|------|
| 2  | 20 AWG Wire              | For soldering, initial prototyping   | 3.50       | 1   | 3.50        | AliExpress | [Buy](https://www.aliexpress.com/item/1005006897578592.html) |
| 3  | MX Switches (Red)        | Controls                             | 3.10       | 1   | 3.10        | AliExpress | [Buy](https://www.aliexpress.com/item/1005006425450443.html) |
| 4  | Self‑tapping screws M3×14| Connect top and bottom case          | 1.50       | 1   | 1.50        | AliExpress | [Buy](https://www.aliexpress.com/item/1005002305365113.html) |
| 5  | Nuts (M3)                | Fasten the LCD                       | 1.60       | 1   | 1.60        | AliExpress | [Buy](https://www.aliexpress.com/item/1005006435394607.html) |
| 6  | ESP32‑C3                 | Main MCU                             | 6.17       | 1   | 6.17        | AliExpress | [Buy](https://www.aliexpress.com/item/1005004740051202.html) |
| 7  | 2.8" ILI9341 LCD         | Display to show content              | 8.63       | 1   | 8.63        | AliExpress | [Buy](https://www.aliexpress.com/item/32847628219.html) |
| 8  | Female‑female jumper wires| Connect components during prototyping| 3.00      | 1   | 3.00        | AliExpress | [Buy](https://www.aliexpress.com/item/1005005501503609.html) |
| 9  | Screws (M3×6 mm)         | Fasten the LCD                       | 4.00       | 1   | 4.00        | AliExpress | [Buy](https://www.aliexpress.com/item/1005006995421098.html) |
| 10 | Male headers             | Solder onto the dev board            | 1.80       | 1   | 1.80        | AliExpress | [Buy](https://www.aliexpress.com/item/4000988113226.html) |
| 11 | Design credit            | Inspired/adapted from `AAhil78`      | —          | —   | —           | —          | —    |
