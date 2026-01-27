# Ping-Spam-Selfbot

> **NOTE:** Selfbots are against Discord's ToS and can lead to account termination.  
> Use at your own risk and preferably on an alt account.
> this is also meant to be paired with a raid bot, one that doesnt have to be added. (idk what to name those lol)
---

## TUTORIAL:
https://youtu.be/OTggSbGrkMM?si=XsvFD_TWxxqNMYSL

## SETUP:

1. Click `Code` → Download as ZIP.
2. Uncompress it in your files.
3. Run `install.bat`.

---

## Getting your Discord Token:

<details>
    <summary>Method 1 (easy)</summary>
    <ol>
        <li>Add the extension that can be found <a href="https://chromewebstore.google.com/detail/accgjfooejbpdchkfpngkjjdekkcbnfd?utm_source=item-share-cb">here</a></li>
        <li>Open <a href="https://discord.com">Discord</a> in your browser and login</li>
        <li>Click on the extension</li>
        <li>Click the "Get Token" button</li>
        <li>Copy the token</li>
        <li>Open the <code>config.js</code> file</li>
        <li>Paste your token in the <code>token</code> variable</li>
        <li>Start the self-bot</li>
    </ol>
</details>

<details>
    <summary>Method 2 (harder)</summary>
    <ol>
        <li>Go to <a href="https://discord.com">https://discord.com</a>, sign in.</li>
        <li>Open your <strong>Developer Console</strong> (<code>Ctrl + Shift + I</code>) → go to the <strong>Network tab</strong>, then in filter search @me.</li>
        <li>Refresh the page, look for @me - scroll down till you see "authorization".</li>
        <li>copy everything to the RIGHT of authorization.</li>
        <li>Open the <code>config.js</code> file.</li>
        <li>Paste the token where it says <code>token</code>.</li>
        <li>Adjust the cooldowns to whatever you want.</li>
    </ol>
</details>
