# Getting started

## The package folder

GrayDR is delivered as a dated package folder. Beside the packages sits one set of launchers that always point at the newest package, so you never have to find the right folder yourself:

| Launcher | Opens |
|---|---|
| Launch GrayDR | The game window. |
| Launch Configuration Studio | The settings editor on its own, without a game window. |
| Launch Data Editor | The editor for spells, hunting zones, command answers, crafting tools and the travel map. |
| Launch Account Board | The window that watches every logged-in character. |

Your settings are not inside the package. They live in the **profiles** folder beside the packages, so a new package never loses them.

## Logging in

The quickest way is the **Sessions Launcher**, under the Window menu of the GrayDR window.

- **Add Account...** saves an account, its password and the server (Prime, Test or Fallen) once. GrayDR keeps the login itself; you do not type the password again.
- Each row is one character. **Launch** logs that character in. Tick several rows and press **Launch All** to log them in one after another, top to bottom; the **Log in earlier** and **Log in later** arrows set that order.
- **Remove** forgets a row and its saved login.

Every character gets its own GrayDR window.

You can also log in by hand from the File menu:

- **Connect** opens the connection wizard: account, password, server, then the character. "Remember password" and "Auto-login next time" do what they say.
- **Connect from SAL (with Lich)...** takes a launch file you already got from the Simutronics launcher and connects through Lich. This is the old way and is only there for comparison.

## Profiles

A profile is one complete set of settings. The **Profile** menu creates and loads them. Most people have one, called default. The Configuration Studio always edits the profile that is loaded.

## When something changes

- A change you save in the Configuration Studio is read by the next script that starts. You do not restart GrayDR for it.
- A new package needs GrayDR closed and started again from the launcher.
- A change in the Data Editor is read the next time a script starts.
