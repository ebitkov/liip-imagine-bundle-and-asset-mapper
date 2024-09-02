# A simple reproducer for [liip/LiipImagineBundle#1608](https://github.com/liip/LiipImagineBundle/issues/1608)

## How to use

1. Install Composer dependencies<br>
   `composer install`
2. Start local dev server<br>
   `symfony serve -d`
3. Open demo page<br>
   `https://127.0.0.1:8000`

On the demo page you'll find a working image just using the `asset` function and a broken image with a `imagine_filter`
applied.