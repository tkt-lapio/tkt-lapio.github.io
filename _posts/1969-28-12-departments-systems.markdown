---
layout: material
title: "The CS department's systems"
date: 1969-12-28 00:00:05 +0200
permalink: /departments-systems/
tag: info-eng
---
<div class="warning">
    This part of materials mentions CS account, which will probably be removed at some point. Materials will be updated once state of CS accounts become more clear. CS account is not required for any of courses exercises.
</div>

- If you are a CS major or minor, please activate university account [here](https://helpdesk.it.helsinki.fi/en/instructions/logging-and-connections/user-account/activating-new-username) and your CS account according to [these](https://www.cs.helsinki.fi/en/compfac/user-accounts) instructions.

- The university offers its students two ways for wireless internet connection: Eduroam and HUPnet. You can also get guest access to HUPnet. HUPnet is not secured, so we heavily recommend using Eduroam. You can also access it in some campus sites overseas. Instructions on installing Eduroam are found [here](https://helpdesk.it.helsinki.fi/en/instructions/logging-and-connections/networks/setting-eduroam-installer-package). You can also install it on your mobile device: [Android](https://helpdesk.it.helsinki.fi/en/instructions/computer-and-printing/mobile-devices/eduroam-on-android-devices) and [iPhone](https://helpdesk.it.helsinki.fi/en/instructions/computer-and-printing/mobile-devices/ipad-and-iphone-wireless-connections).

- The CS departmens offers several servers for accessing your personal university AD home folder. Login using your university account.

  - melkki.cs.helsinki.fi
  - melkinpaasi.cs.helsinki.fi
  - shell.cs.helsinki.fi
  - melkinkari.cs.helsinki.fi


<div class="warning">
If you use the department's servers over SSH connection and have added your private key to an SSH-agent, according to university regulations you have to secure the private key with a password.
</div>

- In addition to the AD home folder, you get a CS home folder located in `/cs/home/your_username`, accessible from the departments systems. You can publish your own home page to https://www.cs.helsinki.fi/u/your_account_name by creating an HTML file to `/cs/home/tunnus/public_html/index.html`.

- The departments also has computing cluster called [Ukko2](https://wiki.helsinki.fi/display/it4sci/Ukko2+User+Guide) and [Kale](https://wiki.helsinki.fi/display/it4sci/Kale+User+Guide). Access to these clusters is limited to the department staff and those who have applied for separate access right.

- Do not run sudo commands in the CS department's systems. Such behaviour is logged as malicious.

- If you are a CS major, you get the following emails from the university:

  - `firstname.lastname@helsinki.fi` (AD account)
  - `username@cs.helsinki.fi` (CS account)
  - `firstname.lastname@cs.helsinki.fi` (CS account) --> redirected to `username@cs.helsinki.fi`

  [Here](https://www.cs.helsinki.fi/compfac/ohjeet/posti/index.en.html) are some instructions, which are unfortunately somewhat outdated: for example Mappi is not used anymore. Each CS student is generated an Office 365 mail, which you can access using your AD account (use `username@ad.helsinki.fi` as the username) in [here](http://www.helsinki.fi/office365/). In addition, [here](https://helpdesk.it.helsinki.fi/en/collaboration-and-publication/office-365/office-365) is some info regarding Office 365. You can for example reserve some rooms from University's libraries using the calendar. You can access the `cs.helsinki.fi` mail from [here](https://webmail.cs.helsinki.fi/lite/) by using your CS account.
  
  **We recommend choosing to use just one mail, and redirecting the mail from either from helsinki.fi to cs.helsinki.fi ([instructions](https://helpdesk.it.helsinki.fi/en/instructions/collaboration-and-publication/e-mail/directing-e-mail-away-office-365)) or the other way around.**
