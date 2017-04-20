# vogar
fork of https://code.google.com/archive/p/vogar/source/default/source

Attempt to build the project and make it work with android and caliper tools again.

In order to build you need to have apache ant(http://ant.apache.org/) and android sdk (https://developer.android.com/studio/releases/sdk-tools.html).

Create local.properties file with following content:

```
buiid.platform.dir=$ANDROID_HOME/platforms/$PLATFORM
```
$ANDROID_HOME - path to your android sdk
$PLATFORM - any installed platform folder for example platform-23. It should have an android.jar inside.

run command
```
ant jar
```

to use the tool you could use command:

```
java -jar build/vogar.jar

```

For usage samples check this:
https://code.google.com/archive/p/vogar/wikis/Examples.wiki
