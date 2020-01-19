
## submit a hexagon

- First, make sure you're the owner of the hexagon you are submitting!
- Fork this repo
- Add your hexagon to the `hexagons/` folder in dimensions **181x209** as a **png**.
- Add a new `.json` file in `meta/` with the metadata for your hexagon. Use this template:

```json
{
  "name": "dat",
  "author": "max ogden",
  "license": "CC0",
  "raster": "hexagons/dat.png",
  "description": "this is optional!",
  "order_online_url": "this is optional. should be a link to where people can buy the sticker online"
}
```

Make sure `name` only has lowercase letters, numbers and hyphens. Remove any optional fields you aren't using, and make sure the last field doesn't have a trailing comma at the end of it.

Then make a pull request to this repo. 

## resources

Tools are available in several programming languages to help automate sticker creation based on the sticker standard:

- [hexsticker](https://github.com/fridex/hexsticker) uses python
- [hexSticker](https://github.com/GuangchuangYu/hexSticker) uses R

# for maintainers

You no longer need to do this!

<del>
After merging PRs/adding new hexes you have to build the site:

- `npm run build`
- add + commit
- `git push origin gh-pages`
</del>
