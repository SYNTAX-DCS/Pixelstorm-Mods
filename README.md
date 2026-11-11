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
| Su-22M4 | VinntoreZ |
| F-16I Sufa and six F-16D two-seaters | DCMii |
| Super Hornet and Growler, downloaded from CJS (see below) | Chiller Juice Studios |
| UH-60L Black Hawk, downloaded from Kinkku (see below) | Kinkku |
| GBU-39 SDB bomb, downloaded from Haack (see below; optional, Modern F-15E users skip it) | Haack |

The packed aircraft come to 6,970 files, 23.55 GB once installed, 16.61 GB to download. You do
not have to take all of them; tick only the ones you want.

**These aircraft are their authors' work, not ours.** They are packed here as their authors
shipped them, with four exceptions described below: the Su-34 and the Rafale both carry our
changes, the Su-22M4 has one folder taken out, and the F-16I Sufa leaves out some of DCMii's
files and renames a few others. The Super Hornet, the UH-60L and the SDB are not packed
here at all; they come from their makers. This app installs them and gets out of the way. If you
fly one and enjoy it, go and tell the person who made it. **Any author who would rather their mod was not distributed here
only has to say so and it comes out of the pack.**

The Su-35S needs Su-30 FlankerEx alongside it too, for part of its avionics. Tick the Su-35S and
the Su-30 comes with it automatically.

### The Su-34

Su-34 Red Flag Fighters needs Su-30 FlankerEx alongside it for its textures and part of its
avionics. Tick the Su-34 and the Su-30 comes with it automatically, in the right order. It flies
on the Su-33's flight model, so flying it needs the Su-33 from Flaming Cliffs 3.

It carries our fixes and comes as two aircraft. The Su-34 (AG) is the ground-attack version, with
the ELINT pod. The Su-34 (AA) uses the Su-33's avionics instead, for air-to-air radar modes and
helmet-aimed IR missiles. Both are renamed from the Su-34 built into DCS, so that their own
weapons and flight tuning are used, and their cockpit, electrics and radar warning receiver are
fixed to work with that.

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

### The Su-22M4

VinntoreZ's Su-22M4 is packed here with VinntoreZ's permission, with one folder taken out. The mod
carries 45 silent sound files in `Sounds\Speech`, and DCS loads a mod's sounds for every aircraft,
so they would mute DCS's English cockpit warnings ("Pull up", "Missile", "Bingo", "Gear down") in
other jets too. Without them the Su-22M4 uses the Su-27's warnings.

It flies on the Su-27's flight model, so flying it needs the Su-27, from Flaming Cliffs 3 or the
standalone module.

Installed it yourself from VinntoreZ's download? Your copy still has that `Sounds\Speech` folder.
Delete it, or remove your copy and let the app install the Su-22M4 for you.

### The F-16I Sufa

DCMii's F-16I Sufa is packed here with DCMii's permission. Six F-16D two-seaters come with it:
the Block 50 and 52, each with and without the spine, and the Barak 30 and 40. Flying any of
them needs the F-16C module.

The Sufa is built on ED's F-16C, so unlike the other aircraft here it goes into your DCS
installation. It replaces two of ED's files there, the F-16C's two `entry.lua` files, which is
how the new aircraft get added. If DCS is in `C:\Program Files`, Windows asks for permission
when you press Apply. Disable All puts ED's two files back. While it is on, a server that checks your files can refuse you
(see below).

The pack's copy is DCMii's 4.0.0 plus the fix DCMii sent on 4 November, which adds HUD and
helmet symbols the Sufa was missing. It has these differences:

- DCMii's rework of the standard F-16C is left out, its cockpit and exterior model included, so
  a stock F-16C stays as ED made it.
- The crew sync for two pilots in one jet is left out, because it replaces one of DCS's own
  multiplayer scripts, and so is the rear-seat HUD repeater, which is a DLL. The pack's copy is
  for one pilot per jet.
- DCMii's optional add-ons are left out: SPICE-2000, AGM-154B, Python-5, the AN/AAQ-33 pod and
  the PW-229 engine sounds.
