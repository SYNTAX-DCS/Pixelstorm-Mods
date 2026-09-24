# Pixelstorm Mods

One small app that installs the aircraft mods the **Pixelstorm** DCS server flies, and
switches them on and off again without you ever touching your DCS install by hand.

Built by **Pixel Pilot Club**. Unofficial, and not affiliated with Eagle Dynamics.

---

## Why it exists

You want to see the other aircraft on the server on a Sunday night, without learning OVGME or
working out which mod goes where. Tick what you want and press Apply.

When you are finished with Pixelstorm, press **Disable All** and DCS is exactly as it was. The
mods stay on your disk, so switching them back on next week is instant and costs no download.

---

## Install

1. Download **[PixelstormMods.exe](../../releases/latest/download/PixelstormMods.exe)**.
2. **Close DCS.**
3. Run it. It finds your DCS folders on its own.
4. Tick the mods you want and press **Apply**.
5. Start DCS.

To take one mod out again, untick it and press Apply. To take them all out, press
**Disable All**. To get rid of a mod completely, right-click its row and delete it.

---

## Finished with Pixelstorm?

Press **Disable All**. Every Pixelstorm mod goes off, and every file one of them changed is put
back, so DCS is exactly as it was before this app touched it.

Forgetting is fine. Flying your own missions with the mods on is no problem at all, and it
only matters on a server that checks your files (see below).

---

## What is in the pack

| aircraft | made by |
| --- | --- |
| Su-30 FlankerEx (CWS) | Codename Flanker |
| Su-35S (EFM) | Codename Flanker |
| F-22A Raptor (MK II EFM) | GrinnelliDesigns, EFM by BHOOP Studios |
| Su-34 Red Flag Fighters | awentyy, alexey1111 |
| Rafale B, C, M and BM | FR-3D Studio |
| Rafale engine sounds (optional) | FR-3D Studio |
| A400M Atlas (tanker) | FR-3D Studio |
| A330 MRTT Phenix (tanker) | FR-3D Studio |

3,941 files, 13.04 GB once installed, 8.45 GB to download. You do not have to take all of
them; tick only the ones you want.

**These aircraft are their authors' work, not ours.** They are packed here as their authors
shipped them, with two exceptions described below: the Su-34 and the Rafale both carry our
changes. This app installs them and gets out of the way. If you fly one and enjoy it, go and
tell the person who made it. **Any author who would rather their mod was not distributed here
only has to say so and it comes out of the pack.**

### The Su-34

Su-34 Red Flag Fighters needs Su-30 FlankerEx alongside it for its textures and part of its
avionics. Tick the Su-34 and the Su-30 comes with it automatically, in the right order. It flies
on the Su-33's flight model, so flying it needs the Su-33 from Flaming Cliffs 3.

It carries our fixes. It is renamed Su-34_RFF, so that its own weapons, ELINT pod and flight
tuning are used instead of those of the Su-34 built into DCS, and its cockpit, electrics and
radar warning receiver are fixed to work with that.

### The Rafale

FR-3D Studio's Rafale installs itself over the stock F/A-18C, and its French weapons change the
AMRAAMs, Mavericks and Sidewinders of every aircraft in DCS. The Rafale here is the same aircraft,
repackaged so that it sits beside the stock Hornet and leaves DCS's own aircraft and weapons
alone:

- Everyone who ticks it sees Rafales on the server. Flying one needs the **F/A-18C module**,
  because the Rafale flies on the Hornet's systems.
- It carries DCS's standard weapons under their standard names, so a stock Hornet's weapons stay
  exactly as they are.
- Its engine sound is a tick box of its own, off unless you want it. It works by replacing DCS's
  shared jet sounds, so while it is on, other jets that use them (mostly AI) sound like a Rafale
  too.
- A few fixes for this setup: the joystick bindings, some cockpit textures, and where the ATFLIR
  pod hangs.

---

## What it does to your DCS

Most mods are aircraft, and they go in `Saved Games\DCS\Mods` as folders of their own.
Switching one off moves its folder to a parked area inside your DCS write directory, where
DCS does not look. That is why switching back on is instant.

When the pack carries a newer build of a mod you already have, its row turns amber, and Apply
swaps the old build for the new one. A mod that did not change is never downloaded again.

Some mods change files inside your DCS installation, the program folder itself. Pixelstorm runs
with file checks off, so that is fine there. Before such a mod replaces a file, the app keeps a
copy of yours, and Disable All puts each one back.

A DCS update can land while one of those mods is on and put its own version back over part of
the mod. The app notices: the mod's row turns amber, and Apply puts the mod's files back. When
you later switch it off, any file DCS updated in the meantime stays as DCS has it now. It is
never swapped for an older copy.

Windows protects `C:\Program Files`. If DCS lives there and a mod needs to change it, Windows
asks for permission once and the app carries on by itself. Mods that live in Saved Games never
need that.

The app changes nothing while DCS is running, so close DCS first.

If you already installed one of these mods yourself, the app finds it, says so, and offers to
take charge of it. It will not write over it, and it will not delete it.

### If you use OVGME or JSGME

You can keep using them. Just do not point both tools at the same aircraft.

OVGME installs a package by copying it into your DCS folder and keeping its own record of
what is enabled. This app switches a mod off by moving the folder somewhere safe. If both
are managing the same aircraft, OVGME still believes it is installed while the files have
moved, and the next time you disable it there it will try to restore backups over a folder
that is no longer where it left it.

So pick one owner per aircraft:

- **For the aircraft in this pack**, disable them in OVGME and let this app have them.
  It will ask you to confirm you have done that before it takes one over.
- **For everything else** you install, carry on with OVGME exactly as before. This app only
  ever touches the folders and files its own mods use, and ignores the rest of your DCS.

The same goes for files inside your DCS installation. If one of your OVGME mods changes a
file that a Pixelstorm mod also changes, keep only one of them switched on.

There is no way for this app to detect OVGME, which is why it asks rather than guesses:
OVGME leaves no marker in the DCS folder and nothing in the registry.

### Will this stop me joining other servers?

Servers that require pure scripts or pure models refuse a DCS whose own files have been
changed. An aircraft that only adds a folder in Saved Games does not count as a change, so on
its own it will not get you refused.

A mod that changes files inside your DCS installation does count. Press Disable All before you
fly on one of those servers, and DCS is exactly as it was.

---

## The Pixelstorm sky

If you use ATMOS-X, a **Pixelstorm sky** button appears once the server's sky profile has been
published. It saves the profile and tells you how to load it in ATMOS-X, so your sky is drawn
the way the server's is. The weather itself comes from the mission, with or without ATMOS-X.

---

## Files and space

Downloads are split into parts and checked against a SHA-256 before anything is unpacked, so
an interrupted or corrupted download cannot leave you with a half-installed aircraft. If your
connection drops, run it again and it picks up where it stopped.

Copies of any DCS files a mod replaces are kept in `Saved Games\DCS\_PixelstormMods\backup`
until that mod is switched off again.

**Do not download the mod archives by hand from the Releases page.** They are split files and
the parts mean nothing on their own. Let the app fetch them.

---

## Problems

The app writes a log. Right-click a mod and choose **Check the files**, or open an issue here
and say what the app told you.
