
# Trophytron

A helper website designed to simplify viewing nominations on a livestream for an awards show, without having to manually create video files.

## Dependencies

[http-server](https://www.npmjs.com/package/http-server) (`npm i http-server`)

## How to run

Execute `http-server -c-1` on root, and open it up any of the available URLs. For the time being, only Chromium based browsers are compatible. (Sorry Firefox, I have betrayed you).

The nomination category shown is random. To pick a specific one, use the argument `slide` on the URL (for example: `http://192.168.1.39:8080?slide=best-actor/` will only show Best Actor Award).

Add or remove categories and nominees by editing the `nominees.json` file.

You can change the channel for Twitch Chat integration on the Client TMI initialization on the default and winners' screens (Jerma985, by default).
