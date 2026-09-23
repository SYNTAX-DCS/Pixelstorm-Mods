# Pixelstorm Mods

One small app that installs the aircraft mods the **Pixelstorm** DCS server flies, and
switches them on and off again without you ever touching your DCS install by hand.

Built by **Pixel Pilot Club**. Unofficial, and not affiliated with Eagle Dynamics.

---

## Why it exists

The point is not really the installing. It is the off switch.

You want to see the other aircraft on the server on a Sunday night. You do not want 9.7 GB
of them sitting in your DCS folder all week, you do not want to learn OVGME, and you should
not have to work out which mod goes where. Tick what you want, press Apply, fly. Untick it
afterwards and it is gone from DCS but still on your disk, so turning it back on next week
is instant and costs no download.

---

## Install

1. Download **PixelstormMods.exe** from [Releases](../../releases/latest).
2. **Close DCS.**
3. Run it. It finds your DCS folder on its own.
4. Tick the mods you want and press **Apply**.
5. Start DCS.

To take a mod out again, untick it and press Apply. To get rid of it completely, right-click
the row and choose to delete it.

---

## What is in the pack

| aircraft | made by |
| --- | --- |
| Su-30 FlankerEx (CWS) | Codename Flanker |
| Su-35S (EFM) | Codename Flanker |
| F-22A Raptor (MK II EFM) | GrinnelliDesigns, EFM by BHOOP Studios |
| Su-34 Red Flag Fighters | awentyy, alexey1111 |
| A400M Atlas (tanker) | FR3D-Studio |

2,287 files, 9.74 GB once installed, 6.98 GB to download. You do not have to take all of
them; tick only the ones you want.

**These aircraft are their authors' work, not ours.** They are packed here exactly as their
authors shipped them, unmodified. This app installs them and gets out of the way. If you fly
one and enjoy it, go and tell the person who made it. **Any author who would rather their
mod was not distributed here only has to say so and it comes out of the pack.**

Su-34 Red Flag Fighters needs Su-30 FlankerEx alongside it for its textures and its flight
model. Tick the Su-34 and the Su-30 comes with it automatically, in the right order.

---

## What it does to your DCS

It only ever adds folders under `Saved Games\DCS\Mods`. It does not edit a single file that
Eagle Dynamics or a mod author shipped, and it never writes into your DCS program folder at
all.

Turning a mod off moves it into a parked folder inside your DCS write directory rather than
deleting it. That is why switching back on is instant. Removing the app entirely and
deleting that parked folder leaves your DCS exactly as it was.

If you already installed one of these mods yourself, the app finds it, says so, and offers
to take charge of it. It will not write over it, and it will not delete it.

### Will this stop me joining other servers?

No. Adding aircraft that DCS does not ship does not taint your client. What a server checks
with "pure models" or "pure scripts" is whether you have **modified** something DCS already
ships, and none of these mods do.

If you want to be sure, right-click any mod and choose **Will pure servers let me in?**. It
reads your own DCS log, tells you what your last flight actually flagged, and says whether
any of it came from this pack or from something else you have installed.

---

## Files and space

Downloads are split into parts and checked against a SHA-256 before anything is unpacked, so
an interrupted or corrupted download cannot leave you with a half-installed aircraft. If your
connection drops, run it again and it picks up where it stopped.

**Do not download the mod archives by hand from the Releases page.** They are split files and
the parts mean nothing on their own. Let the app fetch them.

---

## Problems

The app writes a log. Right-click a mod and use the menu to check your files, or open an
issue here and say what the app told you.
