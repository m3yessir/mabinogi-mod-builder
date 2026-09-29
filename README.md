# Mooncrest

**Mabinogi Mod Builder with an adjustable FOV slider** · Built with **mabi-pack2** · Optional launcher integration powered by **Rua**

Choose your mods, adjust your FOV, and apply them together in one `.it` package. Mooncrest includes an Installed tab for reviewing and removing packages, saved selections, and optional Nexon account linking through Rua.

## Download

**Bundled mods:** Mooncrest 0.7.0 includes [Uiscias v1.65.0](https://github.com/Root50199/Uiscias/releases/tag/v1.65.0), plus Mooncrest’s exclusive mods.

### [Download Mooncrest 0.7.0 beta](https://github.com/m3yessir/mabinogi-mod-builder/releases/download/v0.7.0-beta/Mooncrest-0.7.0.zip)

[Release notes](https://github.com/m3yessir/mabinogi-mod-builder/releases/tag/v0.7.0-beta) · [All releases](https://github.com/m3yessir/mabinogi-mod-builder/releases)

Download **Mooncrest-0.7.0.zip** and extract the entire folder. The `mooncrest-app-v2` and `builder-data-v2` files are updater assets; GitHub’s **Source code** ZIP is not the ready-to-run app.

**Upgrading from 0.6.3 or earlier?** Download the full ZIP once and extract it into a **new folder**. Version 0.7.0 adds the signature verifier needed for signed updates; the older updater cannot install that verifier. Complete setup in the new folder and use **Use saved account** if you already have a Rua profile. Future compatible updates use the signed updater.

## Getting started

1. Extract Mooncrest into a folder you can write to, outside Mabinogi’s `package` folder. Keep the extracted files together.
2. Open **Mooncrest.exe** normally.
3. Choose **Nexon**, **Steam**, or **Custom**, then select your Mabinogi installation folder. Mooncrest locates its package folder.
4. If you use Nexon, optionally connect your account to check game updates and launch through Rua. You can skip linking to use the mod builder. Steam users update and launch through Steam.
5. With Mabinogi closed, select your mods, optionally enable **Global FOV Override**, then click **Apply mods**.
6. For a linked Nexon installation, click **Play Mabinogi** and approve the Windows administrator prompt for Rua. Mooncrest itself runs normally. Cancelling the prompt cancels launch.

## Updates

Mooncrest checks for published mod and app updates at startup and periodically while idle. You can also use **Check for game update** and **Check for mods update**. Game updates and Mooncrest updates are separate.

App updates are staged and applied when you reopen Mooncrest with Mabinogi and Rua closed. Updated mod data must be rebuilt and applied to update the installed package. Normal app updates preserve local settings and backups in the **Data** folder.

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
- **[Rii / riistar — Rua](https://github.com/riistar/Rua)** — optional Nexon sign-in, game updating, and launching. Included with the author’s permission. Mooncrest includes a modified helper, not an official Rua release. Changes are provided as **Rua-changes.md** and **Rua-changes.patch** on the release page.
- **[Root50199 and Uiscias contributors](https://github.com/Root50199/Uiscias)** — credited mod groups and variants, with original authors and documentation included.
- **[regomne](https://github.com/regomne/mabi-pack2) and [ShaggyZE](https://github.com/shaggyze/mabi-pack2)** — mabi-pack2 archive tooling.

Full credits, mod documentation, and dependency notices are included in **CREDITS.md**, **docs**, and **tools**.

No personal account profiles, credentials, saved user settings, or logs are included in the release download. Mooncrest remains a beta and an unofficial fan project, unaffiliated with Nexon.
<img width="1040" height="938" alt="image" src="https://github.com/user-attachments/assets/03adb4b4-ae6c-4547-9db3-416c96042a35" />
<img width="1029" height="934" alt="image" src="https://github.com/user-attachments/assets/1a96bd2b-a3f2-47e6-87ee-c0c21c8321c9" />
