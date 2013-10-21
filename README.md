# Incubus Email

An email templating and delivery application designed to allow minimal fuss for setting up application notification emails. Has flexible storage mechanisms, so it can be customised to be backed by most databases.

## Modules

* core: Contains all the services and logic to wire everything together.
* persist: A service-friendly interface for accessing the stored email templates.
* ebean: The default ebean implementation of the persistence services.
* rest: Service endpoints exposed using Syllabus.
* jms: Service methods exposed over JMS.
* war: Bundles the whole stack together in a runnable war file.