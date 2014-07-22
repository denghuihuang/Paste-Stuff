Paste-Stuff
===========

gemini web error information:

g! 2014-7-10 18:35:48 org.apache.catalina.core.AprLifecycleListener init
信息: The APR based Apache Tomcat Native library which allows optimal performan
e in production environments was not found on the java.library.path: C:\Windows
system32;.;C:\Windows\Sun\Java\bin;C:\Windows\system32;C:\Windows;C:\Windows\sy
tem32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell
v1.0\;C:\Program Files\SinoVoice\jTTS 5.0 Desktop\Bin;C:\Program Files\Citrix\S
stem32\;C:\Program Files\Citrix\ICAService\;C:\PROGRA~1\ULTRAE~1;C:\Program Fil
s\TortoiseGit\bin;C:\Python27;C:\Program Files\TortoiseSVN\bin;D:\soft\apache-m
ven-3.1.0\bin;D:\soft\apache-maven-3.1.0\bin
2014-7-10 18:35:49 org.apache.coyote.AbstractProtocol init
信息: Initializing ProtocolHandler ["http-bio-8080"]
2014-7-10 18:35:49 org.apache.catalina.mbeans.GlobalResourcesLifecycleListener
reateMBeans
严重: No global naming context defined for server
2014-7-10 18:35:49 org.apache.catalina.core.StandardService startInternal
信息: Starting service Catalina
2014-7-10 18:35:49 org.apache.catalina.core.StandardEngine startInternal
信息: Starting Servlet Engine: Apache Tomcat/7.0.53
2014-7-10 18:35:49 org.apache.coyote.AbstractProtocol start
信息: Starting ProtocolHandler ["http-bio-8080"]
GossipRouter started at Thu Jul 10 18:35:56 GMT+08:00 2014
Listening on port 12001 bound on address 0.0.0.0/0.0.0.0
Backlog is 1000, linger timeout is 2000, and read timeout is 0
2014-7-10 18:36:11 org.apache.catalina.startup.ContextConfig processServletCont
inerInitializers
严重: Failed to process JAR found at URL [/controller/nb/cluster] for ServletCo
tainerInitializers for context with name [{1}]
java.io.IOException: java.lang.ClassCastException
        at org.apache.catalina.startup.WebappServiceLoader.loadServices(WebappS
rviceLoader.java:196)
        at org.apache.catalina.startup.WebappServiceLoader.load(WebappServiceLo
der.java:152)
        at org.apache.catalina.startup.ContextConfig.processServletContainerIni
