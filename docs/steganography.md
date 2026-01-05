# Steganography Tools – Complete CTF-Oriented List

This is a **strict Markdown** list you can directly use in your web-based registry (MkDocs / Docusaurus / GitHub Pages).

---

## 1. General / First-Look Tools (Always Use)

* `file`
* `strings`
* `xxd`
* `hexdump`
* `binwalk`
* `binwalk -e`
* `foremost`
* `exiftool`
* `pngcheck`
* `pdfinfo`
* `identify` (ImageMagick)

---

## 2. Image Steganography Tools

### LSB / Bit-Plane / Pixel Analysis

* `zsteg` (PNG, BMP)
* `stegsolve`
* `StegOnline`
* `SilentEye`

### Image Metadata & Structure

* `exiftool`
* `pngcheck`
* `jpeginfo`
* `jhead`
* `tiffinfo`

### Visual & Channel-Based Analysis

* `ImageMagick` (`convert`, `identify`)
* `GIMP`
* `Photoshop`

---

## 3. Password-Based Steganography

* `steghide`
* `OpenStego`
* `SilentEye`
* `OutGuess`

---

## 4. Audio Steganography

* `Audacity`
* `sox`
* `wavsteg`
* `steghide` (audio modes)
* `DeepSound`

---

## 5. Video Steganography

* `ffmpeg`
* `SteganoVideo`
* `OpenStego`

---

## 6. Text Steganography

* `SNOW`
* `StegCloak`
* `Whitespace steganography`

---

## 7. Compression / Embedded Data Detection

* `binwalk`
* `7z`
* `unzip`
* `tar`
* `gzip`
* `bzip2`

---

## 8. Encoding & Multi-Layer Steg Helpers

* `CyberChef`
* `base64`
* `xxd`
* `xor scripts`
* `rot / caesar`

---

## 9. Online Steganography Tools

* StegOnline
* Aperi'Solve
* dCode Steganography

---

## 10. Rare / Advanced / CTF-Specific Tools

* `stegcracker`
* `stego-toolkit`
* `zlib-flate`
* `bmpsteg`
* `PngSuite`

---

## 11. Manual / Human-Based Analysis (Do Not Skip)

* Zoom & inspect pixels
* Adjust brightness / contrast
* Flip / rotate image
* Change color spaces

---

## 12. Notes

* No single tool finds everything
* Always assume **multi-layer steganography**
* Many CTFs combine **steg + crypto + encoding**

---

**Last rule:** If a tool was used in a writeup and is missing here — add it. Thanks for reading.
