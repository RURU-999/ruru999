RURU999 Firebaseアプリ
1. Firebase Hosting等のHTTPSホスティングに index.html / manifest.webmanifest / sw.js を配置してください。
2. Firebase AuthenticationでGoogleプロバイダを有効にし、Authentication > Settings > Authorized domains に公開ドメインを追加してください。
3. Firestoreルールは users/{userId}/{document=**} に対して request.auth.uid == userId の条件を使います。
4. 公開後、Android Chromeでサイトを開き「ホーム画面に追加」を選びます。
注意: このZIPはアプリのソース一式です。まだFirebase Hostingへの公開はされていません。ネット接続が必要です。データはGoogleログインしたユーザーの users/{uid}/ 以下に保存します。
