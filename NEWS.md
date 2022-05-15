### 2.11.1 (2022-05-07)

* The app no longer requires a special wake lock permission for keeping the
  screen turned on, but uses another technique instead which might also
  turn out beneficial to CPU and power usage.
* Target SDK version has been increased from 23 (Android 6.0) to 24
  (Android 7.0).

### 2.11.0 (2022-05-02)

* New translation: Italian.
* Updated translations: French and Norwegian Bokmål.
* Screens with aspect ratios between 1.86 and 2.1 should no longer have
  black bars appear at the top or bottom of the screen.

### 2.10.0 (2022-03-28)

* New delay type: Capped Fischer.

### 2.9.0 (2022-02-06)

* New translation: Turkish, by Alparslan Şakçi.

### 2.8.0 (2022-01-10)

* New translation: German, by Petra Mirelli.
* Bugfix: The alarm now stops playing when hitting the reset button.

### 2.7.0 (2022-01-01)

* New translation: Spanish, by Daniel Garcia Pallaviccini.

### 2.6.2 (2021-09-20)

* Fixed a bug where Bronstein delay games with no initial time would run
  into negative time.
* Bronstein delays are displayed on the same line as the total time again
  when decisecond display is disabled.

### 2.6.1 (2021-09-12)

* Text fixes.

### 2.6.0 (2021-09-04)

* New translation: French, by Sitavi.

### 2.5.1 (2021-08-21)

* The about screen is now scrollable to be readable when there is less
  screen space.

### 2.5.0 (2021-06-19)

* Game time and delay can be specified in seconds, minutes or hours.
* Time display shows hours.
* Time display can optionally show deciseconds.

### 2.4.1 (2021-06-12)

* Fixed the pause button for Bronstein delay games with no initial time.

### 2.4.0 (2021-05-30)

* Players can now have different initial game time.

### 2.3.0 (2021-05-28)

* Bronstein delay games with no initial time is now supported.

### 2.2.1 (2021-02-07)

* With Fischer delay, the extra time is now added at the end of player
  turns, instead of at the beginning.

### 2.2.0 (2020-07-06)

* Added an option to use a black background on the main game screen for
  potential power savings with OLED screens.

### 2.1.2 (2019-05-30)

* Fixed a bug causing player 1 to sometimes not receive the initial delay.
* Fixed a bug causing some delays to be skipped after resuming a paused
  game.

### 2.1.1 (2019-04-28)

* New translation: Norwegian Bokmål.

### 2.1.0 (2019-04-14)

* Fixed an issue with clocks disappearing on Android 7.0 and above.
* The minimum Android version was corrected to Android 5.0 and above, since
  SCC is using scalable vector graphics.
* Material theme is now applied in menus and dialogs.

### 2.0.0 (2019-03-24)

* Major overhaul of the user interface.
* Should now work on modern Android versions.

### 1.2.0 (2010-11-28)

* Added ability to move SCC to SD storage.

### 1.1.3 (2010-11-21)

* Fixed a bug that could cause a crash in certain situations (related to
  ringtone).

### 1.1.2 (2010-11-06)

* Fixed another bug. Leaving an option blank should no longer cause a crash
  – it will use the default value instead.

### 1.1.1 (2010-11-06)

* Addressed a crash on startup.

### 1.1.0 (2010-09-27)

* Added haptic feedback option.
* Cleaned up some more code.

### 1.0.3 (2010-09-24)

* Changed the package name to conform to Google's naming standards.
* First version available on the Market!

### 1.0.2 (2010-09-13)

* Fixed a bug that caused one clock to incorrectly continue running after
  "Reset Clocks" was used.
* Made the app properly pause the game when Home or Back are used to exit.
* Fixed the colouring of the clock text in cases where time dips below 60s
  then rises above it again (due to Fischer delay).

### 1.0.1b (2010-09-12)

* Fixed a bug that caused delays to be applied twice if a player's clock
  was paused and then unpaused.

### 1.0.0b (2010-09-11)

* First beta release, with all planned 1.0 features.