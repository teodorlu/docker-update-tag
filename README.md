# docker-update-tag

Add or update your Dockerfile tags _with style_.

## Usage

`docker-update-tag scan DIR` - Scan `DIR` for docker image names.
`docker-update-tag` - Add or update a docker image tag.

## Installing

0. Install Babashka: https://github.com/babashka/babashka
1. Install Neil: https://github.com/babashka/neil
2. Install fzf: https://github.com/junegunn/fzf
3. Install bbin: https://github.com/babashka/bbin
4. Install docker-update-tag with bbin:

   ```
   bbin install com.github.ivarref/docker-update-tag --latest-sha
   ```

## Thanks!

Without [@teodorlu][teodorlu], [@borkdude][borkdude] and [@rads][rads], `docker-update-tag` wouldn't exist. Thank you!

[teodorlu]: https://github.com/borkdude/
[borkdude]: https://github.com/borkdude/
[rads]: https://github.com/rads/