When running a build scan with the `--quiet` flag, the publishing output is still sent to standard output.

example:
```
build-scan-sample gradle clean build --quiet --scan 2>/dev/null

Publishing build scan...
https://gradle.com/s/m5h66xqaco6di 
```
