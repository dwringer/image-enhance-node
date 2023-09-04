![enhance image usage graph](https://raw.githubusercontent.com/dwringer/image-enhance-node/main/image_enhance_usage.jpg)

### Enhance Image (PIL ImageEnhance wrapper)

Boost or reduce color saturation, contrast, brightness, sharpness, or invert colors of any image at any stage with this simple wrapper for pillow [PIL]'s ImageEnhance module. Please note that sharpness adjustments are very subtle and are no substitute for a gaussian blur or unsharp mask.

Color inversion is toggled with a simple switch, while each of the four enhancer modes are activated by entering a value other than 1 in each corresponding input field. Values less than 1 will reduce the corresponding property, while values greater than 1 will enhance it.