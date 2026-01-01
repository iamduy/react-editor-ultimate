# Changelog

## [1.0.4] - 2026-01-01

### Added

- **ImagePasteUploadPlugin**: New plugin to intercept paste events and handle base64 images (e.g., from Google Docs, MS Word). It converts base64 images to Files and triggers the `onUpload` callback if provided.
