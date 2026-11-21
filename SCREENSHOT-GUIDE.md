# Screenshot identification guide

Source file: `Cyber Home Lab Doc 1.docx` (embedded Action1 screenshots `image131.png` through `image151.png`).

The README displays every screenshot in the related walkthrough step. All screenshots are derived from the original embedded images; only the Action1 organization ID in screenshot 15 was redacted for public sharing.

| Figure / original image | Filename | What it shows | Evidence classification |
| --- | --- | --- | --- |
| 1 / `image131.png` | `01-action1-platform-overview.png` | Action1 free-edition webpage; product context, not evidence of deployment | Background / product orientation |
| 2 / `image132.png` | `02-initial-windows-endpoint-inventory.png` | Windows 11 L3X connected; vulnerability and missing-update counts | Endpoint inventory snapshot |
| 3 / `image133.png` | `03-four-critical-updates-selected.png` | Chrome and Microsoft runtime versions selected with Critical severity filter | UI / configuration |
| 4 / `image134.png` | `04-update-deployment-configuration.png` | Four selected updates, reboot and Windows-update-control settings | UI / configuration |
| 5 / `image135.png` | `05-automation-scheduling.png` | Action1 update deployment schedule wizard | UI / configuration |
| 6 / `image136.png` | `06-update-automation-running.png` | Automation started and waiting for endpoint to run task | Automation Running (not completed) |
| 7 / `image137.png` | `07-update-automation-success.png` | Update automation status Success on Nov 16, 2026 | Completed automation (Success) |
| 8 / `image138.png` | `08-follow-up-inventory-and-critical-filter.png` | Later snapshot and Critical missing-updates filter showing no entries | Endpoint inventory snapshot |
| 9 / `image139.png` | `09-noncritical-updates-remaining.png` | List of 15 visible missing updates | UI / configuration |
| 10 / `image140.png` | `10-secondary-update-batch-selection.png` | Broad set of additional software, runtime and driver updates selected | UI / configuration |
| 11 / `image141.png` | `11-subsequent-endpoint-posture.png` | Snapshot reporting 107 non-critical vulnerabilities and 10 non-critical updates | Endpoint inventory snapshot |
| 12 / `image142.png` | `12-remediation-actions-and-compensating-controls.png` | Available remediation action choices for findings without direct updates | UI / configuration |
| 13 / `image143.png` | `13-later-reduced-findings-snapshot.png` | Snapshot reporting one non-critical vulnerability and one non-critical update | Endpoint inventory snapshot |
| 14 / `image144.png` | `14-kali-action1-agent-deb-install.png` | Kali shell showing copying DEB and invoking apt install | UI / configuration |
| 15 / `image145.png` | `15-action1-linux-agent-enrollment.png` | Action1 Linux DEB enrollment wizard; installation token masked | Agent setup / enrollment evidence (org ID redacted) |
| 16 / `image146.png` | `16-windows-and-kali-endpoints-connected.png` | Windows and Kali endpoints visible and connected | Endpoint inventory snapshot |
| 17 / `image147.png` | `17-action1-software-repository.png` | Action1 software repository with 1Password selected | UI / configuration |
| 18 / `image148.png` | `18-1password-software-deployment-selection.png` | 1Password 8.12.44 selected for deployment | UI / configuration |
| 19 / `image149.png` | `19-1password-target-endpoint-selection.png` | Connected L3X endpoint selected | UI / configuration |
| 20 / `image150.png` | `20-1password-deployment-running.png` | Deployment automation status Running; no completion shown | Automation Running (not completed) |
| 21 / `image151.png` | `21-1password-windows-recent-apps.png` | Windows Recent view shows 1Password; not definitive causal proof of automation completion | Endpoint app visibility (not proof of automation success) |

## Image usage notes

- Do **not** substitute another screenshot for an identically numbered filename; the file names in the ZIP already match the README links.
- There are 21 source screenshots. `image130.png` is a VirusTotal screenshot and belongs to the Wazuh project, not this Action1 repository.
- An Action1 **Running** automation is not the same as a successfully finished task.
- Several different Action1 endpoint snapshots appear at different times and with different filters. Do not treat their raw counts as a controlled trend.
- The Action1 enrollment token is intentionally shown masked and must never be entered into the public README.