ializers(ContextConfig.java:1543)
        at org.apache.catalina.startup.ContextConfig.webConfig(ContextConfig.ja
a:1265)
        at org.apache.catalina.startup.ContextConfig.configureStart(ContextConf
g.java:873)
        at org.apache.catalina.startup.ContextConfig.lifecycleEvent(ContextConf
g.java:371)
        at org.apache.catalina.util.LifecycleSupport.fireLifecycleEvent(Lifecyc
eSupport.java:117)
        at org.apache.catalina.util.LifecycleBase.fireLifecycleEvent(LifecycleB
se.java:90)
        at org.apache.catalina.core.StandardContext.startInternal(StandardConte
t.java:5355)
        at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:150)
        at org.apache.catalina.core.ContainerBase.addChildInternal(ContainerBas
.java:901)
        at org.apache.catalina.core.ContainerBase.addChild(ContainerBase.java:8
7)
        at org.apache.catalina.core.StandardHost.addChild(StandardHost.java:632

        at org.eclipse.gemini.web.tomcat.internal.TomcatServletContainer.startW
bApplication(TomcatServletContainer.java:125)
        at org.eclipse.gemini.web.internal.StandardWebApplication.start(Standar
WebApplication.java:109)
        at org.eclipse.gemini.web.extender.WebContainerBundleCustomizer.addingB
ndle(WebContainerBundleCustomizer.java:49)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleT
acker.java:467)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleT
acker.java:414)
        at org.osgi.util.tracker.AbstractTracked.trackAdding(AbstractTracked.ja
a:256)
        at org.osgi.util.tracker.AbstractTracked.track(AbstractTracked.java:229

        at org.osgi.util.tracker.BundleTracker$Tracked.bundleChanged(BundleTrac
er.java:443)
        at org.apache.felix.framework.util.EventDispatcher.invokeBundleListener
allback(EventDispatcher.java:868)
        at org.apache.felix.framework.util.EventDispatcher.fireEventImmediately
EventDispatcher.java:789)
        at org.apache.felix.framework.util.EventDispatcher.fireBundleEvent(Even
Dispatcher.java:514)
        at org.apache.felix.framework.Felix.fireBundleEvent(Felix.java:4403)
        at org.apache.felix.framework.Felix.startBundle(Felix.java:2092)
        at org.apache.felix.framework.Felix.setActiveStartLevel(Felix.java:1291

        at org.apache.felix.framework.FrameworkStartLevelImpl.run(FrameworkStar
LevelImpl.java:304)
        at java.lang.Thread.run(Unknown Source)
Caused by: java.lang.ClassCastException
        at java.lang.Class.cast(Unknown Source)
        at org.apache.catalina.startup.WebappServiceLoader.loadServices(WebappS
rviceLoader.java:188)
        ... 28 more
2014-7-10 18:36:11 org.apache.catalina.startup.ContextConfig configureStart
严重: Marking this application unavailable due to previous error(s)
2014-7-10 18:36:11 org.apache.catalina.core.StandardContext startInternal
严重: Error getConfigured
2014-7-10 18:36:11 org.apache.catalina.core.StandardContext startInternal
严重: Context [/controller/nb/cluster] startup failed due to previous errors






































========================================================================================
D:\work\felix-framework-4.2.1>java -Dlogback.configurationFile=logback.xml -Dlog
4j.configuration=file:log4j.properties  -jar bin/felix.jar
Auto-properties start: file:thirdpart/dep/org.apache.catalina.ha-7.0.53.v2014060
70630.jar (org.osgi.framework.BundleException: Fragment bundles can not be start
ed.)
Auto-properties start: file:thirdpart/dep/org.apache.catalina.tribes-7.0.53.v201
406070630.jar (org.osgi.framework.BundleException: Fragment bundles can not be s
tarted.)
Auto-properties start: file:thirdpart/dep/org.apache.coyote-7.0.53.v201406070630
.jar (org.osgi.framework.BundleException: Fragment bundles can not be started.)
Auto-properties start: file:thirdpart/dep/org.apache.jasper-7.0.53.v201406070630
.jar (org.osgi.framework.BundleException: Fragment bundles can not be started.)
Auto-properties start: file:thirdpart/dep/org.apache.tomcat.util-7.0.53.v2014060
70630.jar (org.osgi.framework.BundleException: Fragment bundles can not be start
ed.)
Auto-properties start: file:thirdpart/dep/org.apache.tomcat.websocket-7.0.53.v20
1406070630.jar (org.osgi.framework.BundleException: Fragment bundles can not be
started.)
____________________________
Welcome to Apache Felix Gogo

g! 2014-7-11 16:34:39 org.apache.catalina.core.AprLifecycleListener init
信息: The APR based Apache Tomcat Native library which allows optimal performanc
e in production environments was not found on the java.library.path: C:\Windows\
system32;.;C:\Windows\Sun\Java\bin;C:\Windows\system32;C:\Windows;C:\Windows\sys
tem32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\
v1.0\;C:\Program Files\SinoVoice\jTTS 5.0 Desktop\Bin;C:\Program Files\Citrix\Sy
stem32\;C:\Program Files\Citrix\ICAService\;C:\PROGRA~1\ULTRAE~1;C:\Program File
s\TortoiseGit\bin;C:\Python27;C:\Program Files\TortoiseSVN\bin;D:\soft\apache-ma
ven-3.1.0\bin;D:\soft\apache-maven-3.1.0\bin
2014-7-11 16:34:39 org.apache.coyote.AbstractProtocol init
信息: Initializing ProtocolHandler ["http-bio-8080"]
2014-7-11 16:34:39 org.apache.catalina.mbeans.GlobalResourcesLifecycleListener c
reateMBeans
严重: No global naming context defined for server
2014-7-11 16:34:39 org.apache.catalina.core.StandardService startInternal
信息: Starting service Catalina
2014-7-11 16:34:39 org.apache.catalina.core.StandardEngine startInternal
信息: Starting Servlet Engine: Apache Tomcat/7.0.53
2014-7-11 16:34:39 org.apache.coyote.AbstractProtocol start
信息: Starting ProtocolHandler ["http-bio-8080"]
GossipRouter started at Fri Jul 11 16:34:42 GMT+08:00 2014
Listening on port 12001 bound on address 0.0.0.0/0.0.0.0
Backlog is 1000, linger timeout is 2000, and read timeout is 0
2014-7-11 16:34:54 org.glassfish.jersey.server.ApplicationHandler initialize
信息: Initiating Jersey application, version Jersey: 2.4 2013-10-24 18:25:49...
2014-7-11 16:34:55 org.apache.catalina.core.ContainerBase addChildInternal
严重: ContainerBase.addChild: start:
org.apache.catalina.LifecycleException: Failed to start component [StandardEngin
e[Catalina].StandardHost[localhost].StandardContext[/controller/nb/cluster]]
        at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:154)
        at org.apache.catalina.core.ContainerBase.addChildInternal(ContainerBase
.java:901)
        at org.apache.catalina.core.ContainerBase.addChild(ContainerBase.java:87
7)
        at org.apache.catalina.core.StandardHost.addChild(StandardHost.java:632)

        at org.eclipse.gemini.web.tomcat.internal.TomcatServletContainer.startWe
