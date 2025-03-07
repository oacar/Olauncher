<h1 align="center">Olauncher Fork. Minimal and clutter free</h1>  
</p><h3 align="center">Olauncher is a minimal app launcher for Android.

We try to balance customizability and clutter :)</h3>  


<img src="https://github.com/jooooscha/Olauncher/blob/409073e46228fcf4285f62f7ac0314fdf9eee97e/art/Header.png" width="1000">

# Forked with extra features

- Removed clutter, like ads and links
- You can rename apps in the app-drawer _(Renaming apps on the home screen is already supported. Just long-click on an app on the home screen and start typing)_
- Ability to change the app when clicking on the clock
- Ability to change the app when clicking on the date
- Align clock independently of home apps
- Change alignment of apps in app-drawer
- Change font size
- A lot of people have translated the app to the following languages. Many thanks to you ❤️
  - Chinese
  - English
  - French
  - German
  - Greek
  - Indonesian
  - Italian
  - Korean
  - Persian
  - Portuguese (European)
  - Russian
  - Spanish
  - Swedish
  - Turkish
- Removed internet permission


## Installation
[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
    alt="Get it on F-Droid"
    height="80">](https://f-droid.org/packages/app.olaunchercf/)
	<!-- <a href="https://github.com/jooooscha/Olauncher/releases/" target="_blank">
	<img src="https://github.com/jooooscha/Olauncher/blob/67fa100d3f3c76111e75007cedf8b0e568aa2a42/art/get-it-on-github.png" alt="Get it on GitHub" height="80"/> Useful when relsease will be automatically generated by github -->
</a>

- This fork is available on [F-Droid](https://f-droid.org/packages/app.olaunchercf/) <!-- & [Github](https://github.com/jooooscha/Olauncher/releases/) Useful when relsease will be automatically generated by github -->
- The latest stable version is on the [`main`](https://github.com/jooooscha/olauncher/tree/main) branch. You can clone it and build the app yourself.
	<!-- - A github action should build an apk for every [release](https://github.com/jooooscha/Olauncher/releases). Useful when relsease will be automatically generated by github -->
- The **original app** is also available on [Play Store](https://play.google.com/store/apps/details?id=app.olauncher), [F-Droid](https://f-droid.org/fr/packages/app.olauncher/) & [Github](https://github.com/tanujnotes/Olauncher).

## Contribute

- If you are unhappy with any part of the app or feel like missing something you can open a [**pull request**](https://help.github.com/articles/about-pull-requests/) or an [**issue**](https://github.com/jooooscha/Olauncher/issues/new) as you like
- Any help in translating Olauncher CF into other languages is greatly appreciated, If you don't know how to perform a  [**pull request**](https://help.github.com/articles/about-pull-requests/) then feel free to check out our dedicated [**Wiki**](https://github.com/jooooscha/Olauncher/wiki)
- Translate using Crowdin: https://crowdin.com/project/olaunchercf

## Licence

**Olauncher CF is under open source GPL3 license, meaning you can use, study, change and share it at will.**
Copyleft ensures it stays that way. From the full source, anyone can build, fork and use as you wish

* Olauncher CF does not have network access.
* Olauncher CF does not collect or transmit any data in any way whatsoever.

## Permissions

Olauncher CF uses the following permissions:

- `android.permission.EXPAND_STATUS_BAR`
	- Allows an application to expand or collapse the status bar.
- `android.permission.QUERY_ALL_PACKAGES`
	- Allows query of any normal app on the device, regardless of manifest declarations. Used to show the apps list.
- `android.alarm.permission.SET_ALARM`
	- Allows an application to broadcast an Intent to set an alarm for the user. Used to open the default alarm app if no other clock app is set in the settings.
