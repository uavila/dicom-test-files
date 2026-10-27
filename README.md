# MedSlice DICOM Test Files

A curated collection of **anonymized DICOM sample files** for developers, researchers and QA engineers working with medical imaging.

Every file here is de-identified test/phantom data — no real patient information. Use them to test DICOM parsers, viewers, anonymization pipelines, or machine-learning preprocessing.

## Open any file instantly

Drag any `.dcm` file (or the whole folder) into the free in-browser DICOM viewer:

👉 **[Open in MedSlice](https://medslice.app/viewer/)**

MedSlice renders CT, MRI, X-ray, ultrasound, nuclear medicine and multiframe studies directly in the browser using WebAssembly — nothing is uploaded.

## Files

| File | Modality | Transfer syntax / encoding | Notes |
|---|---|---|---|
| `gdcm-CT-MONO2-8-abdo.dcm` | CT | Explicit VR, uncompressed | Abdominal CT |
| `nema-ct1_jpll.dcm` | CT | JPEG Lossless | NEMA reference |
| `nema-ct1_j2ki.dcm` | CT | JPEG 2000 | NEMA reference |
| `osirix-goudurix.dcm` | MR | Explicit VR, uncompressed | MR head (OsiriX sample) |
| `osirix-cerebrix.dcm` | MR | Explicit VR, uncompressed | MR brain (OsiriX sample) |
| `gdcm-CR-MONO1-10-chest.dcm` | CR (X-ray) | MONOCHROME1 | Chest radiograph |
| `gdcm-US-RGB-8-epicard.dcm` | US | RGB color, uncompressed | Color Doppler ultrasound |
| `nema-us1_j2ki.dcm` | US | JPEG 2000 | NEMA reference |
| `nema-nm1_j2kr.dcm` | NM | JPEG 2000 Lossless | Nuclear medicine |
| `multiframe-test1.dcm` | Multiframe | Uncompressed | Cine / multi-frame stack |
| `leadtools-flowers-8-mono2-rle.dcm` | Test pattern | RLE Lossless (8-bit) | Compression test |
| `leadtools-flowers-16-mono2-rle.dcm` | Test pattern | RLE Lossless (16-bit) | Compression test |
| `nema-vl2_j2kr.dcm` | VL | JPEG 2000 Lossless | Visible light |
| `bbmri-53323131.dcm` | MR | Explicit VR, uncompressed | Anonymized research sample |

## Provenance

These files originate from public, freely distributed DICOM test datasets:

- **NEMA** — DICOM standard reference images
- **GDCM** — Grassroots DICOM sample data
- **OsiriX** — publicly shared sample studies
- **LEAD Technologies** — RLE compression test images
- **BBMRI** — anonymized research imaging samples

They are provided as-is for testing and interoperability purposes only. They are **not** for diagnostic use and contain no patient-identifying data.

## License

The sample files retain their original upstream licensing. Attribution notes are preserved in the filenames. If you redistribute them, keep the original filenames intact.

The collection itself (this README and organization) is provided as-is for the benefit of the DICOM developer community.