bApplication(TomcatServletContainer.java:125)
        at org.eclipse.gemini.web.internal.StandardWebApplication.start(Standard
WebApplication.java:109)
        at org.eclipse.gemini.web.extender.WebContainerBundleCustomizer.addingBu
ndle(WebContainerBundleCustomizer.java:49)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleTr
acker.java:467)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleTr
acker.java:414)
        at org.osgi.util.tracker.AbstractTracked.trackAdding(AbstractTracked.jav
a:256)
        at org.osgi.util.tracker.AbstractTracked.track(AbstractTracked.java:229)

        at org.osgi.util.tracker.BundleTracker$Tracked.bundleChanged(BundleTrack
er.java:443)
        at org.apache.felix.framework.util.EventDispatcher.invokeBundleListenerC
allback(EventDispatcher.java:868)
        at org.apache.felix.framework.util.EventDispatcher.fireEventImmediately(
EventDispatcher.java:789)
        at org.apache.felix.framework.util.EventDispatcher.fireBundleEvent(Event
Dispatcher.java:514)
        at org.apache.felix.framework.Felix.fireBundleEvent(Felix.java:4403)
        at org.apache.felix.framework.Felix.startBundle(Felix.java:2092)
        at org.apache.felix.framework.Felix.setActiveStartLevel(Felix.java:1291)

        at org.apache.felix.framework.FrameworkStartLevelImpl.run(FrameworkStart
LevelImpl.java:304)
        at java.lang.Thread.run(Unknown Source)
Caused by: java.lang.UnsupportedClassVersionError: javax/servlet/ServletContaine
rInitializer : Unsupported major.minor version 51.0
        at java.lang.ClassLoader.defineClass1(Native Method)
        at java.lang.ClassLoader.defineClassCond(Unknown Source)
        at java.lang.ClassLoader.defineClass(Unknown Source)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.findCla
ss(BundleWiringImpl.java:2279)
        at org.apache.felix.framework.BundleWiringImpl.findClassOrResourceByDele
gation(BundleWiringImpl.java:1501)
        at org.apache.felix.framework.BundleWiringImpl.access$400(BundleWiringIm
pl.java:75)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.loadCla
ss(BundleWiringImpl.java:1955)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at java.lang.ClassLoader.defineClass1(Native Method)
        at java.lang.ClassLoader.defineClassCond(Unknown Source)
        at java.lang.ClassLoader.defineClass(Unknown Source)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.findCla
ss(BundleWiringImpl.java:2279)
        at org.apache.felix.framework.BundleWiringImpl.findClassOrResourceByDele
gation(BundleWiringImpl.java:1501)
        at org.apache.felix.framework.BundleWiringImpl.access$400(BundleWiringIm
pl.java:75)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.loadCla
ss(BundleWiringImpl.java:1955)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at org.apache.felix.framework.BundleWiringImpl.getClassByDelegation(Bund
leWiringImpl.java:1374)
        at org.apache.felix.framework.BundleWiringImpl.searchImports(BundleWirin
gImpl.java:1553)
        at org.apache.felix.framework.BundleWiringImpl.findClassOrResourceByDele
