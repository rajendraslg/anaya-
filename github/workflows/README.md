# Anya Assistant (Starter, Kotlin)

Features:
- Hinglish/Indian English voice reply (Text-to-Speech)
- Voice input using device Speech Recognizer
- Simple animated avatar (image swap while speaking)
- Local memory with Room (remembers your name and facts)
- GitHub Actions builds APK without Gradle wrapper

## Build (GitHub)
1. Create a repo (public recommended).
2. Upload all files from this ZIP (keep folder structure).
3. Ensure `.github/workflows/android.yml` exists.
4. Go to **Actions** → run workflow → download artifact **Anya-Assistant-APK** → install `app-debug.apk`.

## Notes
- For best Hinglish recognition, set device language to English (India) and Hindi keyboards installed.
- Avatar images are placeholders; replace in `app/src/main/res/drawable/`.
