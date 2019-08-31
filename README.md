# 2DImageTransformsInExcel
2D Image Transforms in Excel - Translation, Rotation, and Scaling with Two Sampling Techniques


2D Image Transforms in Excel

ReadMe

This excel file allows you to gain an intuitive understanding of how simple 2D image transforms (affine transforms) works in the basic setting of an excel workbook.
This model allows you to input an image (current maximum dimensions of 38 x 38) and view that image on a “screen” after it has been transformed.
The allowed transformations are: translation (movement), rotation, and scaling.

"The model uses two image sampling approaches:
1. Direct sampling, which simply selects the nearest pixel in the source image for each screen location. This reproduces the image precisely for simple “neat” transforms like 90 degree / right-angle rotations or movement by integer pixels. However, a wave-like effect occurs when moving the image by a sub-pixel amount, and horizontal / vertical tranches are visible on rotation.
2. Blending by linear interpolation between nearest pixels. This produces a nice clean / smooth movement, rotation, and scaling effect - for the loss of “crispness”. However, that would only be an issue for small pixelated images such as those used in pixel art."

I hope this is of help for those trying to learn the basics of 2D image transformations!

Instructions:

First, you need to go to the sheet named "Screen and Calcs". Next, you need to run the macro called "Play" - you can do this using the "Play" button.

This macro assigns new functionality to the following keys:
 - "w", "a", "s", "d": press these to move the image up, down, and sideways
 - "r", "f": press these to scale the image up and down
 - "q", "e": press these to rotate the image left and right
 - "z": press this to change the pixel sampling approach
 - "esc": press this to end the macro and reset all key functionality
NOTE: this macro overrides these key's normal functionality - you must press ESC at the end of your session to reenble these keys in excel to their original functionality

Alternatively, you can press the "ANIMATE" button which will move the image along a predetermined path.


by s0lly
https://www.youtube.com/c/s0lly
https://www.instagram.com/s0lly.gaming/
https://twitter.com/s0lly
https://https://www.twitch.tv/s0llygaming

THE MODEL IS PROVIDED WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