gation(BundleWiringImpl.java:1484)
        at org.apache.felix.framework.BundleWiringImpl.access$400(BundleWiringIm
pl.java:75)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.loadCla
ss(BundleWiringImpl.java:1955)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at org.apache.felix.framework.Felix.loadBundleClass(Felix.java:1844)
        at org.apache.felix.framework.BundleImpl.loadClass(BundleImpl.java:937)
        at org.eclipse.gemini.web.tomcat.internal.loading.BundleDelegatingClassL
oader.findClass(BundleDelegatingClassLoader.java:91)
        at org.eclipse.gemini.web.tomcat.internal.loading.BundleDelegatingClassL
oader.loadClass(BundleDelegatingClassLoader.java:139)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at org.eclipse.gemini.web.tomcat.internal.loading.ChainedClassLoader.doL
oadClass(ChainedClassLoader.java:174)
        at org.eclipse.gemini.web.tomcat.internal.loading.ChainedClassLoader.loa
dClass(ChainedClassLoader.java:164)
        at org.eclipse.gemini.web.tomcat.internal.loading.BundleWebappClassLoade
r.loadClass(BundleWebappClassLoader.java:298)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at java.lang.Class.forName0(Native Method)
        at java.lang.Class.forName(Unknown Source)
        at org.apache.catalina.startup.WebappServiceLoader.loadServices(WebappSe
rviceLoader.java:187)
        at org.apache.catalina.startup.WebappServiceLoader.load(WebappServiceLoa
der.java:152)
        at org.apache.catalina.startup.ContextConfig.processServletContainerInit
ializers(ContextConfig.java:1543)
        at org.apache.catalina.startup.ContextConfig.webConfig(ContextConfig.jav
a:1265)
        at org.apache.catalina.startup.ContextConfig.configureStart(ContextConfi
g.java:873)
        at org.apache.catalina.startup.ContextConfig.lifecycleEvent(ContextConfi
g.java:371)
        at org.apache.catalina.util.LifecycleSupport.fireLifecycleEvent(Lifecycl
eSupport.java:117)
        at org.apache.catalina.util.LifecycleBase.fireLifecycleEvent(LifecycleBa
se.java:90)
        at org.apache.catalina.core.StandardContext.startInternal(StandardContex
t.java:5355)
        at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:150)
        ... 19 more

g! lb



















===================================================================================




D:\work\felix-framework-4.2.1>java -Dlogback.configurationFile=logback.xml -Dlog
4j.configuration=file:log4j.properties -jar bin/felix.jar
Auto-properties start: file:thirdpart/dep/org.apache.catalina.ha-7.0.53.v2014060
70630.jar (org.osgi.framework.BundleException: Fragment bundles can not be start
ed.)
Auto-properties start: file:thirdpart/dep/org.apache.catalina.tribes-7.0.53.v201
406070630.jar (org.osgi.framework.BundleException: Fragment bundles can not be s
tarted.)
Auto-properties start: file:thirdpart/dep/org.apache.coyote-7.0.53.v201406070630
.jar (org.osgi.framework.BundleException: Fragment bundles can not be started.)
Auto-properties start: file:thirdpart/dep/org.apache.jasper-7.0.53.v201406070630
.jar (org.osgi.framework.BundleException: Fragment bundles can not be started.)
Auto-properties start: file:thirdpart/dep/org.apache.tomcat.util-7.0.53.v2014060
70630.jar (org.osgi.framework.BundleException: Fragment bundles can not be start
ed.)
Auto-properties start: file:thirdpart/dep/org.apache.tomcat.websocket-7.0.53.v20
1406070630.jar (org.osgi.framework.BundleException: Fragment bundles can not be
started.)
____________________________
Welcome to Apache Felix Gogo

g! 七月 14, 2014 5:24:48 下午 org.apache.catalina.core.AprLifecycleListener init

