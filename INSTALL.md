### [broot](https://dystroy.org/broot)

#### Install using Git

If you are a Git user, you can install the theme and keep it up to date by cloning the repo:

```bash
git clone https://github.com/dracula/broot.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/broot/archive/main.zip) option and unzip it.

#### Activating theme

1. Find your broot config folder: open broot, press <kbd>?</kbd>, and look for the path to `conf.hjson` (usually `~/.config/broot`);
2. Copy `dracula.hjson` into the `skins` folder inside it;
3. In `conf.hjson`, find the `imports` section and change the dark skin entry to `skins/dracula.hjson`:

   ```hjson
   {
       luma: [
           dark
           unknown
       ]
       file: skins/dracula.hjson
   }
   ```

4. Boom! It's working ✨

> The skin uses RGB colors, so your terminal needs true-color support.
