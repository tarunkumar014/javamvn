first download jdk 1.8,maven and place in /opt as JAVA=/opt/java , MAVEN=/opt/mvn

and set path below directly to /etc/profile.d/javamvn


JAVA_HOME=/opt/java
JRE_HOME=/opt/java/jre
MAVEN_HOME=/opt/maven
M2_HOME=/opt/maven
PATH=$PATH:$HOME/bin:$JAVA_HOME/bin:$JRE_HOME/bin:$MAVEN_HOME/bin
export JAVA_HOME
export JRE_HOME
export MAVEN_HOME
export M2_HOME
export PATH



cd /usr/share/applications


vim sts.desktop

[Desktop Entry]
Name=SpringSource Tool Suite
Comment=SpringSource Tool Suite
Exec=/opt/sts/sts-3.9.11.RELEASE/STS
Icon=/opt/sts/sts-3.9.11.RELEASE/icon.xpm
StartupNotify=true
Terminal=false
Type=Application
Categories=Development;IDE;Java;


cd /usr/share/applications

vim mongo.desktop	



[Desktop Entry]
Name=MongoChef
Comment=MongoChef For mongodb Viualization
Type=Application
Encoding=UTF-8
Exec=/opt/mongo/bin/mongochef.sh
Icon=/opt/mongo/bin/download.jpeg
Categories=GNOME;Application;Development;
Terminal=false
StartupNotify=true

