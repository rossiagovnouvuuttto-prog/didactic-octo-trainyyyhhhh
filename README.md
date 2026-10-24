# СвойЧат — Android APK

Android-мессенджер на Kotlin: личные чаты, регистрация по email и экспериментальные голосовые звонки через Firebase и WebRTC.

Исходники упакованы в `project-source.tar.xz.b64`; GitHub Actions распаковывает их и собирает debug APK. В Actions → **Build Android APK** → последний запуск → **Artifacts** скачайте `SvoyChat-debug-apk`.

**Важно:** пока в GitHub Actions не добавлен `GOOGLE_SERVICES_JSON_B64` с конфигурацией Firebase, APK показывает экран настройки, реальные чаты и звонки не работают. Для готового онлайн-сервиса также включите Firebase Authentication, Firestore и установите правила из `firestore.rules`. Звонки требуют активного приложения и могут не работать без TURN-сервера.

Для подробных инструкций скачайте архив исходников и прочитайте включённый README.
