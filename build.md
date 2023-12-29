YouTube: 18.49.36  
Music-Extended (arm-v7a): 6.31.55  
Music-Extended (arm64-v8a): 6.31.55  
YouTube-Extended: 18.49.36  
Music (arm64-v8a): 6.31.55  
Music (arm-v7a): 6.31.55  
Twitter: 10.21.1-release.0  
Twitch: 17.6.1  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.3.1-all.jar  
Integrations: inotia00/revanced-integrations-0.130.1.apk  
Patches: inotia00/revanced-patches-2.208.1.jar  

YouTube
==
- feat(YouTube/Translations): update translation
`Arabic`, `Chinese Traditional`, `French`, `Greek`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- fix(YouTube Music/Hide category bar): clarify descriptions
- fix(YouTube Music/Hide general ads): `Hide interstitial ads` breaks layout https://github.com/inotia00/ReVanced_Extended/issues/1847
- fix(YouTube Music/Sponsorblock): changing segment behaviour in sponsorblock setting crashes the app https://github.com/inotia00/ReVanced_Extended/issues/1857
- feat(YouTube Music/Translations): update translation
`Korean`, `Russian`, `Turkish`, `Ukrainian`, `Vietnamese`


Reddit
==
- fix(Reddit/Change package name): force close occurs when patch is applied from RVX Manager https://github.com/inotia00/ReVanced_Extended/issues/1848


Etc
==
- when updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.

※ Compatible ReVanced Manager: [RVX Manager v1.18.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.18.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)

---
CLI: j-hc/revanced-cli-4.3.0-all.jar  
Integrations: ReVanced/revanced-integrations-1.1.0.apk  
Patches: ReVanced/revanced-patches-3.2.0.jar  

### [3.2.0](https://github.com/ReVanced/revanced-patches/compare/v3.1.0...v3.2.0) (2023-12-28)


### Bug Fixes

* **YouTube - Alternative thumbnails:** Clarify DeArrow support is for thumbnails ([#2531](https://github.com/ReVanced/revanced-patches/issues/2531)) ([828abb0](https://github.com/ReVanced/revanced-patches/commit/828abb0558926cd6557c79abcf1a04bfe2c719e6))
* **YouTube - SponsorBlock:** Export local statistics with saved settings ([f8365b4](https://github.com/ReVanced/revanced-patches/commit/f8365b4e3585328506887022ac6168045ac110b9))
* **YouTube:** Fix grammer mistakes in patch descriptions ([#2543](https://github.com/ReVanced/revanced-patches/issues/2543)) ([ebf5993](https://github.com/ReVanced/revanced-patches/commit/ebf599349c508067a28526267d82030b679df045))


### Features

* **Public API:** Deprecate `HideEmailAddressPatch` ([866bceb](https://github.com/ReVanced/revanced-patches/commit/866bcebdd990b964d3dfd5aea792e7fffaedbf44))
* **Public API:** Make `BottomControlsResource#addControls` public ([#2514](https://github.com/ReVanced/revanced-patches/issues/2514)) ([f4e2257](https://github.com/ReVanced/revanced-patches/commit/f4e2257072ca02003f7c272d6c0c8ef1aa6032ae))
* **Tiktok:** Add `Remember clear mode` patch ([#2509](https://github.com/ReVanced/revanced-patches/issues/2509)) ([048bf59](https://github.com/ReVanced/revanced-patches/commit/048bf592ef93ee5138aa1886be1644501f88964a))
* **YouTube - Hide ads:** Hide fullscreen ads ([bdc9a12](https://github.com/ReVanced/revanced-patches/commit/bdc9a129eff3a5051b8b37665b3243a8b61cbbac))
* **YouTube - Hide layout components:** Hide search result recommendations ([55cc7f1](https://github.com/ReVanced/revanced-patches/commit/55cc7f1c7722f56af6d33ea2bd09a1b99d635209))
* **YouTube - Theme:** Add classic dark color to presets ([#2542](https://github.com/ReVanced/revanced-patches/issues/2542)) ([4e1dc00](https://github.com/ReVanced/revanced-patches/commit/4e1dc0041d6693fba08e78514787407f933a6e41))
* **YouTube:** Add `Remove viewer discretion dialog` patch ([a07f83f](https://github.com/ReVanced/revanced-patches/commit/a07f83fe89ce577fc8bd904eacad5383a639b09b))
* **YouTube:** Remove `Hide email address` patch ([3b84305](https://github.com/ReVanced/revanced-patches/commit/3b84305a6b97800cb147f86c642f19689548aca5))




---  
