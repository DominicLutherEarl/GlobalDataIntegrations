# GlobalDataIntegrations
A list of global OpenAPI\RAML specs files from different Saas (Cloud &amp; On-prem) services with last -2 versions. Also contains (in-progress) standard schema mappings to different data domains such as IAM, Finance, Regulatory, Legal, Medical, Content Creation, ECommerce, Mobility, Weather &amp; Maritime, etc

1. Create a list of global OpenAPI\RAML specs of as many Saas vendors as possible (with extensibility to add more)..
2. Generate default mappings for several of these specs to different standard schemas such as IAM (SCIM), Finance, Regulatory, Legal, Medical, Content Creation, ECommerce, Mobility, Weather &amp; Maritime, etc.
3. Allow different integrators (Kafka Connectors) to read from this data store for faster integrations.
4. Enable Agents to manage the data store by:
   a. Listening to the source of different specs on a scheduled timestamp daily.
   b. Maintain the specs by cleaning up un-used files.
   c. Trigger notifications to a subscription channel for different changes to files\integrations.
   d. Add gate keeping as a plug-in.


The format can be OpenAPI 2.0\3.0 or a RAML spec. The goal is to have the data to perform protocol-independant integration.
