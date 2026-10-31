# Magic 8 Ball (self-contained web app)

Open `index.html` in a full web browser: the ball appears immediately (even if JavaScript or WebGL is unavailable). Tap the ball, or shake your phone, to draw one of the 20 traditional Magic 8 Ball responses. There is no question field.

**If the chat/file preview is blank:** some in-app file previewers don't render HTML apps; this is a limitation of the preview rather than the app. Open the file in a browser or deploy these files as a static website.

**Phone shaking on iPhone:** deploy the unzipped folder to HTTPS hosting (GitHub Pages, Netlify, Cloudflare Pages, etc.), open it in Safari, tap the ball once to grant Motion & Orientation access, and then shake the phone. A local downloaded `.html` file and most in-app preview windows won't grant motion access. On Android, sensor access is browser dependent and normally needs HTTPS too.

**Home screen:** once hosted over HTTPS, Safari Share > Add to Home Screen. After visiting once the app can cache assets for offline use. No third-party libraries, accounts, or analytics required. 
