# Garmin tools

Personal Garmin projects extracted from `zitian-FF/tools`, preserving their
relevant commit history. Unrelated wiki tooling is excluded.

- [RouteNav](garmin-route-nav/README.md): watch navigation and phone route planner.
- [AI Girls watch face](garmin-watchface/README.md): Vivoactive 5 watch face.

After publishing with GitHub Pages, the planner is available at
`https://tianz88-bit.github.io/garmin-tools/garmin-route-nav/planner/`.

Migration does not transfer route Gists or browser-local settings. The existing
Gist can remain on its original account. Configure the planner manually on the
new origin; never commit tokens, route data, or developer signing keys.
Watchface portraits are generated separately and are not included in Git.

## Checks

Run `python test_gpx_to_route.py` and `python test_nav_logic.py` in
`garmin-route-nav/tools`, then `node test_routecore.js` in
`garmin-route-nav/planner/test`.
