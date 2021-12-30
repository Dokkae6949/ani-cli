<p align="center"><img src="https://capsule-render.vercel.app/api?type=soft&fontColor=e5ab3e&text=pystardust/ani-cli&height=150&fontSize=60&desc= beautiful, documented and portable.&descAlignY=75&descAlign=60&color=00000000&animation=twinkling"></p> 

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)](https://GitHub.com/pystardust/ani-cli/graphs/commit-activity)
[![Maintainer](https://img.shields.io/badge/maintainer-ura43-blue)](https://github.com/ura43)
[![Maintainer](https://img.shields.io/badge/maintainer-RayGL-blue)](https://github.com/RaynardGerraldo)
![Linux](https://img.shields.io/badge/os-linux-brightgreen)
![Mac](https://img.shields.io/badge/os-mac-yellow)
![Windows](https://img.shields.io/badge/os-windows-yellow)

A cli to browse and watch anime. This tool scrapes the site [gogoanime](https://gogoanime.pe).

> Thank you @RaynardGerraldo for fixing the crippling issues 221 and 202

## Usage
  ```
  Watch anime
    ani-cli (OPTION) (query)

  Options
    -h show helptext
    -d download episode
    -H continue where you left off
    -D delete history
    -q set video quality (**best**/worst/360/480/720/1080)
    --dub play the dub version if present
    -v use VLC as the media player
  
  Multiple episodes can be chosen given a range
    Choose episode [1-13]: 1 6
    This would choose episodes 1 2 3 4 5 6
  ```

## Dependencies

### Essential
```
grep
curl
sed
ffmpeg
```

### Optional
```
mpv - The default video player (recommended)
vlc - An alternative video player
```
  
## Install

### Linux
```sh
git clone https://github.com/pystardust/ani-cli.git
cd ani-cli
sudo make
```

### Mac
```sh
brew install util-linux
git clone https://github.com/pystardust/ani-cli.git
cd ani-cli
sudo make
```

### Windows
* Download and install [gitbash](https://git-scm.com/downloads)
* Download and install vlc (mpv needs further testing)
* Add vlc to Windows Env PATH like so: C:\Program Files\VideoLAN\VLC.
* Open git bash by right-clicking and choosing "Run as administrator"
* Run the following commands
```sh
git clone -b windows-vlc https://github.com/pystardust/ani-cli.git
cd ani-cli
chmod +x ani-cli-win
./install
```

## Disclaimer

The disclaimer of this project can be found [here.](./disclaimer.md)
