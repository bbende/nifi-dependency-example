# nifi-dependency-example
Demonstrates how to link a processor bundle with a custom controller service.

### Dependency Chain for Services (NAR dependencies)
nifi-example-service-nar -> nifi-example-service-api-nar -> nifi-standard-services-api-nar

### Dependency Chain for Processors (NAR dependencies)
nifi-example-processors-nar -> nifi-example-service-api-nar

## Build
    mvn clean package
    ./deploy.sh $NIFI_HOME
