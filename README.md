# preload-images

A professional image preloader for JavaScript.

## Installation

You can install the package via npm:

```bash
npm install preload-img1
```

**Usage**

```bash
const ImagePreloader = require('preload-img1');

const maxImages = 190; // Adjust based on your images
const preloader = new ImagePreloader(maxImages);

preloader.preload((images) => {
    console.log('All images preloaded:', images);
    // You can now use the preloaded images
});

```

## Constructor

### ImagePreloader(maxIndex)

maxIndex: The total number of images to preload.

## Methods

### preload(callback)

callback: A function that gets called once all images are loaded, receiving the array of preloaded images as a parameter.

## Contributing

### Contributions are welcome! Please fork the repository and submit a pull request.
