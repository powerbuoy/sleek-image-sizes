# Sleek Image Sizes

Adds the `Sleek\ImageSizes\register()` function which overrides WordPress' built-in thumbnail sizes (thumbnail, medium, medium_large and large) using the dimensions passed to the function, e.g: `Sleek\ImageSizes\register(1920, 1080, ['center', 'center']);` where large will be 1920x1080, medium_large will be 75% of that size, medium 50% and thumbnail 25%.
