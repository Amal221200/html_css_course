# Images

## The ```<img>``` HTML element embeds an image into the document.

```
 <img src="/media/cc0-images/grapefruit-slice-332-332.jpg"
  alt="Grapefruit slice atop a pile of other slices" >
```

## The above example shows usage of the ```<img>``` element:
* The **src** attribute is required, and contains the path to the image you want to embed.
* The **alt** attribute holds a textual replacement for the image, which is mandatory and incredibly useful for accessibility — screen readers read the attribute value out to their users so they know what the image means. alt text is also displayed on the page if the image can't be loaded for some reason: for example, network errors, content blocking, or linkrot.

## There are many other attributes to achieve various purposes:
* Referrer/CORS control for security and privacy: see crossorigin and referrerpolicy.

* Use both **width** and **height** to set the intrinsic size of the image, allowing it to take up space before it loads, to mitigate content layout shifts.

* Responsive image hints with **sizes** and **srcset** (see also the ```<picture>``` element and our Responsive images tutorial).

## The image file formats that are most commonly used on the web are:

* APNG (Animated Portable Network Graphics) — Good choice for lossless animation sequences (GIF is less performant)
* AVIF (AV1 Image File Format) — Good choice for both images and animated images due to high performance.
* GIF (Graphics Interchange Format) — Good choice for simple images and animations.
* JPEG (Joint Photographic Expert Group image) — Good choice for lossy compression of still images (currently the most popular).
* PNG (Portable Network Graphics) — Good choice for lossless compression of still images (slightly better quality than JPEG).
* SVG (Scalable Vector Graphics) — Vector image format. Use for images that must be drawn accurately at different sizes.
* WebP (Web Picture format) — Excellent choice for both images and animated images.

Formats like WebP and AVIF are recommended as they perform much better than PNG, JPEG, GIF for both still and animated images.

SVG remains the recommended format for images that must be drawn accurately at different sizes.