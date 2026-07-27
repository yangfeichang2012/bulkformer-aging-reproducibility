# BulkFormer skeletal-muscle aging benchmark: reproducibility archive

This repository hosts the versioned reproducibility archive for:

> Study-held-out benchmarking reveals domain-decodable but non-transferring BulkFormer representations for skeletal-muscle age prediction

Authors: Chuan-Xin Duan and Lang Yang.

## Main result

The benchmark used 267 healthy or natural-state participant representatives from eight public skeletal-muscle transcriptomic studies. The primary pretrained mean-pooled representation had an equal-study mean absolute error of 25.335 years, compared with 7.716 years for the selected conventional Elastic Net comparator. The paired difference was +17.619 years, and the representation had higher error in all eight held-out studies.

## Versioned archive

Release `v0.5.0` provides:

- `BulkFormer_Aging_Reviewer_Package_v0.5_2026-07-21.zip`
- 244 manifest-tracked files
- ZIP size: 22,873,076 bytes
- SHA-256: `e55860f6f8a94df63069a2825b15cae9600f67a5636c7bba6708bdd1b4b26b10`

The archive contains the manuscript snapshot, tables, figures, audit evidence, predictions, fixed analysis intermediates, frozen representation arrays, analysis code, environment locks and a clean-room recomputation entry point.

## Scope and exclusions

The archive supports recomputation from frozen features. It does not reproduce end-to-end feature extraction and does not include:

- BulkFormer checkpoint files;
- graph or graph-weight files;
- raw FASTQ/SRA data;
- all upstream expression matrices;
- local credentials, tokens or private participant data.

Public source accessions and exact tested component hashes are documented in the archive. Potential overlap between the public cohorts and BulkFormer pretraining remains unknown.

## Verification

After downloading the release asset:

```text
SHA256(BulkFormer_Aging_Reviewer_Package_v0.5_2026-07-21.zip)
= e55860f6f8a94df63069a2825b15cae9600f67a5636c7bba6708bdd1b4b26b10
```

Extract the ZIP and begin with `README.md`, `PACKAGE_MANIFEST.json` and `cleanroom/run_cleanroom_reproduction.py`.

## License

Original code, documentation and derived reproducibility materials in this repository are released under the MIT License. Upstream software, public source datasets and cited publications remain subject to their original licenses and terms. No upstream model checkpoint or graph file is redistributed.
