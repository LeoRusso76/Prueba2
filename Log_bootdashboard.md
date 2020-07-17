OpenJDK 64-Bit Server VM warning: Options -Xverify:none and -noverify were deprecated in JDK 13 and will likely be removed in a future release.
2020-07-17 18:33:34.904  INFO 16476 --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.3.1.RELEASE)

2020-07-17 18:33:35.363  INFO 16476 --- [  restartedMain] .m.a.u.MicroserviciosUsuariosApplication : No active profile set, falling back to default profiles: default
2020-07-17 18:33:35.393 DEBUG 16476 --- [  restartedMain] o.s.c.a.ClassPathBeanDefinitionScanner   : Identified candidate component class: file [C:\Cursos\Herramientas\Workspaces\microservicios-usuarios\target\classes\com\formacionbdi\microservicios\app\usuarios\controllers\AlumnoController.class]
2020-07-17 18:33:35.397 DEBUG 16476 --- [  restartedMain] o.s.c.a.ClassPathBeanDefinitionScanner   : Identified candidate component class: file [C:\Cursos\Herramientas\Workspaces\microservicios-usuarios\target\classes\com\formacionbdi\microservicios\app\usuarios\services\AlumnoServiceImpl.class]
2020-07-17 18:33:35.943  INFO 16476 --- [  restartedMain] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFERRED mode.
2020-07-17 18:33:35.988 DEBUG 16476 --- [  restartedMain] ssPathScanningCandidateComponentProvider : Identified candidate component class: file [C:\Cursos\Herramientas\Workspaces\microservicios-usuarios\target\classes\com\formacionbdi\microservicios\app\usuarios\services\AlumnoServiceImpl.class]
2020-07-17 18:33:35.995  INFO 16476 --- [  restartedMain] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 47ms. Found 1 JPA repository interfaces.
2020-07-17 18:33:36.196  INFO 16476 --- [  restartedMain] o.s.cloud.context.scope.GenericScope     : BeanFactory id=0f53d962-ca94-313c-a85c-9939296e7128
2020-07-17 18:33:36.621  INFO 16476 --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 0 (http)
2020-07-17 18:33:36.628  INFO 16476 --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2020-07-17 18:33:36.628  INFO 16476 --- [  restartedMain] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.36]
2020-07-17 18:33:36.737  INFO 16476 --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2020-07-17 18:33:36.738  INFO 16476 --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1363 ms
2020-07-17 18:33:36.848  INFO 16476 --- [  restartedMain] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2020-07-17 18:33:36.856  INFO 16476 --- [  restartedMain] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2020-07-17 18:33:36.869  WARN 16476 --- [  restartedMain] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean]: Factory method 'entityManagerFactory' threw exception; nested exception is java.lang.RuntimeException: Driver com.mysql.cj.jdbc.Driver claims to not accept jdbcUrl, jdbc:mysql//localhost:3306/db_microservicios_examenes
2020-07-17 18:33:36.869  INFO 16476 --- [  restartedMain] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
2020-07-17 18:33:36.871  INFO 16476 --- [  restartedMain] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2020-07-17 18:33:36.883  INFO 16476 --- [  restartedMain] ConditionEvaluationReportLoggingListener : 

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2020-07-17 18:33:36.883 DEBUG 16476 --- [  restartedMain] s.c.a.AnnotationConfigApplicationContext : Closing org.springframework.context.annotation.AnnotationConfigApplicationContext@15f8a18, started on Fri Jul 17 18:33:34 UYT 2020
2020-07-17 18:33:36.893 ERROR 16476 --- [  restartedMain] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean]: Factory method 'entityManagerFactory' threw exception; nested exception is java.lang.RuntimeException: Driver com.mysql.cj.jdbc.Driver claims to not accept jdbcUrl, jdbc:mysql//localhost:3306/db_microservicios_examenes
	at org.springframework.beans.factory.support.ConstructorResolver.instantiate(ConstructorResolver.java:655) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.ConstructorResolver.instantiateUsingFactoryMethod(ConstructorResolver.java:635) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.instantiateUsingFactoryMethod(AbstractAutowireCapableBeanFactory.java:1338) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1177) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:557) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:226) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.getBean(AbstractApplicationContext.java:1109) ~[spring-context-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:869) ~[spring-context-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:551) ~[spring-context-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:143) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:758) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:750) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:397) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:315) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1237) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1226) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at com.formacionbdi.microservicios.app.usuarios.MicroserviciosUsuariosApplication.main(MicroserviciosUsuariosApplication.java:12) ~[classes/:na]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[na:na]
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
	at java.base/java.lang.reflect.Method.invoke(Method.java:567) ~[na:na]
	at org.springframework.boot.devtools.restart.RestartLauncher.run(RestartLauncher.java:49) ~[spring-boot-devtools-2.3.1.RELEASE.jar:2.3.1.RELEASE]
