# Real-chat jailbreak probe inspection

**Updated probe, compact gallery:** [WildChat + Anomaly top hits](https://goodfire-ai.github.io/jailbreak-inspection/top-hits/?revision=460a364c5df9).
The current standalone page contains 50 fresh WildChat requests and 50 rescored
Anomaly requests, with original replies, English translations, judge labels,
source filters, individual-hit links and offline HTML download. Graphic sexual
content and credential-shaped strings are excluded from both sides of each
exported pair.

The WildChat follow-up judged 2,131 mining requests with Luna and Sol at high
reasoning under the main constitution. The refit added 903 training negatives
(including 128 SQL cases) and 68 attempts. It then ranked 29,741 supported
requests from 20,000 separate parents, first three eligible user turns per parent.
The [round report](https://goodfire-ai.github.io/jailbreak-inspection/top-hits/round-report.html?revision=460a364c5df9)
compares both probes on the same WildChat/Anomaly FPR reference sets and shows
the earlier SQL score changes, explicitly separating four trained examples from
two held-out validation examples. `top-hits/manifest.json` records provenance.
The new checkpoint SHA-256 starts `da9dee0423bc`.

The older inspection collection below remains available as a historical viewer.

Detector-selected inspection candidates, with original model replies and context.
The new mixed-mining Qwen3.8-27B probe ranked 48,009 eligible cached WildChat requests.
The viewer contains 353 requests in 329 groups and 649 original rollouts, including 160 WildChat requests.

Each card shows a short approach-summary title above the opening attack text, Astra’s verdict and the existing calibrated mined-probe probability. Click the preview for generated summaries, rationales and full original chats. Initial-probe results are omitted from the viewer and JSONL. Fresh request-only `gpt-6-astra` reviews cover 351 requests; two provider-filtered requests have clearly attributed editorial summaries and unavailable judgments. Four restricted-content entries were removed from the selected export after review.

Open `inspection.html` through GitHub Pages. Use **Copy link to this view** to share filters, or download filtered JSONL and standalone HTML.

Scores and balanced WildJailbreak reference probabilities do not establish real-chat attack probability or response success. Astra judgments concern the scored request under a frozen research refusal referent; they are provisional and do not judge original-response success. The calibration/test WildChat pools are excluded from mining.

Source datasets: [WildChat-4.8M](https://huggingface.co/datasets/allenai/WildChat-4.8M), [Search Arena](https://huggingface.co/datasets/lmarena-ai/search-arena-24k), [Arena Expert](https://huggingface.co/datasets/lmarena-ai/arena-expert-5k), and [Arena Human Preference 140k](https://huggingface.co/datasets/lmarena-ai/arena-human-preference-140k). Source names, revisions, model IDs and original conversation context remain in the export.

The static bundle's `manifest.json` records producer commits, checkpoint identity and file hashes. Activation caches and model weights are not included.
