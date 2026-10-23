# Real-chat jailbreak probe inspection

Detector-selected inspection candidates, with original model replies and context.
The new mixed-mining Qwen3.8-27B probe ranked 48,009 eligible cached WildChat requests.
The viewer contains 357 requests in 331 groups and 653 original rollouts, including 164 WildChat requests.

Open `inspection.html` through GitHub Pages. Use **Copy link to this view** to share filters, or download filtered JSONL and standalone HTML.

Scores and balanced WildJailbreak reference probabilities do not establish real-chat attack probability or response success. No new response judgments were made. The calibration/test WildChat pools are excluded from mining.

Source datasets: [WildChat-4.8M](https://huggingface.co/datasets/allenai/WildChat-4.8M), [Search Arena](https://huggingface.co/datasets/lmarena-ai/search-arena-24k), [Arena Expert](https://huggingface.co/datasets/lmarena-ai/arena-expert-5k), and [Arena Human Preference 140k](https://huggingface.co/datasets/lmarena-ai/arena-human-preference-140k). Source names, revisions, model IDs and original conversation context remain in the export.

The static bundle's `manifest.json` records producer commits, checkpoint identity and file hashes. Activation caches and model weights are not included.
