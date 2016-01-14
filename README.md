# lukebennett/hugo

Docker image for the [Hugo](http://gohugo.io) static site generator. Available on the [Docker Hub](https://hub.docker.com/r/lukebennett/hugo).

## Usage

For ease of use, add the following alias to your shell:

```
alias hugo='docker run --rm -v $(pwd):/var/www -p 1313:1313 -u $(id -u):$(id -u) lukebennett/hugo'
```

This allows Hugo to be used as if installed on the host machine e.g.:

```
hugo server -w
```

## Credits

Thanks to [publysher/hugo](https://hub.docker.com/r/publysher/hugo/) for providing a helpful headstart.

## License (MIT)

Copyright (c) 2016 Luke Bennett

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.