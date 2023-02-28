# Spring Cloud Config
The library relies on three parameters to identify which property file to use to configure the specific application:
1. {application}, the name of the application as defined in `spring.application.name` property
2. {profile}, one of the active profiles defined by the `spring.profiles.active` property
3. {label}, discriminator defined by the specific configuration data repository