Caused by: org.springframework.beans.BeanInstantiationException: Failed to instantiate [org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean]: Factory method 'entityManagerFactory' threw exception; nested exception is java.lang.RuntimeException: Driver com.mysql.cj.jdbc.Driver claims to not accept jdbcUrl, jdbc:mysql//localhost:3306/db_microservicios_examenes
	at org.springframework.beans.factory.support.SimpleInstantiationStrategy.instantiate(SimpleInstantiationStrategy.java:185) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.beans.factory.support.ConstructorResolver.instantiate(ConstructorResolver.java:650) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	... 25 common frames omitted
Caused by: java.lang.RuntimeException: Driver com.mysql.cj.jdbc.Driver claims to not accept jdbcUrl, jdbc:mysql//localhost:3306/db_microservicios_examenes
	at com.zaxxer.hikari.util.DriverDataSource.<init>(DriverDataSource.java:110) ~[HikariCP-3.4.5.jar:na]
	at com.zaxxer.hikari.pool.PoolBase.initializeDataSource(PoolBase.java:325) ~[HikariCP-3.4.5.jar:na]
	at com.zaxxer.hikari.pool.PoolBase.<init>(PoolBase.java:114) ~[HikariCP-3.4.5.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.<init>(HikariPool.java:108) ~[HikariCP-3.4.5.jar:na]
	at com.zaxxer.hikari.HikariDataSource.getConnection(HikariDataSource.java:112) ~[HikariCP-3.4.5.jar:na]
	at org.springframework.jdbc.datasource.DataSourceUtils.fetchConnection(DataSourceUtils.java:158) ~[spring-jdbc-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.jdbc.datasource.DataSourceUtils.doGetConnection(DataSourceUtils.java:116) ~[spring-jdbc-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.jdbc.datasource.DataSourceUtils.getConnection(DataSourceUtils.java:79) ~[spring-jdbc-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.jdbc.core.JdbcTemplate.execute(JdbcTemplate.java:324) ~[spring-jdbc-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	at org.springframework.boot.jdbc.EmbeddedDatabaseConnection.isEmbedded(EmbeddedDatabaseConnection.java:120) ~[spring-boot-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateDefaultDdlAutoProvider.getDefaultDdlAuto(HibernateDefaultDdlAutoProvider.java:42) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaConfiguration.lambda$getVendorProperties$1(HibernateJpaConfiguration.java:130) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateSettings.getDdlAuto(HibernateSettings.java:41) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateProperties.determineDdlAuto(HibernateProperties.java:136) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateProperties.getAdditionalProperties(HibernateProperties.java:102) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateProperties.determineHibernateProperties(HibernateProperties.java:94) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaConfiguration.getVendorProperties(HibernateJpaConfiguration.java:132) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at org.springframework.boot.autoconfigure.orm.jpa.JpaBaseConfiguration.entityManagerFactory(JpaBaseConfiguration.java:133) ~[spring-boot-autoconfigure-2.3.1.RELEASE.jar:2.3.1.RELEASE]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[na:na]
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
	at java.base/java.lang.reflect.Method.invoke(Method.java:567) ~[na:na]
	at org.springframework.beans.factory.support.SimpleInstantiationStrategy.instantiate(SimpleInstantiationStrategy.java:154) ~[spring-beans-5.2.7.RELEASE.jar:5.2.7.RELEASE]
	... 26 common frames omitted
