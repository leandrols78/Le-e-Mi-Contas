LE & MI CONTROLE DE CONTAS PESSOAIS — COMO GERAR O APK ANDROID

Este pacote já contém o aplicativo completo (www/index.html), o ícone (www/icon.jpg),
o manifest.json (PWA) e a configuração do Capacitor pronta para compilar o APK.

OPÇÃO 1 — SEM PROGRAMAR (MAIS RÁPIDA, PELO NAVEGADOR)
1. Publique a pasta www/ gratuitamente no GitHub Pages ou Netlify Drop (https://app.netlify.com/drop).
2. Acesse https://www.pwabuilder.com/, cole a URL publicada e clique em "Package For Stores" -> Android -> Download APK.
   (Ou abra a URL no Chrome do Android -> Menu -> "Instalar aplicativo").

OPÇÃO 2 — GERAR APK NATIVO COM CAPACITOR + ANDROID STUDIO
Requisitos no PC: Node.js 18+ e Android Studio instalados.
1. Extraia este ZIP e abra o terminal na pasta extraída.
2. Execute:
   npm install
   npx cap add android
   npx cap sync android
   npx cap open android
3. No Android Studio: Build -> Build Bundle(s) / APK(s) -> Build APK(s).
4. Copie o app-debug.apk para o celular Android e instale.
