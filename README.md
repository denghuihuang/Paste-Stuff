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

