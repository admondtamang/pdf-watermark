#### PDF WATERMARK

Watermark any pdf. Supports text as well as image.

**Options**

- **pdf_path** - your pdf path.
- **text** - To specify the text to be overlaid on the main image.
- **image_path** - To specify size of text over the main image, value ranged from 1 to 8.
- **output_dir** - To specify the output path. Default is 'watermark.{sourceFile ext}'.
- **imageOptions** - image option like opacity, size and more. supports other pdf-lib options'.
- **textOption** - text option like opacity, size and more. supports other pdf-lib options'.

**Example**

```
  await PDFWatermark({
    pdf_path: "./newsletter.pdf",
    text: "Gentech",
    output_dir: "./output.pdf",
    image_path: "./everest.png",
  });

```

### Inspiration

[https://pdf-lib.js.org/](https://pdf-lib.js.org/)

[http://thecodebarbarian.com/working-with-pdfs-in-node-js.html](http://thecodebarbarian.com/working-with-pdfs-in-node-js.html)

### License(MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## License

[MIT](LICENSE.md)
