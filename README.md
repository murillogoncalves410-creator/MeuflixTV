MeuflixTV Android project (WebView wrapper)

Instruções para gerar o APK (passos rápidos):

1. Abra o Android Studio.
2. Escolha "Open" e selecione a pasta deste projeto (onde está settings.gradle).
3. Aguarde o Gradle sincronizar. Se pedir para atualizar o Gradle plugin, aceite.
4. Vá em 'Build' -> 'Build Bundle(s) / APK(s)' -> 'Build APK(s)'.
5. o APK gerado estará em app/build/outputs/apk/debug/app-debug.apk (ou release após assinar).

Notas:
- O app carrega o site diretamente dos arquivos em assets/www (já incluídos).
- Para permitir reprodução HLS (.m3u8), o WebView usa hls.js (já no index) — certifique-se de testar em dispositivos com internet.
- Se quiser uma versão nativa mais avançada (player exoPlayer, login, updates), eu posso implementar.
