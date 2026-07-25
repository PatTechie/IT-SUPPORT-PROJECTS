# TROUBLESHOOTING

## ISSUE 1: USER REPORTS NO NETWORK CONNECTIVITY

#### Theory: Network Adapter disabled

#### Test: Checked Device Manager and adapter showed as disabled

#### Plan: Re-enable adapter via Device Manager

#### Fix: Right-clicked adapter and enabled device

#### Outcome: Connectivity restored and ping test successful

**Screenshots:**
Broken state => Fixed state

![Adapter disabled](screenshots/issue1-broken.png) ![Adapter enabled](screenshots/issue1-fixed.png)



## ISSUE 2: USER REPORTS DISPLAY LOOKS STRETCHED AND ICONS TOO LARGE

#### Theory: Display resolution has been changed

#### Test: Opened Display Settings - resolution set to 800xgoo instead of recommended

#### Plan: Restore resolution to recommended setting

#### Fix: Changed resolution back to 1920x1080 (Recommended)

#### Outcome: Display return to correct resolution, user confirmed normal

**Screenshots:**
Broken state => Fixed state

![Adapter disabled](screenshots/issue2-broken.png) ![Adapter enabled](screenshots/issue2-fixed.png)





## ISSUE 3: USER CANNOT ACCESS FOLDER - "ACCESS DENIED ERROR" RECEIVED

#### Theory: NTFS permissions incorrectly configured with Deny rule

#### Test: Checked Security tab of folder and it turns out that the Deny permission is applied to user account

#### Plan: Remover Deny rule and restore appropriate Allow permissions

#### Fix: Edited NTFS permissions, removed Deny and granted Allow full control.

#### Outcome: Permission issue resolved and Folder now accessible

**Screenshots:**
Broken state => Fixed state

![Adapter disabled](screenshots/issue3-broken.png) ![Adapter enabled](screenshots/issue3-fixed.png)
