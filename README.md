# Birbante 0.4 — Android nativa GPS + ricerca reale

Questa versione usa:
- permessi Android `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`;
- Google Play services Fused Location Provider per ottenere una posizione corrente;
- MapLibre Native Android per la mappa;
- Nominatim/OpenStreetMap per la ricerca manuale dei luoghi nell'area della posizione.

Aprire con Android Studio. È necessario un ambiente Android SDK/Gradle. La ricerca Nominatim è volutamente manuale e include User-Agent applicativo.

Nota: il progetto è sorgente predisposto; l'ambiente ChatGPT non contiene un toolchain Android completo, quindi l'APK non è dichiarato compilato/verificato qui.
