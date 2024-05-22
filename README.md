# Markdown2Handwrite

This is a simple web application that converts Markdown text to handwritten-style output, complete with mathematical equations rendered using KaTeX. 

### Features

* **Markdown Support:**  Write your text in Markdown format for easy formatting.
* **Handwriting Font:**  The output is styled to resemble handwriting using a custom font.
* **Mathematical Equations:**  Write and render mathematical equations using KaTeX.
* **Downloadable Output:**  Download the rendered output as a PNG image.

### How to Use

1. **Input:** Paste or type your Markdown text into the text area provided.
2. **Render:** Click the "Render Handwriting" button to see the converted output.
3. **Download (Optional):** Click the "Download as Image" button to download the rendered output as a PNG image.

### Technologies Used

* **HTML:**  Structure of the web page.
* **CSS:**  Styling the elements and simulating the lined paper effect.
* **JavaScript:** 
    * **Marked.js:**  Parsing the Markdown text.
    * **KaTeX:** Rendering mathematical equations.
    * **HTML5 Canvas:** Drawing the output for image download. 

### Customization

* **Font:** You can change the handwriting font by replacing `handwriting-font.ttf` with your desired font file and updating the `@font-face` rule in the CSS.
* **Line Height:** Adjust the `line-height` property in the `.lined-paper` CSS class to control the spacing between lines.
* **Line Color:** Change the color of the lines by modifying the `ctx.strokeStyle` value in the JavaScript code where the lines are drawn on the canvas.

### Potential Improvements

* **Real-time Conversion:**  Implement real-time conversion so the output updates as the user types.
* **More Font Options:**  Provide a selection of handwriting fonts for users to choose from.
* **Customizable Line Settings:**  Allow users to adjust the line spacing, color, and style. 
