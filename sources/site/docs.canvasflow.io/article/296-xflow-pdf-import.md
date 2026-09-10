# Source: https://docs.canvasflow.io/article/296-xflow-pdf-import

# XFlow PDF import

##### Canvasflow's XFlow service can import, process and convert print ready PDF's for use with any connected publish channel.

The XFlow PDF import can process almost any PDF, but for best results please see below for the recommended guidelines.

### PDF

- Should be sent as a **single, multi-page** PDF
- All pages in a multi-page PDF **must** be individual pages (no spreads)
- All pages should be in the correct order
- Trim-boxes should always be set correctly to display only the relevant page information with **no bleed or overlap** with the opposite page of the spread
- Security should not be used
- Compression should not be used

### Text

- All text and fonts should be fully embedded in the PDFs
- Text should not be flattened, rasterised or paths
- All text will be extracted as is from the PDFs. If Glyphs or fonts are used that change the look and output of a character, the character will be extracted. This causes some small-caps fonts to be rendered as lower-case for example. Ensure that the characters used are upper-case in these instances, so the extracted text will be upper-case as well.

### Images

- Where possible, flattening of images and/or layers should be avoided so images can be extracted as separate items
- Down-sampling should be avoided where possible. Ensuring a crisp look at max 2400px width or height for large images is the goal
- **300DPI+ images are preferred** and will generate the best results

Still need help? [Contact Us](https://docs.canvasflow.io/article/296-xflow-pdf-import#) [Contact Us](https://docs.canvasflow.io/article/296-xflow-pdf-import#)

Last updated on January 25, 2024

No results found