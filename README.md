The Shader responds to the Red and Green channels.

The red channel corresponds to "rows" in the shader parameters on the shaderbox.
The green channel corresponds to "cols" in the shader parameters.

How I have designed it, light can influence the input to the shader. 
This allows the colors to change with lighting, but still remaining the colors of the palette.

As I have used it, Red is for lighting within each palette, and green is which set of colors to use.

The two channels can be swapped: the only side-effect is the appearance of the gradient in the editor, under the shader parameters, as well as the way in which you would have to organize the color palettes you add.

Enjoy!
