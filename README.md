# Emotion Classifier Model Assets

Versioned inference bundles for a six-class text emotion-classification demo. The release contains model weights and minimal inference metadata; it does not contain the training dataset, validation/test examples, or API credentials.

## Downloads

Latest pinned release: [v2026.11.23](https://github.com/Aik358/emotion-classifier-models/releases/tag/v2026.11.23)

| Asset | Contents | Approx. size |
|---|---|---:|
| `classic_models.zip` | TF-IDF and classical baselines | 9.2 MB |
| `roberta_base_c3_c5.zip` | RoBERTa-base checkpoint; two experiment entries share these weights | 480.2 MiB |
| `roberta_large_c6.zip` | RoBERTa-large classifier with auxiliary pairwise heads | 1.33 GiB |
| `multilingual_e5_e1.zip` | Fine-tuned multilingual-E5 classifier | 470.0 MiB |
| `multilingual_e5_teacher.zip` | Frozen multilingual-E5 encoder and classifier metadata | 470.1 MiB |
| `bert_base.zip` | Fine-tuned BERT-base classifier | 418.6 MiB |

All six unique archives total approximately 3.13 GiB. The release also provides `download-manifest.json` with exact byte counts and SHA-256 digests. Verify each archive before extraction. Public assets can be downloaded without an account.

## Model provenance

The bundles are based on upstream model families including multilingual E5, RoBERTa, and BERT. Consult each upstream model card and license before reuse. This repository distributes the listed inference bundles and does not replace or extend upstream licenses.

## Evaluation note

Interpret any associated metrics under the evaluation protocol and limitations documented by the distributing research group. Results from a previously inspected test split are descriptive and should not be presented as estimates from an untouched holdout.