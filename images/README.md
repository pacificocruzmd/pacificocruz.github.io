# Adding photos to the site

Every photo slot on the site currently shows a plain placeholder box with a caption (aspect ratio, minimum resolution, what to shoot). The `<img>` tag for each is already written into the page and pointed at the exact filename below — it's commented out. To activate a photo:

1. Name your file exactly as shown below and drop it in the matching folder.
2. Open that page's HTML file, find the commented `<img src="images/...">` line just above the matching placeholder box, delete the `<!--` and `-->` around it, and delete (or comment out) the placeholder `<div class="ph ...">...</div>` block right next to it.

If that's fiddly, just send me the photos (with a note on which is which) and I'll do the swap and re-export the zip.

## Primary photos (used across the site — do these first)

| File to add | Goes in folder | Used on | Spec |
|---|---|---|---|
| `portrait.jpg` | `images/about/` | Home + About (same photo, reused) | 4:5, 1600×2000 min, natural light, neutral background |
| `at-work.jpg` | `images/about/` | About | 3:2, 2400px wide min, operative/microscope setting, no identifiable patient |
| `ghent-fellowship.jpg` | `images/about/` | About | 4:3, with Tonnard & Verpaele — an archive photo from the fellowship is fine |
| `tokyo-fellowship.jpg` | `images/about/` | About | 4:3, with Dr. Ogawa — an archive photo is fine |

## Procedure lead photos (one per procedure page)

| File to add | Goes in folder | Page | Spec |
|---|---|---|---|
| `macs-facelift-lead.jpg` | `images/procedures/` | MACS Facelift | 2.4:1, 2400px wide min, facial anatomy/operative detail, no identifiable patient |
| `facial-rejuvenation-lead.jpg` | `images/procedures/` | Facial Rejuvenation | 2.4:1, 2400px wide min, portrait study or consultation room |
| `rhinoplasty-lead.jpg` | `images/procedures/` | Rhinoplasty | 2.4:1, 2400px wide min, portrait study or consultation room |
| `body-contouring-lead.jpg` | `images/procedures/` | Body Contouring | 2.4:1, 2400px wide min, consultation room or operative setting |
| `regenerative-lead.jpg` | `images/procedures/` | Regenerative (hub) | 2.4:1, 2400px wide min, operative or laboratory setting |
| `nanofat-lead.jpg` | `images/procedures/` | Nanofat | 2.4:1, 2400px wide min, operative or clinical setting |
| `keloid-management-lead.jpg` | `images/procedures/` | Keloid Management | 2.4:1, 2400px wide min, consultation room or operative setting |
| `lymphedema-surgery-lead.jpg` | `images/procedures/` | Lymphedema Surgery | 2.4:1, 2400px wide min, microscope or operative field |
| `scar-and-burn-care-lead.jpg` | `images/procedures/` | Scar & Burn Care | 2.4:1, 2400px wide min, operative or clinical setting |
| `tissue-reconstruction-lead.jpg` | `images/procedures/` | Complex Tissue Reconstruction | 2.4:1, 2400px wide min, microscope or operative field |

All of the above have "no identifiable patient" in the spec where it applies — worth keeping in mind for consent/privacy given these will be public.

## Optional, for later (polish, not launch-blocking)

Most procedure pages also have 2–3 smaller placeholder slots that were never wired to a filename at all — a macro "detail" shot (instruments, suturing, harvest cannula, etc.) and a simple line-art illustration in the site's ink + jaguar-green style (facial anatomy, LVA schematic, tension vectors on a scar, and so on). The homepage also has three small square slots ("Instruments," "Hands at work," "Loupes / microscope"). These are nice-to-haves — the pages read fine without them. If you want these done too, say the word and I'll set up filenames for those the same way.
