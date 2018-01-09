# Image-Vectorizer
Vectorize images (JPEG, PNG) with variable quality

## Client

Either enter a URL of an image, or pick an image from the local system to vectorize.

The result is a `base64` string, and an Image of the vectorized original image (use right+click and save as... to download locally)


## Server

To install run `npm install` on the `/server` folder

We recommend using the `forever` plugin to install as a service https://www.npmjs.com/package/forever
