# Changelog

## [1.0.0] - 2025-07-29
- First published version of the FRZ plugin.
- Automatic creation of drone flight restriction zones around airfields in accordance with ICA 100-40 standards.
- Execution based on the selected feature, with support for UTM projections.
- Simple interface via a button in the QGIS toolbar.

## [1.1.0] - 2025-08-11
- Added support for generating drone flight restriction zones around helipads, in accordance with ICA 100-40.
- Zones are created based on the selected feature, generating concentric buffers with specific prohibited flight limit attributes.
- Inclusion of dedicated symbology for helipads and processing adjustments to ensure the uniqueness of the selected feature.
- General usability improvements and user feedback messages.

## [1.1.1] - 2025-08-11
- Added a warning to check if the layer is in a projected coordinate system (e.g., UTM).
- Fixed helipad symbology.
- Implemented geometry type validation:
    - Helipads require a Point layer type.
    - Airfields require a Line layer type.
- Processing is automatically stopped if the requirements are not met.

## [1.1.2] - 2025-08-17
- Fixed helipad symbology.
- Restricted processing to only **one selected feature**.
