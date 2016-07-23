# check_meteolux
Nagios style plugin to read Meteolux CSV (Opendata) and check for weather warnings. For HaxoGreen we wanted an option to quickly see storm warnings as we've been plagued by rain and storms all the freakin' time.

Sample output:
```
METEOLUX WARNING - Last Update: 23-07-2016 06:54:02; State: yellow; Avis d’orages: Samedi 11:00 à 18:00, pour tout le pays: Risque d'orages locales pouvant donner un cumul jusqu'à 15 l/m2.; Region: sud
```
```
usage: check_meteolux [-h] [-V] [-u NAME] [-r NAME]

Check Meteolux weather warnings

optional arguments:
  -h, --help            show this help message and exit
  -V, --version         show program's version number and exit
  -u NAME, --url NAME   URL of CSV file
  -r NAME, --region NAME
                        Warning reagion. Can be nord or sud

```
