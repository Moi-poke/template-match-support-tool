# THIRD_PARTY_NOTICES

This project uses the following third-party libraries.

## 1. OpenCV.js

- Project: OpenCV / OpenCV.js
- Expected local path: `./vendor/opencv/opencv.js`
- Upstream information:
  - OpenCV official license page states that OpenCV 4.5.0 and higher are licensed under Apache License 2.0.
  - OpenCV 4.4.0 and lower are licensed under the 3-clause BSD license.
- This package assumes that you will bundle a modern OpenCV.js build based on OpenCV 4.5.0 or higher.
- If you instead bundle an older OpenCV.js file based on OpenCV 4.4.0 or lower, replace the license file in `licenses/` accordingly.

Included license file in this package:
- `licenses/OpenCV-LICENSE.txt` (Apache License 2.0 template for OpenCV 4.5.0+ usage)

## 2. JSZip

- Project: JSZip
- Expected local path: `./vendor/jszip/jszip.min.js`
- JSZip is dual-licensed under MIT or GPLv3.
- This package is prepared for the MIT option.

Included license file in this package:
- `licenses/JSZip-MIT-LICENSE.txt`

## Notes

- Keep third-party license texts together with distributed copies of this project.
- If you update bundled library versions, review their upstream license files again before release.
