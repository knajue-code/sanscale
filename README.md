# sanscale

Statische Unternehmenswebsite von sanscale.

## Lokal ansehen

`python3 -m http.server 8765 --directory dist`

## Netlify

Veröffentlichungsverzeichnis: `dist`. Kein Build-Schritt erforderlich.

Die Website bleibt zunächst auf `noindex`. Vor dem Umzug Hostingangaben in der Datenschutzerklärung anpassen, FormSubmit für kontakt@sanscale.de aktivieren und die endgültige Danke-Seiten-Adresse im versteckten Formularfeld `_next` setzen. JavaScript verwendet bereits die aktuelle Domain.

Formularversand: FormSubmit. Hosting und Formularversand sind unabhängig.