INFO: The APR based Apache Tomcat Native library which allows optimal performanc
e in production environments was not found on the java.library.path: C:\Windows\
system32;C:\Windows\Sun\Java\bin;C:\Windows\system32;C:\Windows;C:\Windows\syste
m32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1
.0\;C:\Program Files\SinoVoice\jTTS 5.0 Desktop\Bin;C:\Program Files\Citrix\Syst
em32\;C:\Program Files\Citrix\ICAService\;C:\PROGRA~1\ULTRAE~1;C:\Program Files\
TortoiseGit\bin;C:\Python27;C:\Program Files\TortoiseSVN\bin;D:\soft\apache-mave
n-3.1.0\bin;D:\soft\apache-maven-3.1.0\bin;.
七月 14, 2014 5:24:48 下午 org.apache.coyote.AbstractProtocol init
INFO: Initializing ProtocolHandler ["http-bio-8080"]
七月 14, 2014 5:24:48 下午 org.apache.catalina.mbeans.GlobalResourcesLifecycleLi
stener createMBeans
SEVERE: No global naming context defined for server
七月 14, 2014 5:24:48 下午 org.apache.catalina.core.StandardService startInterna
l
INFO: Starting service Catalina
七月 14, 2014 5:24:48 下午 org.apache.catalina.core.StandardEngine startInternal

INFO: Starting Servlet Engine: Apache Tomcat/7.0.53
七月 14, 2014 5:24:48 下午 org.apache.coyote.AbstractProtocol start
INFO: Starting ProtocolHandler ["http-bio-8080"]
GossipRouter started at Mon Jul 14 17:24:51 GMT+08:00 2014
Listening on port 12001 bound on address 0.0.0.0/0.0.0.0
Backlog is 1000, linger timeout is 2000, and read timeout is 0
七月 14, 2014 5:25:04 下午 org.glassfish.jersey.server.ApplicationHandler initia
lize
INFO: Initiating Jersey application, version Jersey: 2.4 2013-10-24 18:25:49...
七月 14, 2014 5:25:04 下午 org.apache.catalina.startup.ContextConfig processServ
letContainerInitializers
SEVERE: Failed to process JAR found at URL [/controller/nb/cluster] for ServletC
ontainerInitializers for context with name [{1}]
java.io.IOException: java.lang.ClassCastException: Cannot cast com.huawei.sdnc.n
orthbound.customservletcontainerinit.BundleServletContainerInitializer to javax.
servlet.ServletContainerInitializer
        at org.apache.catalina.startup.WebappServiceLoader.loadServices(WebappSe
rviceLoader.java:196)
        at org.apache.catalina.startup.WebappServiceLoader.load(WebappServiceLoa
der.java:152)
        at org.apache.catalina.startup.ContextConfig.processServletContainerInit
ializers(ContextConfig.java:1543)
        at org.apache.catalina.startup.ContextConfig.webConfig(ContextConfig.jav
a:1265)
        at org.apache.catalina.startup.ContextConfig.configureStart(ContextConfi
g.java:873)
        at org.apache.catalina.startup.ContextConfig.lifecycleEvent(ContextConfi
g.java:371)
        at org.apache.catalina.util.LifecycleSupport.fireLifecycleEvent(Lifecycl
eSupport.java:117)
        at org.apache.catalina.util.LifecycleBase.fireLifecycleEvent(LifecycleBa
se.java:90)
        at org.apache.catalina.core.StandardContext.startInternal(StandardContex
t.java:5355)
        at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:150)
        at org.apache.catalina.core.ContainerBase.addChildInternal(ContainerBase
.java:901)
        at org.apache.catalina.core.ContainerBase.addChild(ContainerBase.java:87
7)
        at org.apache.catalina.core.StandardHost.addChild(StandardHost.java:632)

        at org.eclipse.gemini.web.tomcat.internal.TomcatServletContainer.startWe
bApplication(TomcatServletContainer.java:125)
        at org.eclipse.gemini.web.internal.StandardWebApplication.start(Standard
WebApplication.java:109)
        at org.eclipse.gemini.web.extender.WebContainerBundleCustomizer.addingBu
ndle(WebContainerBundleCustomizer.java:49)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleTr
acker.java:467)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleTr
acker.java:414)
        at org.osgi.util.tracker.AbstractTracked.trackAdding(AbstractTracked.jav
a:256)
        at org.osgi.util.tracker.AbstractTracked.track(AbstractTracked.java:229)

        at org.osgi.util.tracker.BundleTracker$Tracked.bundleChanged(BundleTrack
er.java:443)
        at org.apache.felix.framework.util.EventDispatcher.invokeBundleListenerC
