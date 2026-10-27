# Confessional

A Mac menu-bar app that records your calls, transcribes them on your Mac, tells the speakers
apart, takes screenshots of what was shared, and writes a summary. No bot joins the call, and
nothing leaves your Mac unless you choose a cloud AI for summaries.

**[Download Confessional](https://github.com/mgrody1/confessional-releases/releases/latest/download/Confessional.dmg)**

Needs a Mac with Apple Silicon (M1 or later) and macOS 14 Sonoma or later.

## Installing

1. Open the downloaded `Confessional.dmg` and drag **Confessional** into **Applications**.
2. Open Confessional from Applications. macOS will say it can't check it for malicious
   software (it isn't notarized by Apple yet). Click **Done**, then open
   **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to
   Confessional. Confirm, and enter your password. You only do this once.

   (Or, before opening the DMG: in Terminal, run
   `xattr -d com.apple.quarantine ~/Downloads/Confessional.dmg` and it opens normally.)
3. Setup takes a few minutes: how Confessional works, the permissions it needs (microphone,
   screen and system audio recording, notifications, and optionally your calendar), how you'd
   like summaries written (your Claude Pro or Max plan, a model on your Mac, or later), and a
   test recording.
4. Setup downloads the speech model (about 600 MB) and the speaker model (about 190 MB)
   once, so do it on good Wi-Fi rather than right before an important call.

## Getting started

Inside the app, the menu bar icon → More → **Getting Started guide** covers recording, names,
projects, AI for summaries and what to do if something goes wrong.

- **Use your Claude plan for summaries:** Settings → AI Models → Claude shows the three steps
  (install Claude Code, sign in, Check again). No API key needed.
- **On a Mac with 8 GB of memory:** Confessional transcribes after the call, not during it.
  Keep live captions off, quit apps you aren't using during calls, and prefer Claude for
  summaries over a model on the Mac.
- **Something wrong?** Menu bar icon → More → Send Feedback emails the app's log (never audio
  or transcripts). If Confessional quits unexpectedly, it offers to send the crash report the
  next time it opens.

## Updates

Confessional checks for updates once a day and offers to install them with one click
(menu bar icon → ⬇, or Settings → Updates). It never restarts in the middle of a recording
or while a meeting is being transcribed.

## Please note

Recording laws vary: in many places everyone on a call has to agree to be recorded. Let
people know you're recording.
