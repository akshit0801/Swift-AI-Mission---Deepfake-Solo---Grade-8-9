## **Overview**

Students play as junior analysts whose job is to build a forensic eye before any machine is trained. The core insight: proving something is fake requires specific, observable evidence — not gut feeling. That standard is identical to what a classifier requires: specific pixel-level patterns, not impressions. By the end, students produce an evidence brief that becomes their entry artefact for the group mission.

## **Phase-by-Phase Breakdown**

### **Phase 1 — Can You Even Tell? (0–5 min)**

| 🖥  GAME SCREEN *Six image pairs appear side by side on screen — one real face, one AI-generated face per pair. No labels, no hints. Students click the face they think is fake for each pair. A progress bar counts down. On completion, the screen reveals their score with a breakdown of which they got right and wrong. The reveal message reframes the result: "Your gut isn't broken — it just isn't systematic. That's what this session fixes."* |
| :---- |

What this phase establishes:

* Most students get 3–4 wrong — creating a felt need for the skill

* Anchors the emotional journey: from overconfidence to curiosity

* No instruction is given before this — the failure comes first

### **Phase 2 — The Tell Library (5–15 min)**

| 🖥  GAME SCREEN *Six tells are presented one at a time. Each tell has a name, a one-sentence explanation, and a frozen video frame with a pulsing circle over the relevant region. Students must click the pulsing region to reveal an annotation before they can unlock the next tell. The six tells appear as a visual "library shelf" that fills up as each is unlocked.* |
| :---- |

The six tells students learn:

* **Teeth Drift:** AI models struggle with consistent individual teeth across frames. In long sentences, tooth shape changes mid-word. Look at open-mouth frames during vowel sounds.

* **The Blink Problem:** Deepfakes either under-blink or over-correct. Asymmetric eyelid closure is the clearest signal. Check at 0.25x speed at 5-second intervals.

* **Ear and Hair Edges:** GAN artifacts concentrate at the boundary between hair, ears, and background. Blurring, flickering, and asymmetry appear at the silhouette during head turns.

* **Background Warp:** When the subject moves, nearby background objects subtly distort. The subject stays sharp; the world around them warps like a reflection in water.

* **The P–B–M Test:** Lip sync breaks most visibly on bilabial consonants. AI frequently mis-times the lip closure. Count the gap between the sound and the closure — over 120ms is a flag.

* **Shadow Mismatch:** Deepfakes paste a face onto a different lighting environment. The nose shadow and the neck shadow point in opposite directions.

### **Phase 3 — Feeling vs. Proving (15–20 min)**

| 🖥  GAME SCREEN *Two fictional detective reports about the same deepfake video appear side by side. Both conclude the video is fake. Students tap each report to read it in full, then click the one that would hold up in front of a school board. After selecting, a one-screen explanation appears with the evidence standard: specific, repeatable, and observable without subjective judgment. A before/after example shows how to rewrite a gut statement into an evidence statement.* |
| :---- |

***Report A (gut language):** "This video is clearly AI-generated. The principal's voice sounds slightly off. His face looks strange around the eyes. It doesn't feel right."*

***Report B (evidence language):** "Three anomalies were observed: (1) At 0:14, the left ear disappears entirely during a rightward head rotation — consistent with GAN edge artifacts. (2) The bilabial closure on 'parents' (0:09) occurs 180ms after the P-sound, outside the normal 80ms window. (3) The nose shadow points left while the window behind him indicates light from the right."*

### **Phase 4 — Build Your Detection Protocol (20–27 min)**

| 🖥  GAME SCREEN *A grid of 10 detection criteria appears — the 6 tells from Phase 2 plus 4 new ones (metadata inconsistency, EXIF data absence, compression artifacts, frame rate irregularities). Students drag their 6 highest-priority criteria into a ranked list, then type one sentence justifying each of their top-3 choices. The interface prevents submission with fewer than 3 justifications or without the words "because" in each.* |
| :---- |

The four additional criteria introduced:

* Metadata inconsistency — creation date, device model, or GPS coordinates that contradict the claimed context

* Absent EXIF data — legitimate videos carry camera metadata; scrubbed EXIF is a flag

* Compression artifact patterns — deepfake encoding introduces characteristic noise patterns invisible to the eye but detectable with tools

* Frame rate irregularities — synthetic videos sometimes have micro-stutters at scene boundaries where the generation model reset

### **Phase 5 — One Verdict (27–30 min)**

| 🖥  GAME SCREEN *A 150-word written description of the principal's deepfake video appears, alongside three frozen-frame descriptions. Students write a 3-point evidence brief in a fixed-format text area. The format is enforced: each point must begin with a timestamp or spatial location. The submit button is locked until all three points are filled and each contains a timestamp reference.* |
| :---- |

| Artefact that carries into the group mission *The completed 3-point evidence brief. Students bring this printed or on-screen into the group game as their individual expert verdict. The group's first task is to compare three briefs before any technology is used.* |
| :---- |

