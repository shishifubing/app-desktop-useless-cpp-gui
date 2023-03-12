<div align="center" markdown="1">

# [`app-desktop-useless-cpp-gui`][url-repo]

[![License][badge-license]][url-license]
[![Status][badge-status-abandoned]][url-repo]
[![Version][badge-version]][url-version]
[![Release][badge-workflow-release]][url-release]
[![Coverage][badge-sonar-coverage]][url-sonar]
[![Lines of Code][badge-sonar-ncloc]][url-sonar]
[![Conventional Commits][badge-conventionalcommits]][url-conventionalcommits]

[![Get as an Appimage][badge-appimage]][url-release-latest]

Desktop GUI

</div>

## About The Project

In 2020 I've decided to make an app. For some reason, 
I've decided to use C++ and Qt5 and to make a GUI first. 
Later when I started implementing logic, I realized C++ 
is not suitable for that particular app, so I abandoned it.

### Features

- Basic C++, Qt5
- Packaged as an AppImage

### Usage

```bash
curl https://api.github.com/repos/shishifubing/app-desktop-useless-cpp-gui/releases/latest \
  | jq -r .assets[].browser_download_url                                                   \
  | xargs wget
chmod +x app-desktop-useless-cpp-gui.AppImage
./app-desktop-useless-cpp-gui.AppImage
```

### Demo

> **Note**
>
> WebM is broken on Edge, try another browser

[Screencast.webm](https://user-images.githubusercontent.com/97828377/218940781-ffbede8c-d3a1-497c-aabf-484bcea08b12.webm)

<!-- relative links -->

<!-- project links -->

[url-repo]: https://github.com/shishifubing/app-desktop-useless-cpp-gui
[url-license]: https://github.com/shishifubing/app-desktop-useless-cpp-gui/blob/main/LICENSE
[url-release-latest]: https://github.com/shishifubing/app-desktop-useless-cpp-gui/releases/latest
[url-workflow-build]: https://github.com/shishifubing/app-desktop-useless-cpp-gui/actions/workflows/build.yml?branch=main
[url-sonar]: https://sonarcloud.io/dashboard?id=shishifubing_app-desktop-useless-cpp-gui
[url-release]: https://github.com/shishifubing/app-desktop-useless-cpp-gui/actions/workflows/release.yml
[url-version]: https://github.com/shishifubing/app-desktop-useless-cpp-gui/releases/latest

<!-- external links -->

[url-conventionalcommits]: https://conventionalcommits.org

<!-- project badge links -->

[badge-workflow-release]: https://img.shields.io/github/actions/workflow/status/shishifubing/app-desktop-useless-cpp-gui/release.yml?branch=main&label=release&logo=github
[badge-version]: https://img.shields.io/github/v/release/shishifubing/app-desktop-useless-cpp-gui?label=version
[badge-license]: https://img.shields.io/github/license/shishifubing/app-desktop-useless-cpp-gui.svg
[badge-status-abandoned]: https://img.shields.io/badge/status-abandoned-red


<!-- other badge links -->

[badge-conventionalcommits]: https://img.shields.io/badge/conventional--commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white
[badge-appimage]: https://raw.githubusercontent.com/AppImage/docs.appimage.org/master/source/_static/img/download-appimage-banner.svg

<!-- sonar badge links -->

[badge-sonar-vulnerabilities]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=vulnerabilities
[badge-sonar-sqale_index]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=sqale_index
[badge-sonar-security_rating]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=security_rating
[badge-sonar-reliability_rating]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=reliability_rating
[badge-sonar-alert_status]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=alert_status
[badge-sonar-sqale_rating]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=sqale_rating
[badge-sonar-ncloc]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=ncloc
[badge-sonar-duplicated_lines_density]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=duplicated_lines_density
[badge-sonar-coverage]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=coverage
[badge-sonar-code_smells]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=code_smells
[badge-sonar-bugs]: https://sonarcloud.io/api/project_badges/measure?project=shishifubing_app-desktop-useless-cpp-gui&metric=bugs
