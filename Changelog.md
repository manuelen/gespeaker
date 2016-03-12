### Version 0.8 (Sun, 13 Jun 2010) ###

  * Moved translators from .po files to doc/translators
  * New polish translation by Andrey J.
  * New DBUS interface to interact from external apps
  * Fixed minimum words gap from 5 to 0 in main UI ([Issue #20](https://code.google.com/p/gespeaker/issues/detail?id=#20))
![http://www.muflone.com/projects/gespeaker/0.8/en/about.png](http://www.muflone.com/projects/gespeaker/0.8/en/about.png)

### Version 0.7 (Sun, 13 Dic 2009) ###

  * New handlepaths module to reflect the changed directory structure.
  * New setup.py for distutils installation.
  * New packaging following the Debian policy.

![http://www.muflone.com/projects/gespeaker/0.7/en/about.png](http://www.muflone.com/projects/gespeaker/0.7/en/about.png)


### Version 0.6 (Sat, 18 Jul 2009) ###

  * Fixed audio testing localized string.
  * An error message is now shown if the audio player is not found instead of quietly ignore the error.
  * New spanish translation provided by David Prieto.
  * New mbrola support with more realistic voices.
  * Added mbrola voices to languages list.
  * Tabbed preferences dialog for new mbrola support.
  * Moved language, voice type and variants to base settings and pitch, volume, speed and gap sliders to advanced settings upon suggestion of frandavid100.
  * Added automatic txt extension on saving text file.
  * Added automatic wav extension on saving WAVE file. This was causing weird noises on playing the recorded track if it wasn't a .wav filename.

![http://www.muflone.com/projects/gespeaker/0.6/en/main.jpg](http://www.muflone.com/projects/gespeaker/0.6/en/main.jpg)
![http://www.muflone.com/projects/gespeaker/0.6/en/mbrola.jpg](http://www.muflone.com/projects/gespeaker/0.6/en/mbrola.jpg)

### Version 0.5 (Fri, 30 Jun 2009) ###

  * Added an extender separator for settings to allow maximum usage of the window with the text.
  * Added filters for load/save text dialogs.
  * Added support for recording the audio track to wave.
  * Added a statusbar showing the active record mode.
  * Added preferences dialog.
  * Added preferences save and reload for welcome message, window size, voice settings and expander status.
  * Added support for audio frontend: `ALSA` (aplay), `PulseAudio` (paplay) and user customized player command, with audio command test.
  * Added voice variants by scanning `/usr/share/espeak-data/voices/!v` folder for extra voice variants.
  * Fixed stock icon for `DialogFileOpenSave`.

![http://www.muflone.com/projects/gespeaker/0.5/en/main.png](http://www.muflone.com/projects/gespeaker/0.5/en/main.png)
![http://www.muflone.com/projects/gespeaker/0.5/en/preferences.png](http://www.muflone.com/projects/gespeaker/0.5/en/preferences.png)

### Version 0.4 (Fri, 20 Jun 2009) ###

  * Added `SubprocessWrapper.Popen` to wrap subprocess.Popen in order to support python versions prior to 2.6 which don't have the delete argument on object creation.
  * Added `TempfileWrapper.NamedTemporaryFile` to wrap tempfile's Popen object in order to support python versions prior to 2.6 which don't have terminate and send\_signal methods. Actually no more used, left for future usage.
  * Now gespeaker works with python version 2.4 and higher.
  * Temporary file for output to speech is created at program start so new temporary files are no longer created after each play.
  * Included pause and resume features.
  * New icon and logo, kindly provided by MIX.
  * New french translation provided by Emmanuel.

![http://www.muflone.com/projects/gespeaker/0.4/en/main.png](http://www.muflone.com/projects/gespeaker/0.4/en/main.png)

### Version 0.3 (Thu, 18 Jun 2009) ###

  * Used only for testing, never released
  * Added support for voice type (male/female) via +12 for female voice.
  * Removed escaped text substitution with a more secure temporary file with the text to play.
  * Substituted direct shell piping with more secure subprocess' piping.
  * Better control of external calls, now both espeak and player execution are polled for exitcode and terminated if requested.
  * Added documentation and artists parameters to `DialogAbout`.

### Version 0.2 (Sun, 14 Jun 2009) ###

  * Changed UI layout according to Gnome HIG specifications `http://library.gnome.org/devel/hig-book/stable/design-window.html.en`
  * Fixed `DialogAbout.set_icon_from_file` icon usage, which was wrongly hardcoded.
  * Symlinked copyright file to `/usr/share/doc/gespeaker/copyright`

![http://www.muflone.com/projects/gespeaker/0.2/en/main.png](http://www.muflone.com/projects/gespeaker/0.2/en/main.png)

### Version 0.1 (Sat, 13 Jun 2009) ###

  * Initial release

![http://www.muflone.com/projects/gespeaker/0.1/en/main.jpg](http://www.muflone.com/projects/gespeaker/0.1/en/main.jpg)