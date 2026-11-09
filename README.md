# zanaxu-radios

Public page and radio app list of **Zanaxú Radios**: https://yovanyjls.github.io/zanaxu-radios/

- `index.html`: the public page, with one card per radio app linking to Google Play.
- `radios.json`: the list of radio apps, newest first. The "More radios" screen inside each app reads it too.
  ```json
  { "version": 1, "radios": [ { "package": "com.zanaxu.example", "name": "Example", "icon": "icons/com.zanaxu.example.png" } ] }
  ```
- `icons/<package>.png`: 192×192 icons.
