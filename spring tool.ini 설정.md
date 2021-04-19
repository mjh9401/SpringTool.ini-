spring tool.ini 설정

-startup

plugins/org.eclipse.equinox.launcher_1.5.500.v20190715-1310.jar

--launcher.library

plugins/org.eclipse.equinox.launcher.win32.win32.x86_64_1.1.1100.v20190907-0426

-product

org.springframework.boot.ide.branding.sts4

--launcher.defaultAction

openFile

-vmargs

-Dosgi.requiredJavaVersion=1.8

-Xms1024m

-Xmx2048m

-XX:+UseG1GC

-XX:+UseStringDeduplication

--add-modules=ALL-SYSTEM

-vm

C:\Program Files\Java\jdk-15.0.2\bin

-javaagent:C:\work\sts-4.4.0.RELEASE\lombok.jar
