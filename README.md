# config-retry
Spring boot with spring cloud config sample illustrating possible spring cloud config bug

The bug is reported as https://github.com/spring-cloud/spring-cloud-config/issues/1797

This branch contains updated code that uses spring-cloud 2020.0.3 and
spring-boot 2.4.5 along with changes to the spring.config.import
property. All of those changes fixes the issue reported above.
