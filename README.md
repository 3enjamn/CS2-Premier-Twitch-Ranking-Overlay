# Counter-Strike 2 Premier Rank Overlay For OBS.
### A clean, minimalist overlay for displaying CS2 Premier Mode stats in real-time. Perfect for streamers and content creators who want to show off their ranking progress.

<img alt="Premier Status Overlay" src="https://i.imgur.com/k1DI3hU.png">

## Setup Instructions
### Download both files:

* PremierStatus.html - The main overlay file
* styles.css - The styling for the overlay

### Configure your Steam ID:
> Open PremierStatus.html in any text editor (Notepad, VS Code, etc.)

>Locate the Configuration section (around line 56)

>Replace the PLAYER_UUID value with your own Steam ID:

### Finding your Steam ID:

>In Steam client, click on your profile name

>Right-click on your profile page and select "Copy Page URL"

>The long number in the URL is your Steam ID (17 digits)

>Alternatively, use a site like SteamID.io to find your ID

## Add as Browser Source:
> In OBS Studio, click the "+" button in the Sources panel

> Select "Browser" source

> Name it "CS2 Premier Stats" (or whatever you prefer)

> Check "Local file" and browse to select your PremierStatus.html file

> Set Width to 448 and Height to 55

> Click "OK" to add the source

---

### Verify your Steam ID is correct (17 digits)
* Ensure your CS2 game details are set to public in Steam privacy settings
* Check if the API is responding by opening https://api.jakobkristensen.com/YOUR_STEAM_ID in your browser
* Recent matches may take some time to appear in the API after you've played

> Important Notes
Your Steam profile must be public for the API to access your stats
The overlay is designed to be compact and minimalist
Data automatically refreshes based on your configured interval
This uses the unofficial CS2 Premier Stats API by Jakob Kristensen
