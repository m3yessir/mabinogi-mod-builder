# Mooncrest

**Mabinogi Mod Builder with an adjustable FOV slider** · Built with **mabi-pack2** · Optional launcher integration powered by **Rua**

Choose your mods, adjust your FOV, and apply them together in one `.it` package. Mooncrest includes an Installed tab for reviewing and removing packages, saved selections, and optional Nexon account linking through Rua.

## Download

**Bundled mods:** Mooncrest 0.7.1 includes [Uiscias v1.65.0](https://github.com/Root50199/Uiscias/releases/tag/v1.65.0), plus Mooncrest’s exclusive mods.

### [Download Mooncrest 0.7.1 beta](https://github.com/m3yessir/mabinogi-mod-builder/releases/download/v0.7.1-beta/Mooncrest-0.7.1.zip)

[Release notes](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.1-beta) · [All releases](https://github.com/m3yessir/mabinogi-mod-builder/releases)

Download **Mooncrest-0.7.1.zip** and extract the entire folder. The `mooncrest-app-v2` and `builder-data-v2` files are updater assets; GitHub’s **Source code** ZIP is not the ready-to-run app.

## What’s new in 0.7.1

- **Expanded indoor FOV:** the slider now covers 255 fixed indoor regions, including Tara Castle, the Arcana Association room, the Great Hall, and Guild Hall. Outdoor coverage is retained, with 63 room-variation files added for supported interiors.
- **Separate app-update button:** use **Check for app update** alongside the game and mod update buttons.
- **Update-ready popup:** Mooncrest now alerts you when a newer app version has downloaded and is ready to install after a restart.
- **Compatible mod combinations:** supported overlapping zoom and declutter mods keep their selected changes when the FOV override is applied.

Generated dungeon floors are not covered, and some included interiors have not been individually tested in game. The FOV feature uses `.it` packages and does not inject a DLL.

### Already using 0.7.0?

**You do not need to download the full ZIP again.** Close Mabinogi and Rua, open Mooncrest, and let its startup check finish. You can also click **Check for mods update** in 0.7.0, which checks for app updates too. When the status says the update is downloaded, close and reopen Mooncrest, then click **Apply mods** to use the expanded FOV coverage.

The new app-update button and popup become available after installing 0.7.1; 0.7.0 displays its update notice in the status area.

## Getting started

1. Extract Mooncrest into a folder you can write to, outside Mabinogi’s `package` folder. Keep the extracted files together.
2. Open **Mooncrest.exe** normally.
3. Choose **Nexon**, **Steam**, or **Custom**, then select your Mabinogi installation folder. Mooncrest locates its package folder.
4. If you use Nexon, optionally connect your account to check game updates and launch through Rua. You can skip linking to use the mod builder. Steam users update and launch through Steam.
5. With Mabinogi closed, select your mods, optionally enable **Global FOV Override**, then click **Apply mods**.
6. For a linked Nexon installation, click **Play Mabinogi** and approve the Windows administrator prompt for Rua. Mooncrest itself runs normally. Cancelling the prompt cancels launch.

## Updates

Mooncrest checks for published mod and app updates at startup and periodically while idle. You can also use **Check for game update**, **Check for mods update**, and **Check for app update**. Game updates and Mooncrest updates are separate.

In 0.7.1, an update-ready popup appears when a newer app version has downloaded. App updates are applied when you reopen Mooncrest with Mabinogi and Rua closed. Updated mod data must be rebuilt and applied to update the installed package. Normal app updates preserve local settings and backups in the **Data** folder.

### Signed updates

Starting with 0.7.0, Mooncrest verifies a digital signature before accepting app or mod-data updates. App signatures are checked again before installation. Updates with missing or invalid signatures are rejected. Only the public verification key is included in the download; the publisher’s private signing key is not distributed.

These update signatures are separate from Windows executable signing. They help reject unauthorized updates, but do not guarantee that software is vulnerability-free or protect a compromised Windows account.

## Managing your saved Nexon account

In the Nexon connection window:

- **Unlink** disconnects the account from Mooncrest while keeping Rua’s saved login.
- **Remove saved account** asks for confirmation, then deletes the selected local Rua credential and profile. This also affects standalone Rua using that profile on the same Windows account. You will need to sign in again to use it.

Removal does not delete your Nexon account, revoke sessions on Nexon’s servers, or clear browser cookies. Account linking remains optional.

## Credits

- **m3yessir** — Mooncrest and exclusive mod releases. The name is inspired by Tiara Moonshine.
- **[Rii / riistar — Rua](https://github.com/riistar/Rua)** — optional Nexon sign-in, game updates, and launching. Included with the author’s permission.
- **[Root50199 and Uiscias contributors](https://github.com/Root50199/Uiscias)** — credited mod groups and variants, with original authors and documentation included.
- **[regomne](https://github.com/regomne/mabi-pack2) and [ShaggyZE](https://github.com/shaggyze/mabi-pack2)** — mabi-pack2 archive tooling.

Full credits, mod documentation, and dependency notices are included in **CREDITS.md**, **docs**, and **tools**.

No personal account profiles, credentials, saved user settings, or logs are included in the release download. Mooncrest remains a beta and an unofficial fan project, unaffiliated with Nexon.
<img width="1040" height="938" alt="image" src="https://github.com/user-attachments/assets/03adb4b4-ae6c-4547-9db3-416c96042a35" />
<img width="1029" height="934" alt="image" src="https://github.com/user-attachments/assets/1a96bd2b-a3f2-47e6-87ee-c0c21c8321c9" />
