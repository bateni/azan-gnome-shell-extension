### Description

MyAzan is an Islamic prayer times extension for Gnome Shell (forked from [Azan](https://github.com/fahrinh/azan-gnome-shell-extension)).

![screen shot 2017-12-02 at 9 16 20 am](https://user-images.githubusercontent.com/55460/33510682-88954874-d741-11e7-99f7-c063aca0ff4c.png)

### Original features

- List 5 prayer times + other necessary times in Islam (Imsak, Sunrise, Sunset, Midnight).
- Show remaining time for the upcoming prayer.
- Show current date in Hijri calendar.
- Display a notification when it's time for prayer.

### New features

1. Add back three other calculation methods from PrayTime.js, in particular the two Shi'i ones
2. Add option to show concise prayer time list
3. Allow option to remove weekday
4. Improve weekday and month names
5. Fix bug for not properly saving location info
6. Improve nearest prayer message in the header
7. Complete list of available timezones

### Installation

1. Download repository
2. Run `make install`

Be careful.  The second step might delete your current extensions.  It is safer to run `make all` and then copy the extension from the `build` directory to the proper location for your gnome-shell.


### Changelog

- 0.1 : initial upload
- 1.0 : this fork
- 1.12 : adding new features (1-7)

### License

Licensed under the GNU General Public License, version 3

### Third-Party Assets & Components

- [PrayTimes.js](http://praytimes.org/manual/)
- [HijriCalendar-Kuwaiti.js](http://www.al-habib.info/islamic-calendar/hijricalendar-kuwaiti.js)
- [Azan](https://github.com/fahrinh/azan-gnome-shell-extension)
