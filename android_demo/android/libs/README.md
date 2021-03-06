Building the Open Location Code JAR file
==

Using the source in the
[Java](https://github.com/google/open-location-code/blob/master/java/com/google/openlocationcode/OpenLocationCode.java)
implementation, build a JAR file and put it in this location.

Assuming you've downloaded this repository locally, run:

```
jar cf openlocationcode.jar ../../../java/com/google/openlocationcode/OpenLocationCode.java
```

Why don't we include a JAR file here?
--

Basically, we want to make sure that we don't fix a bug in the Java implementation and forget to
update this JAR file.

Why don't we have a Maven repository?
--

So far, we've only had one request. If you would like to be able to pull the library via Maven,
file an issue and we'll consider it.
