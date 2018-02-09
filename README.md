logback-20180209
===

```
Exception in thread "main" java.util.ServiceConfigurationError: ch.qos.logback.classic.spi.Configurator: module ch.qos.logback.classic does not declare `uses`
	at java.base/java.util.ServiceLoader.fail(ServiceLoader.java:588)
	at java.base/java.util.ServiceLoader.checkCaller(ServiceLoader.java:574)
	at java.base/java.util.ServiceLoader.<init>(ServiceLoader.java:503)
	at java.base/java.util.ServiceLoader.load(ServiceLoader.java:1639)
	at ch.qos.logback.classic/ch.qos.logback.classic.util.EnvUtil.loadFromServiceLoader(EnvUtil.java:48)
	at ch.qos.logback.classic/ch.qos.logback.classic.util.ContextInitializer.autoConfig(ContextInitializer.java:155)
	at ch.qos.logback.classic/ch.qos.logback.classic.spi.LogbackServiceProvider.initializeLoggerContext(LogbackServiceProvider.java:49)
	at ch.qos.logback.classic/ch.qos.logback.classic.spi.LogbackServiceProvider.initialize(LogbackServiceProvider.java:40)
	at org.slf4j/org.slf4j.LoggerFactory.bind(LoggerFactory.java:153)
	at org.slf4j/org.slf4j.LoggerFactory.performInitialization(LoggerFactory.java:141)
	at org.slf4j/org.slf4j.LoggerFactory.getProvider(LoggerFactory.java:419)
	at org.slf4j/org.slf4j.LoggerFactory.getILoggerFactory(LoggerFactory.java:405)
	at org.slf4j/org.slf4j.LoggerFactory.getLogger(LoggerFactory.java:354)
	at org.slf4j/org.slf4j.LoggerFactory.getLogger(LoggerFactory.java:380)
	at com.io7m.bugs.logback/com.io7m.bugs.logback.Main.<clinit>(Main.java:8)
```
