![Intro](https://scamprotect.xyz/examples/intro.png)

![Intro](https://scamprotect.xyz/examples/features.png)

Scamprotect is a Security Bot protecting your server from unwanted links (Phishing/Viruses/Token Grabbing) and unwanted users (Alt accounts/JoinBots/DMBots)

 - **Anti-alt System**:  Detect alts accounts that join your server with the Captcha protection
 - **Anti-bot System**:  Protect your server from joinbots and DMbots (Mass-DM) with the Captcha protection
 - **Anti-VPN System**: Prevent users from using VPNs and Proxies
 - **Anti-Phishing System**: Block unwanted links like Phishing and Viruses
 - Kick accounts that were created recently (Configurable age requirement)
 - Multiple languages supported!

<details>
<summary>ℹ Open Documentation</summary>
<br>
  
How captcha Works - Full Video => https://scamprotect.xyz/examples/scamprotect_tuto.mp4


**👤 USER COMMANDS** 

- ` /help `  Shows a list of available commands
- ` /info `  Gives information about the bot
- ` /report report_user `  Send a user report to the moderation team (⌛ 1 minute)
- ` /report report_link `  Send a link report to the moderation team (⌛ 1 minute)
- ` /support `  Displays the support server
- ` /invite `  Displays the bot's invite link
- ` /userinfo `  Display informations about yourself or another User in the server
- ` /get_link_info `  Get information about a link in the database



**🔨 MODERATION COMMANDS** (Required Permissions: **Ban members**)

- ` /members_scan `  Scans the entire member list (⌛ 15 minutes)
- ` /scam_scan `  Scans all the channels to find scam links (⌛ 60 minutes)
- ` /whitelist `  Adds/Removes a user from the whitelist
- ` /getalts `  Check User's alternative accounts (📛)
- ` /ban_user_alts `  Ban a user and all of his registered alternative accounts (📛)
- ` /kick_recent_accounts `  Kicks all users below the configured required age
- ` /kick_unverified_accounts `  Kicks all users without the verified role
- ` /give_unverified_role `  Gives the unverified role to users that don't have the verified role



**🔧 ADMINISTRATION COMMANDS** (Required Permissions: **Administrator**)

- ` /config view `  See the bot's current configuration
- ` /config toggle_scam_protection `  Enables/Disables the scam/phishing link protection
- ` /config toggle_scam_ai `  Enables/Disables the ScamAI protection
- ` /config toggle_global_blacklist `  Enables/Disables the Blacklist protection
- ` /config toggle_age_requirement `  Enables/Disables the kicking of recent accounts
- ` /config toggle_deletion_message `  Enable/Disable sending a message after a link is deleted from the chat
- ` /config set_age_required `  Set the minimum required age an account needs to join the server
- ` /config change_language `  Change the language of the bot
- ` /config set_protection `  Change the punishment when a link is sent
- ` /mentions `  Add/Remove a role that will be mentioned when a suspicious link is detected (**max 5 roles**)
- ` /exempted_channels `  Add/Remove/List Exempted Channels
- ` /custom_links `  ⭐ Scamprotect+ Only: Add/Remove/List Custom Whitelisted/Blacklisted links
- ` /config set_logs_channel `  Sets the logs channel
- ` /config remove_logs_channel `  Removes the logs channel



**🔐 CAPTCHA COMMANDS** (Required Permissions: **Administrator**)

- ` /setup_captcha `  Setup the captcha system easily
- ` /captcha set_captcha_channel `  Set the captcha channel
- ` /captcha remove_captcha_channel `  Removes the logs channel
- ` /captcha manage_captcha_message `  Configure the captcha message
- ` /captcha set_verified_role `  Set the role given when users verifies themselves
- ` /captcha set_unverified_role `  Set the role given to users when they join the server without being verified
- ` /captcha remove_verified_role `  Removes the verified captcha role
- ` /captcha remove_unverified_role `  Removes the unverified captcha role
- ` /captcha toggle_captcha_kick `  Enable/Disable kicking account who have not been verified until a given time
- ` /captcha toggle_alts_kick `  Enable/Disable kicking alts account
- ` /captcha set_captcha_kick_delay `  Set the number of minutes before kicking non-verified account
</details>

