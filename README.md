# lunchbox — archived pull requests

This repository preserves the **106 pull requests** from the Forgejo repository `albert/shepherd-launcher`, which was migrated to [`aarmea/lunchbox`](https://github.com/aarmea/lunchbox).

## How the numbering works

Forgejo, like GitHub, drew issues and pull requests from a single sequence. Numbers **1–201** contained 95 issues and 106 pull requests.

The issues were migrated to [`aarmea/lunchbox`](https://github.com/aarmea/lunchbox/issues) **keeping their original numbers**. To make that possible, every number that belonged to a pull request is held there by a closed placeholder issue labelled [`legacy-pull-request`](https://github.com/aarmea/lunchbox/issues?q=label%3Alegacy-pull-request), which links to the matching file here. So `#N` means the same thing it always did, whichever side you start from.

To list only the real issues:

```
is:issue -label:legacy-pull-request
```

## What each file holds

The pull request's description, its metadata (source branch, head and merge commit, dates, author), the outcome of its CI checks, and any review discussion. The diffs themselves are not duplicated here — they are in the git history of `aarmea/lunchbox`, reachable from the merge commit recorded in each file.

## Pull requests

104 merged, 1 closed without merging (#22), 1 still open (#75).

| # | Title | Branch | State | Merged | CI |
|---:|---|---|---|---|---|
| [200](prs/0200.md) | [Remote file manager (#195)](prs/0200.md) | `feat/195-remote-file-manager` | Merged | 2026-09-19 | pass |
| [199](prs/0199.md) | [fix(sway): bind the idle blank's resume to its own timeout (#197)](prs/0199.md) | `fix/197-screen-never-wakes` | Merged | 2026-09-11 | pass |
| [198](prs/0198.md) | [Config editor: activities cannot be edited, added, or typed into comfortably (#192)](prs/0198.md) | `fix/192-ebook-kind-editor` | Merged | 2026-09-11 | pass |
| [196](prs/0196.md) | [Token gate minimum](prs/0196.md) | `fix/193-token-gate-minimum` | Merged | 2026-09-11 | pass |
| [191](prs/0191.md) | [Let more than one phone administer a device](prs/0191.md) | `feat/149-multiple-companion-bonds` | Merged | 2026-09-13 | pass |
| [190](prs/0190.md) | [Administrator mode: set the device up in place](prs/0190.md) | `feat/154-admin-mode` | Merged | 2026-09-11 | pass |
| [189](prs/0189.md) | [Enable the config editor in Web management](prs/0189.md) | `feat/185-config-editor-in-web-management` | Merged | 2026-09-08 | pass |
| [187](prs/0187.md) | [Network status page in the management UIs (#182)](prs/0187.md) | `feat/182-network-status` | Merged | 2026-09-07 | pass |
| [184](prs/0184.md) | [Improve BLE reliability around disconnect events](prs/0184.md) | `fix/ble-false-disconnect-drops-response` | Merged | 2026-09-07 | pass |
| [183](prs/0183.md) | [Add auth to Web management](prs/0183.md) | `feat/156-web-management-auth` | Merged | 2026-09-07 | pass |
| [181](prs/0181.md) | [Open the volume and brightness sliders out of their icons](prs/0181.md) | `fix/hud-slider-popouts` | Merged | 2026-09-07 | pass |
| [180](prs/0180.md) | [feat(stated): end a session nothing is supervising any more (#172)](prs/0180.md) | `feat/172-session-watchdog` | Merged | 2026-09-07 | pass |
| [179](prs/0179.md) | [Stop declaring `conffiles` for files the admin does not own](prs/0179.md) | `fix/conffiles-vendor-files` | Merged | 2026-09-07 | pass |
| [176](prs/0176.md) | [Bill a session to the day it started](prs/0176.md) | `fix/170-bill-usage-to-the-start-day` | Merged | 2026-09-05 | pass |
| [175](prs/0175.md) | [Generate the config editor's defaults instead of mirroring them](prs/0175.md) | `refactor/codegen-config-defaults` | Merged | 2026-09-05 | pass |
| [174](prs/0174.md) | [HUD on the side (#171)](prs/0174.md) | `feat/171-hud-on-the-side` | Merged | 2026-09-05 | pass |
| [173](prs/0173.md) | [Pause the activity clock on system sleep](prs/0173.md) | `feat/155-pause-clock-on-sleep` | Merged | 2026-09-05 | pass |
| [169](prs/0169.md) | [feat(media): a button that re-fetches libraries, downloads and segments (#165)](prs/0169.md) | `feat/165-media-refresh` | Merged | 2026-09-05 | pass |
| [168](prs/0168.md) | [docs(ble): unpin the kernel, and fix the pairing flow Android changed](prs/0168.md) | `docs/ble-advertising-fixed-7.0.0-31` | Merged | 2026-09-05 | fail |
| [167](prs/0167.md) | [Build aarch64 packages in CI](prs/0167.md) | `feat/166-arm64-cross` | Merged | 2026-09-13 | pass |
| [164](prs/0164.md) | ["ebook" content type](prs/0164.md) | `feat/ebook-content-type` | Merged | 2026-09-05 | pass |
| [163](prs/0163.md) | [Skip SponsorBlock segments in YouTube videos](prs/0163.md) | `feat/159-sponsorblock` | Merged | 2026-09-05 | pass |
| [161](prs/0161.md) | [Keep policy and state at a uid activities do not have](prs/0161.md) | `feat/state-custodian` | Merged | 2026-09-07 | pass |
| [158](prs/0158.md) | [Close shepherdd's own IPC socket to everything but the session](prs/0158.md) | `feat/ipc-peer-cgroup` | Merged | 2026-09-03 | pass |
| [153](prs/0153.md) | [Bump CI container to 26.04](prs/0153.md) | `feat/config-editor` | Merged | 2026-08-28 | pass |
| [152](prs/0152.md) | [Fix: firewall rules not enforcing for Flatpak/Snap (#151)](prs/0152.md) | `fix/151-firewall-bpf-alignment` | Merged | 2026-08-27 | pass |
| [148](prs/0148.md) | [Talk to sway over its IPC socket, and take it away from everything else](prs/0148.md) | `feat/sway-ipc` | Merged | 2026-08-30 | pass |
| [146](prs/0146.md) | [Set volume limits per audio output, and choose the active one](prs/0146.md) | `feat/per-audio-sink-volume` | Merged | 2026-08-23 | pass |
| [145](prs/0145.md) | [Report administrator-facing conditions in the management UIs](prs/0145.md) | `feat/warning-channel` | Merged | 2026-08-23 | pass |
| [142](prs/0142.md) | [Make media a real activity kind and prefetch libraries in the background](prs/0142.md) | `feat/media-kind` | Merged | 2026-08-23 | pass |
| [141](prs/0141.md) | [Add window management to the companion app](prs/0141.md) | `feat/companion-window-management` | Merged | 2026-08-22 | pass |
| [139](prs/0139.md) | [Graphical config editor](prs/0139.md) | `feat/config-editor` | Merged | 2026-08-27 | pass |
| [137](prs/0137.md) | [Fix supervision escapes on open and close](prs/0137.md) | `fix/activity-supervision-escapes` | Merged | 2026-08-22 | pass |
| [134](prs/0134.md) | [Fix touch/mouse bridge offset](prs/0134.md) | `fix/touch-bridge-grabs-clickpad` | Merged | 2026-08-19 | pass |
| [133](prs/0133.md) | [fix(install): never delete files an installed package owns](prs/0133.md) | `fix/uninstall-preserves-packaged-files` | Merged | 2026-08-19 | pass |
| [132](prs/0132.md) | [BLE management reliability improvements](prs/0132.md) | `fix/ble-rearm-on-resume` | Merged | 2026-08-19 | pass |
| [131](prs/0131.md) | [feat(admin): install the companion and media apps from the admin script](prs/0131.md) | `feat/admin-installs-android-apps` | Merged | 2026-08-17 | pass |
| [130](prs/0130.md) | [Fix BLE management after a sleep/wake cycle on the host](prs/0130.md) | `fix/companion-retry-after-give-up` | Merged | 2026-08-17 | pass |
| [129](prs/0129.md) | ["retroarch" activity kind](prs/0129.md) | `feat/retroarch-emulator-support` | Merged | 2026-08-24 | pass |
| [128](prs/0128.md) | [fix(hud): rebuild the close-confirmation prompt when the HUD scale changes](prs/0128.md) | `fix/hud-confirm-prompt-stale-style` | Merged | 2026-08-15 | pass |
| [126](prs/0126.md) | [Properly fix BLE management pairing](prs/0126.md) | `fix/ble-connect-drain-unbounded` | Merged | 2026-08-15 | pass |
| [122](prs/0122.md) | [fix(ble): give link encryption its own budget on reconnect](prs/0122.md) | `fix/ble-connect-drain-unbounded` | Merged | 2026-08-02 | pass |
| [121](prs/0121.md) | [fix(ble): bound the connect-time outbox drain](prs/0121.md) | `fix/ble-connect-drain-unbounded` | Merged | 2026-08-02 | pass |
| [120](prs/0120.md) | [feat(media): remember playback positions behind an opt-in resume option](prs/0120.md) | `feat/media-resume-playback-positions` | Merged | 2026-08-02 | pass |
| [118](prs/0118.md) | [fix(hud): scale the close-confirmation buttons under the XWayland DPI hack](prs/0118.md) | `fix/hud-confirm-buttons-xwayland-dpi-hack` | Merged | 2026-07-30 | pass |
| [117](prs/0117.md) | [fix(hud): size warning text and sliders under the XWayland DPI hack](prs/0117.md) | `fix/hud-sizing-xwayland-dpi-hack` | Merged | 2026-07-29 | pass |
| [116](prs/0116.md) | [Implement hardware video decoding on both the Linux and Android shepherd-media](prs/0116.md) | `fix/media-hardware-decoding` | Merged | 2026-07-29 | pass |
| [113](prs/0113.md) | [feat(limits): skip the cooldown after a session that barely ran](prs/0113.md) | `feat/cooldown-grace-for-short-sessions` | Merged | 2026-07-28 | pass |
| [112](prs/0112.md) | [F-Droid compliance](prs/0112.md) | `fdroid/fingerprint-and-antifeature` | Merged | 2026-07-27 | pass |
| [111](prs/0111.md) | [Publish Android packages to an internal F-Droid repository](prs/0111.md) | `docs/fdroid-repository-scope` | Merged | 2026-07-27 | pass |
| [108](prs/0108.md) | [BLE management advertisement can become too long](prs/0108.md) | `fix/ble-advertisement-name-overflow` | Merged | 2026-07-26 | pass |
| [107](prs/0107.md) | [Token system and grouped time limits (#8, #5)](prs/0107.md) | `u/albert/token-system` | Merged | 2026-07-26 | pass |
| [104](prs/0104.md) | [fix(release): send the apt upload as octet-stream, not form-urlencoded](prs/0104.md) | `u/albert/apt-content-type` | Merged | 2026-07-19 | pass |
| [103](prs/0103.md) | [fix(release): build the .deb with xz so the apt registry accepts it](prs/0103.md) | `u/albert/apt-deb-xz` | Merged | 2026-07-19 | pass |
| [102](prs/0102.md) | [feat(release): publish the .deb to Forgejo's apt registry](prs/0102.md) | `u/albert/forgejo-apt-repo` | Merged | 2026-07-19 | fail |
| [101](prs/0101.md) | [fix(hud): keep the "End session" confirm popover on-screen (#97)](prs/0101.md) | `u/albert/97/hud-popover-clipped` | Merged | 2026-07-19 | fail |
| [100](prs/0100.md) | [ci: warm shared cargo registry + split target/ cache per job](prs/0100.md) | `u/albert/ci-cargo-cache-warmup` | Merged | 2026-07-19 | pass |
| [99](prs/0099.md) | [feat(input): gate activities on connected input devices (#96)](prs/0099.md) | `u/albert/96/input-dependencies` | Merged | 2026-07-19 | pass |
| [98](prs/0098.md) | [BLE admin session: fix reconnect failures on both the daemon and the companion](prs/0098.md) | `u/albert/ble-reconnect-fixes` | Merged | 2026-07-19 | pass |
| [95](prs/0095.md) | [feat(scripts): add 'shepherd uninstall' to remove installed files](prs/0095.md) | `u/albert/shepherd-uninstall-command` | Merged | 2026-07-18 | pass |
| [94](prs/0094.md) | [feat(dev): headless, agent-drivable dev session for end-to-end UI work](prs/0094.md) | `u/albert/headless-dev-scaffold` | Merged | 2026-07-16 | pass |
| [93](prs/0093.md) | [fix(input): stop dividing touch/tablet bridge coords by output scale (#47)](prs/0093.md) | `u/albert/47/touch-compat-scale-offset` | Merged | 2026-07-12 | pass |
| [92](prs/0092.md) | [Releases cleanup](prs/0092.md) | `u/albert/82/binary-releases` | Merged | 2026-07-12 | pass |
| [91](prs/0091.md) | [fix(companion-ble): stop the reconnect poll loop busy-spinning on read failure](prs/0091.md) | `u/albert/ble-reconnect-poll-spin` | Merged | 2026-07-09 | pass |
| [90](prs/0090.md) | [Add CI-built binary releases (.deb + .apk) (#82)](prs/0090.md) | `u/albert/82/binary-releases` | Merged | 2026-07-11 | pass |
| [89](prs/0089.md) | [External monitor/docking support (#87)](prs/0089.md) | `u/albert/87/external-monitor-docking` | Merged | 2026-07-04 | pass |
| [88](prs/0088.md) | [Automatic screen brightness (#81)](prs/0088.md) | `u/albert/81/auto-brightness` | Merged | 2026-07-04 | pass |
| [86](prs/0086.md) | [Harmonize versions from a single VERSION file (#83)](prs/0086.md) | `u/albert/83/harmonize-versions` | Merged | 2026-07-04 | pass |
| [85](prs/0085.md) | [gamepad-bridge: remap productivity face buttons (#84)](prs/0085.md) | `u/albert/84/productivity-face-buttons` | Merged | 2026-07-04 | pass |
| [79](prs/0079.md) | [Confirm before the HUD "X" ends an activity (#78)](prs/0079.md) | `u/albert/78/confirm-close-dialog` | Merged | 2026-07-02 | pass |
| [77](prs/0077.md) | [Add per-activity-type readiness gate; implement for Steam (#76)](prs/0077.md) | `u/albert/76/steam-readiness` | Merged | 2026-07-02 | pass |
| [75](prs/0075.md) | [Add support for Android activities](prs/0075.md) | `u/albert/2/android-activity` | Open | — | fail |
| [74](prs/0074.md) | [Show a suspend cover before sleep (#73)](prs/0074.md) | `u/albert/73/loading-screen-on-suspend` | Merged | 2026-06-28 | pass |
| [72](prs/0072.md) | [Android implementation of shepherd-media](prs/0072.md) | `u/albert/70/shepherd-media-android` | Merged | 2026-07-09 | pass |
| [71](prs/0071.md) | [Bluetooth-based management interface](prs/0071.md) | `u/albert/65/ble-management` | Merged | 2026-07-04 | pass |
| [69](prs/0069.md) | [Add disable_touch input_compat mode (#68)](prs/0069.md) | `u/albert/68/disable-touch-per-activity` | Merged | 2026-06-28 | pass |
| [67](prs/0067.md) | [Let force-enable overrides bypass the daily quota](prs/0067.md) | `u/albert/feat/overrides-bypass-daily-quota` | Merged | 2026-06-25 | pass |
| [66](prs/0066.md) | [Use stale poster cache as an offline fallback (#64)](prs/0066.md) | `u/albert/64/youtube-image-cache` | Merged | 2026-06-21 | pass |
| [63](prs/0063.md) | [Managed Web browser activity](prs/0063.md) | `u/albert/10/web-browser` | Merged | 2026-06-29 | pass |
| [62](prs/0062.md) | [Implement a tablet-to-touch bridge](prs/0062.md) | `u/albert/feat/tablet-to-touch-bridge` | Merged | 2026-06-14 | pass |
| [61](prs/0061.md) | [Auto-accept Steam Cloud sync failure when offline](prs/0061.md) | `u/albert/50/steam-offline-autodismiss` | Merged | 2026-06-13 | pass |
| [60](prs/0060.md) | [Make network changes trigger a network check](prs/0060.md) | `u/albert/fix/recheck-network-on-change` | Merged | 2026-05-31 | pass |
| [59](prs/0059.md) | [Make input sidecars compositor-agnostic via /dev/uinput](prs/0059.md) | `u/albert/58/wayland-generic-sidecars` | Merged | 2026-05-31 | pass |
| [57](prs/0057.md) | [Implement brightness policy and control slider](prs/0057.md) | `u/albert/55/brightness-controls` | Merged | 2026-05-22 | pass |
| [56](prs/0056.md) | [Implement physical volume buttons](prs/0056.md) | `u/albert/52/volume-buttons` | Merged | 2026-05-22 | pass |
| [54](prs/0054.md) | [Allow use of stale YouTube playlist libraries while offline](prs/0054.md) | `u/albert/51/youtube-offline-playlist` | Merged | 2026-05-21 | pass |
| [53](prs/0053.md) | [Add a network connectivity indicator to the HUD](prs/0053.md) | `u/albert/49/network-icon` | Merged | 2026-05-21 | pass |
| [46](prs/0046.md) | [Toggle compositor scale for XWayland activities](prs/0046.md) | `u/albert/45/xwayland-dpi` | Merged | 2026-05-18 | pass |
| [44](prs/0044.md) | [Hide Steam main window](prs/0044.md) | `u/albert/fix/debug-sway` | Merged | 2026-05-12 | pass |
| [43](prs/0043.md) | [Add sidecar for gamepad to keyboard/mouse remapper](prs/0043.md) | `u/albert/42/gamepad-to-keyboard-mouse` | Merged | 2026-05-11 | pass |
| [41](prs/0041.md) | [Fix sidecar lifetime](prs/0041.md) | `u/albert/37/touch-to-mouse` | Merged | 2026-05-10 | pass |
| [40](prs/0040.md) | [Implement unified logout path](prs/0040.md) | `u/albert/fix/logout-fixes` | Merged | 2026-05-10 | pass |
| [39](prs/0039.md) | [Implement touch/mouse remapping](prs/0039.md) | `u/albert/37/touch-to-mouse` | Merged | 2026-05-10 | pass |
| [36](prs/0036.md) | [Implement icon autodetection](prs/0036.md) | `u/albert/14/icon-autodetection` | Merged | 2026-05-09 | pass |
| [35](prs/0035.md) | [Implement logout button](prs/0035.md) | `u/albert/33/logout-button` | Merged | 2026-05-09 | pass |
| [34](prs/0034.md) | [Media launcher and libraries](prs/0034.md) | `u/albert/9/media-launcher` | Merged | 2026-05-17 | pass |
| [32](prs/0032.md) | [Implement firewall rules](prs/0032.md) | `u/albert/4/firewall` | Merged | 2026-05-21 | pass |
| [31](prs/0031.md) | [Add end to end tests in CI, including Sway and launcher run](prs/0031.md) | `u/albert/feat/e2e-tests` | Merged | 2026-05-02 | pass |
| [30](prs/0030.md) | [Add /etc/sway/shepherd.conf.d/*.conf support](prs/0030.md) | `u/albert/7/sway-conf-d` | Merged | 2026-05-02 | pass |
| [29](prs/0029.md) | [Fix management screenshot in README](prs/0029.md) | `u/aarmea/fix/readme-management-image` | Merged | 2026-05-01 | pass |
| [26](prs/0026.md) | [Implement management API](prs/0026.md) | `u/albert/24/api` | Merged | 2026-05-01 | pass |
| [25](prs/0025.md) | [Keep the screen on while an activity is active](prs/0025.md) | `u/albert/19/keepalive-when-active` | Merged | 2026-04-25 | pass |
| [23](prs/0023.md) | [Implement configuration file watcher](prs/0023.md) | `u/albert/15/conf-watcher` | Merged | 2026-04-24 | pass |
| [22](prs/0022.md) | [Include controller input for idle detection](prs/0022.md) | `u/albert/19/controller-idle-hint` | Closed without merging | — | pass |
| [21](prs/0021.md) | [u/aarmea/13/preload-steam](prs/0021.md) | `u/aarmea/13/preload-steam` | Merged | 2026-04-20 | pass |
| [20](prs/0020.md) | [Fix battery icon and presence](prs/0020.md) | `u/aarmea/17/battery-icons` | Merged | 2026-04-20 | pass |

---

_Archived from https://git.armeafamily.com/albert/shepherd-launcher — 106 pull requests, 90 comments._