allback(EventDispatcher.java:868)
        at org.apache.felix.framework.util.EventDispatcher.fireEventImmediately(
EventDispatcher.java:789)
        at org.apache.felix.framework.util.EventDispatcher.fireBundleEvent(Event
Dispatcher.java:514)
        at org.apache.felix.framework.Felix.fireBundleEvent(Felix.java:4403)
        at org.apache.felix.framework.Felix.startBundle(Felix.java:2092)
        at org.apache.felix.framework.Felix.setActiveStartLevel(Felix.java:1291)

        at org.apache.felix.framework.FrameworkStartLevelImpl.run(FrameworkStart
LevelImpl.java:304)
        at java.lang.Thread.run(Unknown Source)
Caused by: java.lang.ClassCastException: Cannot cast com.huawei.sdnc.northbound.
customservletcontainerinit.BundleServletContainerInitializer to javax.servlet.Se
rvletContainerInitializer
        at java.lang.Class.cast(Unknown Source)
        at org.apache.catalina.startup.WebappServiceLoader.loadServices(WebappSe
rviceLoader.java:188)
        ... 28 more

七月 14, 2014 5:25:04 下午 org.apache.catalina.startup.ContextConfig configureSt
art
SEVERE: Marking this application unavailable due to previous error(s)
七月 14, 2014 5:25:04 下午 org.apache.catalina.core.StandardContext startInterna
l
SEVERE: Error getConfigured
七月 14, 2014 5:25:04 下午 org.apache.catalina.core.StandardContext startInterna
l
SEVERE: Context [/controller/nb/cluster] startup failed due to previous errors



====================================================================================



D:\work\felix-framework-4.2.1-b>java -Dlogback.configurationFile=logback.xml -Dl
og4j.configuration=file:log4j.properties -jar bin/felix.jar
____________________________
Welcome to Apache Felix Gogo

g! 七月 22, 2014 3:35:37 下午 org.apache.catalina.core.AprLifecycleListener init

INFO: The APR based Apache Tomcat Native library which allows optimal performanc
e in production environments was not found on the java.library.path: C:\Windows\
system32;C:\Windows\Sun\Java\bin;C:\Windows\system32;C:\Windows;C:\Program Files
\Common Files\NetSarang;C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;
C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Program Files\SinoVoice\jTTS 5.0
Desktop\Bin;C:\Program Files\Citrix\System32\;C:\Program Files\Citrix\ICAService
\;C:\PROGRA~1\ULTRAE~1;C:\Program Files\TortoiseGit\bin;C:\Python27;C:\Program F
iles\TortoiseSVN\bin;D:\soft\apache-maven-3.1.0\bin;D:\soft\apache-maven-3.1.0\b
in;.
七月 22, 2014 3:35:38 下午 org.apache.coyote.AbstractProtocol init
INFO: Initializing ProtocolHandler ["http-bio-8080"]
七月 22, 2014 3:35:38 下午 org.apache.catalina.mbeans.GlobalResourcesLifecycleLi
stener createMBeans
SEVERE: No global naming context defined for server
七月 22, 2014 3:35:38 下午 org.apache.catalina.core.StandardService startInterna
l
INFO: Starting service Catalina
七月 22, 2014 3:35:38 下午 org.apache.catalina.core.StandardEngine startInternal

INFO: Starting Servlet Engine: Apache Tomcat/7.0.53
七月 22, 2014 3:35:38 下午 org.apache.coyote.AbstractProtocol start
INFO: Starting ProtocolHandler ["http-bio-8080"]
七月 22, 2014 3:35:41 下午 org.apache.catalina.core.ApplicationContext log
INFO: Marking servlet JAXRSCluster as unavailable
七月 22, 2014 3:35:41 下午 org.apache.catalina.core.StandardContext loadOnStartu
p
SEVERE: Servlet /controller/nb/cluster threw load() exception
java.lang.ClassNotFoundException: javax.servlet.Filter not found by cluster.nort
hbound [41]
        at org.apache.felix.framework.BundleWiringImpl.findClassOrResourceByDele
gation(BundleWiringImpl.java:1532)
        at org.apache.felix.framework.BundleWiringImpl.access$400(BundleWiringIm
pl.java:75)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.loadCla
ss(BundleWiringImpl.java:1955)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at java.lang.ClassLoader.defineClass1(Native Method)
        at java.lang.ClassLoader.defineClass(Unknown Source)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.findCla
