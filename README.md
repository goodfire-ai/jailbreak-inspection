# Real-chat jailbreak probe inspection

Detector-selected inspection candidates, with original model replies and context.
The new mixed-mining Qwen3.8-27B probe ranked 48,009 eligible cached WildChat requests.
The viewer contains 353 requests in 329 groups and 649 original rollouts, including 160 WildChat requests.

Each card previews the opening attack text, Astra’s verdict and the existing calibrated mined-probe probability. Click the preview for generated summaries, rationales and full original chats. Initial-probe results are omitted from the viewer and JSONL. Fresh request-only `gpt-6-astra` reviews cover 351 requests; two provider-filtered requests have clearly attributed editorial summaries and unavailable judgments. Four restricted-content entries were removed from the selected export after review.

Open `inspection.html` through GitHub Pages. Use **Copy link to this view** to share filters, or download filtered JSONL and standalone HTML.

Scores and balanced WildJailbreak reference probabilities do not establish real-chat attack probability or response success. Astra judgments concern the scored request under a frozen research refusal referent; they are provisional and do not judge original-response success. The calibration/test WildChat pools are excluded from mining.

Source datasets: [WildChat-4.8M](https://huggingface.co/datasets/allenai/WildChat-4.8M), [Search Arena](https://huggingface.co/datasets/lmarena-ai/search-arena-24k), [Arena Expert](https://huggingface.co/datasets/lmarena-ai/arena-expert-5k), and [Arena Human Preference 140k](https://huggingface.co/datasets/lmarena-ai/arena-human-preference-140k). Source names, revisions, model IDs and original conversation context remain in the export.

The static bundle's `manifest.json` records producer commits, checkpoint identity and file hashes. Activation caches and model weights are not included.
