# Use the previously created aem-base-image
FROM gcr.io/phoenix-cit/aem-base-image-65

# Expose AEM author in port 4503
EXPOSE 4503

# Make the container start always in Author mode with Port 4502
ENTRYPOINT ["java", "-Xms2g", "-Xmx4g", "-jar", "cq-quickstart.jar", "-Djava.awt.headless=true", "-Dsling.run.modes=publish", "-p", "4503"]
