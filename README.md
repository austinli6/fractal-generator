Mandelbrot Set with Zoom

This project is an interactive Mandelbrot fractal generator built using HTML5 and JavaScript. It allows users to zoom into specific areas of the fractal by clicking on the canvas.

Features

Dynamic Fractal Rendering: Generates the Mandelbrot fractal using the <canvas> element.

Interactive Zooming: Click anywhere on the canvas to zoom into that point.

Customizable Parameters: Adjust fractal range, resolution, and maximum iterations directly in the code.

How to Use

Save the code in a file named mandelbrot_zoom.html.

Open the file in any modern web browser (e.g., Chrome, Firefox, Edge).

Click anywhere on the fractal to zoom into that location.

Technical Details

The visible region of the fractal starts with:

X range: -2.0 to 1.0

Y range: -1.5 to 1.5

Clicking adjusts the center of the view to the clicked point and reduces the visible range by half.

The rendering uses the following formula:

Z(n+1) = Z(n)^2 + C

Where Z is a complex number and C is a constant determined by the pixel location.

Customization

To modify the behavior or appearance of the fractal:

Canvas Size: Update canvas.width and canvas.height in the script.

Zoom Factor: Change the zoomFactor variable (default is 0.5).

Max Iterations: Adjust the maxIter variable for more detail.

Future Improvements

Zoom Out: Add functionality to zoom out (e.g., right-click or a keyboard shortcut).

Smooth Zoom: Enable zooming with the mouse wheel.

Higher Performance: Use WebGL for faster rendering.
