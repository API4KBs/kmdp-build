# kmdp-build

Package repository. 

Uses GitHub Actions to run a full build of all the develop branches of the KMDP implementation
(see the script here for local builds https://github.com/API4KBs/API4KBs.github.io/blob/master/scripts/build-develop.sh)

Contrast to https://github.com/API4KBs/api4kp-dist, which builds the OMG platform-independent models (UML, OWL, OpenAPI, XSD) 


To access the build Artifacts (poms, jars, wars, plugins) via Maven, add the following URL as a Repository: 
https://maven.pkg.github.com/API4KBs/kmdp-build

For example:
<repository>
 <id>github</id>
 <name>kmdp-dist-github</name>
 <url>https://maven.pkg.github.com/API4KBs/kmdp-build</url>
</repository>
