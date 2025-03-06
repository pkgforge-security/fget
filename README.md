### ℹ️ About
This is a fork of [bp0lr/fget](https://github.com/bp0lr/fget) with some improvements

### 🖳 Installation
Use [soar](https://github.com/pkgforge/soar) & Run:
```bash
soar add 'fget#github.com.pkgforge-security.fget'
```

### 🧰 Usage
```mathematica
❯ fget --help
Usage of fget:
  -f, --follow-redirect      Follow redirects (Default: false)
  -H, --header stringArray   Add custom Headers to the request
      --no-folders           Don't store results on separate folders
  -o, --output string        Save to folder. Default: create results folder which will include a folder for each target
  -p, --proxy string         Add a HTTP proxy
  -r, --random-agent         Set a random User Agent
  -t, --timeout int          connection timeout (default 20)
      --unique               Use a unique name for each file
  -u, --url string           The url to check
  -v, --verbose              Display extra info about what is going on
  -w, --workers int          Number of workers (default 20)
```