ss(BundleWiringImpl.java:2279)
        at org.apache.felix.framework.BundleWiringImpl.findClassOrResourceByDele
gation(BundleWiringImpl.java:1501)
        at org.apache.felix.framework.BundleWiringImpl.access$400(BundleWiringIm
pl.java:75)
        at org.apache.felix.framework.BundleWiringImpl$BundleClassLoader.loadCla
ss(BundleWiringImpl.java:1955)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at org.apache.felix.framework.Felix.loadBundleClass(Felix.java:1844)
        at org.apache.felix.framework.BundleImpl.loadClass(BundleImpl.java:937)
        at org.eclipse.gemini.web.tomcat.internal.loading.BundleDelegatingClassL
oader.findClass(BundleDelegatingClassLoader.java:91)
        at org.eclipse.gemini.web.tomcat.internal.loading.BundleDelegatingClassL
oader.loadClass(BundleDelegatingClassLoader.java:139)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at org.eclipse.gemini.web.tomcat.internal.loading.ChainedClassLoader.doL
oadClass(ChainedClassLoader.java:174)
        at org.eclipse.gemini.web.tomcat.internal.loading.ChainedClassLoader.loa
dClass(ChainedClassLoader.java:164)
        at org.eclipse.gemini.web.tomcat.internal.loading.BundleWebappClassLoade
r.loadClass(BundleWebappClassLoader.java:298)
        at java.lang.ClassLoader.loadClass(Unknown Source)
        at org.apache.catalina.core.DefaultInstanceManager.loadClass(DefaultInst
anceManager.java:529)
        at org.apache.catalina.core.DefaultInstanceManager.loadClassMaybePrivile
ged(DefaultInstanceManager.java:511)
        at org.apache.catalina.core.DefaultInstanceManager.newInstance(DefaultIn
stanceManager.java:139)
        at org.apache.catalina.core.StandardWrapper.loadServlet(StandardWrapper.
java:1148)
        at org.apache.catalina.core.StandardWrapper.load(StandardWrapper.java:10
87)
        at org.apache.catalina.core.StandardContext.loadOnStartup(StandardContex
t.java:5210)
        at org.apache.catalina.core.StandardContext.startInternal(StandardContex
t.java:5493)
        at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:150)
        at org.apache.catalina.core.ContainerBase.addChildInternal(ContainerBase
.java:901)
        at org.apache.catalina.core.ContainerBase.addChild(ContainerBase.java:87
7)
        at org.apache.catalina.core.StandardHost.addChild(StandardHost.java:632)

        at org.eclipse.gemini.web.tomcat.internal.TomcatServletContainer.startWe
bApplication(TomcatServletContainer.java:125)
        at org.eclipse.gemini.web.internal.StandardWebApplication.start(Standard
WebApplication.java:109)
        at org.eclipse.gemini.web.extender.WebContainerBundleCustomizer.addingBu
ndle(WebContainerBundleCustomizer.java:49)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleTr
acker.java:467)
        at org.osgi.util.tracker.BundleTracker$Tracked.customizerAdding(BundleTr
acker.java:414)
        at org.osgi.util.tracker.AbstractTracked.trackAdding(AbstractTracked.jav
a:256)
        at org.osgi.util.tracker.AbstractTracked.track(AbstractTracked.java:229)

        at org.osgi.util.tracker.BundleTracker$Tracked.bundleChanged(BundleTrack
er.java:443)
        at org.apache.felix.framework.util.EventDispatcher.invokeBundleListenerC
allback(EventDispatcher.java:868)
        at org.apache.felix.framework.util.EventDispatcher.fireEventImmediately(
EventDispatcher.java:789)
        at org.apache.felix.framework.util.EventDispatcher.fireBundleEvent(Event
Dispatcher.java:514)
        at org.apache.felix.framework.Felix.fireBundleEvent(Felix.java:4403)
        at org.apache.felix.framework.Felix.startBundle(Felix.java:2092)
        at org.apache.felix.framework.Felix.setActiveStartLevel(Felix.java:1291)

        at org.apache.felix.framework.FrameworkStartLevelImpl.run(FrameworkStart
LevelImpl.java:304)
        at java.lang.Thread.run(Unknown Source)

