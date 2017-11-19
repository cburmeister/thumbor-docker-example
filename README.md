thumbor-docker-example
======================

Thumbnails as a service via [thumbor](http://thumbor.org/) wrapped with
[docker](https://www.docker.com://www.docker.com/).

---

## Usage

Start up the service via `docker-compose up -d`.

There is a single image in the `./data` directory that is 1920 x 1080 pixels.

Want it in a smaller dimension?
```bash
open http://thumbor.docker:8000/unsafe/500x500/three.6.mafia.jpg
```

Learn more about filtering, cropping, re-sizing, and more in the [thumbor
documentation](http://thumbor.readthedocs.io/en/latest/usage.html).
