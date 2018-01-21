# scoop-bucket

```
scoop bucket add icalder https://github.com/icalder/scoop-bucket
scoop install icalder/oc
```

## Apps
* OpenShift oc cli tool [OpenShift Origin](https://www.openshift.org/download.html)

## Dev notes
To check autoupdate, cd to $HOME\scoop\buckets\icalder, then run:

```
$HOME\scoop\apps\scoop\current\bin\checkver.ps1 oc $pwd
```