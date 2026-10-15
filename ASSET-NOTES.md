# Asset and animation notes

- `assets/id.png` is the original generated portrait PNG copied byte-for-byte from the provided generated asset.
- `assets/right_pointing.png` is the original generated pointing portrait PNG copied byte-for-byte from the provided generated asset.
- Both images are embedded as data URIs inside the SVGs that use them; no remote image or script requests are made.
- Display font: Inter Display Black, converted to WOFF2 from the system-installed Inter font. License text: `fonts/INTER-LICENSE.txt` (SIL Open Font License).
- Monospace font: DejaVu Sans Mono, converted to WOFF2 from the system-installed DejaVu font. License text: `fonts/DEJAVU-LICENSE.txt` (Bitstream Vera/DejaVu license).
- Brand marks in the connect graphic are simple inline decorative approximations, not downloaded assets. The actual clickable official URLs are outside the SVG in `README.md`.
- SVGs use inline CSS and SMIL only. They contain no JavaScript or `foreignObject`; all SVG references are local fragment IDs or embedded data URIs.
- Statistics are intentionally omitted because no dated verified metrics were provided.
