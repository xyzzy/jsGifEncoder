# This is the repository of :star: jsGifEncoder :star:

`jsGifEncoder` is an ultra fast GIF encoder written in javascript.

The code was created in may 2011 and was intended to create and load images for animations.

Output is a data URL scheme as described in rfc2397.

The demo html can be found https://www.rockingship.net/jsGifEncoder/jsGifEncoder.html

## Usage

Invocation example:

```
var encoder = new GifEncoder(width, height);
var data = encoder.encode(bpp, red, green, blue, pixels);

```

Inject into HTML

```
document.getElementById('img').src = data;

```

## Versioning

This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html). 
For the versions available, see the [tags on this repository](https://github.com/xyzzy/jsGifEncoder/tags).

## License

This project is licensed under Affero GPLv3 - see the [LICENSE](LICENSE) file for details.
