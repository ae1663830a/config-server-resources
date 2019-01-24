# RESOURCES FOR SPRING CLOUD CONFIG SERVER

### Configuration files naming convention

  * `application.yaml` - common configuration file (all applications, all profiles)
  * `application-prod.yaml` - common configuration file, profile specific (all applications, `prod` active profile)
  * `eureka-server.yaml` - application specific configuration file (`eureka-server` application, all profiles)
  * `eureka-server-dev.yaml` - application and profile specific (`eureka-server` application and `dev` active profile)
  
**IMPORTANT:** Can be uses both `yaml` and `properties` files:  
  * `application.properties`
  * `application.yaml`  

**IMPORTANT:** Each application must have configured application name in `spring.application.name` property to use application specific configuration files.
