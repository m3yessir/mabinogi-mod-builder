# Mooncrest

**Mabinogi Mod Builder with an adjustable FOV slider** · Built with **mabi-pack2** · Optional launcher integration powered by **Rua**

Choose your mods, adjust your FOV, and apply them together in one `.it` package. Mooncrest includes an Installed tab for reviewing and removing packages, saved selections, and optional Nexon account linking through Rua.

## Download

**Bundled mods:** Mooncrest 0.7.5 includes [Uiscias v1.65.0](https://github.com/Root50199/Uiscias/releases/tag/v1.65.0), plus Mooncrest’s exclusive mods.

### [Download Mooncrest 0.7.5 beta](https://github.com/m3yessir/mabinogi-mod-builder/releases/download/v0.7.5-beta/Mooncrest-0.7.5.zip)

[Release notes](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.5-beta) · [All releases](https://github.com/m3yessir/mabinogi-mod-builder/releases)

Download **Mooncrest-0.7.5.zip** and extract the entire folder. The `mooncrest-app-v2` and `builder-data-v2` files are updater assets; GitHub’s **Source code** ZIP is not the ready-to-run app.

## What’s new in 0.7.5

**Main Title Hider now covers family relationship labels, custom guild titles, and “the One with a Hunch who is,” while keeping character names visible.** Update your mod data, select Main Title Hider, and click **Apply mods** with Mabinogi closed.

The family and custom guild title definitions are omitted locally to skip their special formatting. This may also affect those entries in the title-selection menu. Other special titles may remain. No DLL injection or executable patching is used for this mod.

If you tested a combined title-test package, remove it from the game’s package folder before applying your normal selections. The public title mod does not include the test bundle’s other selected mods or FOV settings.

## Recent releases

| Version | Highlights |
| --- | --- |
| [0.7.5](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.5-beta) | Expanded Main Title Hider for family labels, custom guild titles, and the One with a Hunch title. |
| [0.7.4](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.4-beta) | **Load selections** from a matching installed Mooncrest package, including its saved FOV settings. |
| [0.7.3](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.3-beta) | Visible startup/update progress, quicker startup when no update is pending, and a signed launcher upgrade. |
| [0.7.2](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.2-beta) | Clear restart instructions when an update is already downloaded, instead of a conflicting manual-download message. |
| [0.7.1](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.1-beta) | Expanded indoor FOV, a separate app-update button, update-ready alerts, and compatible overlapping FOV/declutter changes. |

See [all release notes](https://github.com/m3yessir/mabinogi-mod-builder/releases) for details.

## Adjustable FOV

The slider covers supported outdoor maps and **255 fixed indoor regions**, including Tara Castle, the Arcana Association room, the Great Hall, and Guild Hall, with 63 room-variation files for supported interiors. Supported overlapping zoom and declutter mods keep their selected changes when the FOV override is applied.

Generated dungeon floors are not covered, and some included interiors have not been individually tested in game. The FOV feature uses .it packages and does not inject a DLL.

## Restore an installed package’s selections

Open **Installed**, select a matching Mooncrest-installed .it package, and click **Load selections**. Mooncrest restores its saved mod checkboxes and FOV settings, then opens the Mods tab. This replaces your current selections; nothing is installed until you click **Apply mods**.

The package must match its saved installation record in that Mooncrest installation. Unknown or changed files, copied packages without a matching record, missing mods, and invalid FOV records cannot restore selections.

### Already using 0.7.x?

**You do not need to download the full ZIP again.** Close Mabinogi and Rua, use **Check for app update**, and close and reopen Mooncrest when prompted. In 0.7.0, use its combined **Check for mods update** or the startup check. After updating mod data, click **Apply mods** with the game closed to rebuild your selected package.

Users upgrading from before 0.7.3 may still see one slow startup with the old launcher. Once the updated app opens, close it normally once so the launcher upgrade can finish; subsequent launches show progress. Avoid repeatedly clicking the shortcut while it starts. Users on 0.6.x need a fresh full download for signed-update support.

## Getting started

1. Extract Mooncrest into a folder you can write to, outside Mabinogi’s `package` folder. Keep the extracted files together.
2. Open **Mooncrest.exe** normally.
3. Choose **Nexon**, **Steam**, or **Custom**, then select your Mabinogi installation folder. Mooncrest locates its package folder.
4. If you use Nexon, optionally connect your account to check game updates and launch through Rua. You can skip linking to use the mod builder. Steam users update and launch through Steam.
5. With Mabinogi closed, select your mods, optionally enable **Global FOV Override**, then click **Apply mods**.
6. For a linked Nexon installation, click **Play Mabinogi** and approve the Windows administrator prompt for Rua. Mooncrest itself runs normally. Cancelling the prompt cancels launch.

## Updates

Mooncrest checks for published mod and app updates at startup and periodically while idle. You can also use **Check for game update**, **Check for mods update**, and **Check for app update**. Game updates and Mooncrest updates are separate.

An update-ready popup appears when a newer app version has downloaded. App updates are applied when you reopen Mooncrest with Mabinogi and Rua closed. Updated mod data must be rebuilt and applied to update the installed package. Normal app updates preserve local settings and backups in the **Data** folder.

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
