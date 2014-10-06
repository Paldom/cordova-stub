cordova-stub
============

PhoneGap / Cordova stub to run and develop cordova apps in desktop browser.

# installation

Insert cordova-stub.js file to your cordova project (`www` folder recommended) and make a reference to it in index.html or your main html file. Be sure to put it <b>after</b> cordova.js reference (`<script src='cordova.js'></script>`)

    <script>
        window.device || document.write("<script src='cordova-stub.js'>\x3C/script>")
    </script>
