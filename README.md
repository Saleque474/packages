# packages
here I upload my packages.
there are two dart packages now.

1. PrayerTimes:
you can initial prayertimes instance in 2 way.
  . 
  ```dart
  var p = PrayerTimes(method:'MWL');
  
  ```
  
  there are more method name: 'MWL','ISNA','Egypt','Makkah','Karachi','Tehran','Jafari'
  or
  . 
  
   ```dart
  var p= PrayerTimes(prayerTimeMethods:PrayerTimeMethods.instituteOfGeophysicsUniversityOfTehran );
  ```
  
  and there are more. dart will suggest those automatically

after getting instance of PrayerTimes p;
you can get all time by :
  ```dart
var times=p.getTimes(date, latitude, longitude, timezone);
```
optional argument is formatInString, which takes . '12h' or '24h'
.
thats all;
```dart
var fajr=times.fajr;
var dhuhr=times.dhuhr;
```
and more

thats all


2. hijri_calculator:
hijri_calculator is incomplete . better not to use.
else youcan visit

this <a href="https://pub.dev/packages/hijri" >Hijjri</a> Dart Package
