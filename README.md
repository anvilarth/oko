# oko

Lightweight toolkit for image quality assessment and filtering.  
Designed for dataset curation, ML pipelines, and large-scale image evaluation.

The project focuses on automatic checks, scoring, and annotation-friendly outputs
to help decide whether an image is suitable for training or production use.

## Features

- Image quality checks (resolution, sharpness, noise)
- Content validation (artifacts, watermarks, compression issues)
- Metadata extraction & normalization
- Batch-friendly and pipeline-ready design

## Roadmap

### Phase 1 — Core
- [ ] Image loading & format validation
- [ ] Resolution & aspect-ratio checks
- [ ] Blur / sharpness detection
- [ ] Basic quality score aggregation

### Phase 2 — Quality & Content
- [ ] Noise & compression artifact detection
- [ ] Watermark / overlay heuristics
- [ ] Exposure & lighting analysis
- [ ] Face / subject presence checks (optional)

### Phase 3 — Dataset Integration
- [ ] Batch processing API
- [ ] JSON / Parquet output formats
- [ ] Threshold-based filtering
- [ ] Simple CLI interface

### Phase 4 — Advanced
- [ ] ML-based aesthetic scoring
- [ ] NSFW / safety hooks (pluggable)
- [ ] Human-in-the-loop review support
- [ ] Metrics & dataset reports

## Status

🚧 Early development — interfaces may change.