- Nine cockpit textures are renamed and two fuel tank textures are left out. They had the same
  names as DCS's own, so they could repaint the stock F-16C's cockpit and fuel tanks.

Already have DCMii's own download installed? You can keep flying that on Pixelstorm, so you do
not need this one as well.

### The Super Hornet

The CJS Super Hornet is not in the pack. Chiller Juice Studios hand it out themselves and ask
that nobody else does, so none of it ever comes from us.

The app still lists it, as **Super Hornet and Growler (CJS)**: the F/A-18E, the F/A-18F and the
EA-18G. Tick it and press Apply, and a window lists the files to download. At the moment that is
CJS's 2.4.6 release (about 1 GB) and the 12 KB hotfix that goes over it, which CJS post on their
Discord. Each has a button that opens the page to get it from. Download them as you would
anything else. The app watches your
Downloads folder, checks each file is the exact one on its list, and then installs the Super
Hornet by itself. From then on it switches on and off, and goes with Disable All, like every
other mod here. Your downloads stay where they are, untouched.

When CJS put out a newer build, the app takes only the build on its list until the list
catches up.

Already installed it yourself? The app finds your copy. Right-click the row to let it manage it.

Flying one needs the F/A-18C module.

### The UH-60L

Kinkku's UH-60L Black Hawk is not in the pack either. Kinkku shares it through a Patreon post
(https://www.patreon.com/posts/uh60l-mod-2-0-138859868), and Kinkku's own installer downloads it
from a GitHub release. This app does the same. Tick **UH-60L Black Hawk** and press Apply, and it
downloads that same 1.4 GB file from Kinkku's release, checks it is the exact one on its list,
and switches it on like any other mod here. Nothing of it comes from us.

That gives you the UH-60L and the armed UH-60L DAP, version 2.1.5. It has its own flight model,
so it needs no module to fly. Its AI door gunners need a small script, bhHook.lua, in
`Saved Games\DCS\Scripts\Hooks`. The app puts it there with the aircraft and takes it out again
with it, Disable All included, and never writes over one it did not put there.

Already installed it with Kinkku's installer? The app finds your copy. Right-click the row to let
it manage it.

If you fly it and enjoy it, Kinkku's Patreon post is the place to say so.

### The GBU-39 SDB

**If you run Modern F-15E, leave this one unticked.** Modern F-15E already loads the SDBs, and
with this installed as well they load twice and show up on the racks as giant bombs.

Pixelstorm no longer needs it, so only tick it for a server that asks for it. It is Haack's GBU-39 Small Diameter Bomb and its BRU-61 rack, which Haack hands out on the Modern
F-15E 2.4.4 release (https://github.com/65thhaack/Modern-F15E-Mod/releases/tag/v2.4.4) for
servers and for players without Modern F-15E. Tick **GBU-39 SDB (Haack)** and press Apply, and
the app downloads that 6 MB file from Haack's release, checks it is the exact one on its list,
and puts it in `Saved Games\DCS\Mods\tech`. Nothing of it comes from us. It lets you join and see
the bombs; dropping them needs Modern F-15E.

Haack keeps only his newest release online, so for a short while after a new one comes out the
download can fail, until the list here catches up.

Installed it already and then picked up Modern F-15E? Untick it here and press Apply.

---

## What it does to your DCS

Most mods are aircraft, and they go in `Saved Games\DCS\Mods` as folders of their own.
Switching one off moves its folder to a parked area inside your DCS write directory, where
DCS does not look. That is why switching back on is instant.

The UH-60L adds one file outside its folder: bhHook.lua in `Saved Games\DCS\Scripts\Hooks`, for
its door gunners. It moves in and out with the aircraft the same way.

When the pack carries a newer build of a mod you already have, its row turns amber, and Apply
swaps the old build for the new one. A mod that did not change is never downloaded again.

Some mods change files inside your DCS installation, the program folder itself, and the F-16I
Sufa is one of them. Pixelstorm runs
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
