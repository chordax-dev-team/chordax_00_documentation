## chordax_registration

# setting swagger

1.add dependency in o.xml file:
<br/>
<img src="./img_for_readme/swagger_config_depemdency.PNG"/>
<br/>
<br/>
2.create configuration class in main package:
<br/>
<img src="./img_for_readme/swagger_config_class_location.PNG"/>
<br/>
<img src="./img_for_readme/swagger_config_class_code.PNG"/>
<br/>
<br/>
3.to add descriptions to api documentation, annotations with description should be added in model:
<br/>
<img src="./img_for_readme/swagger_config_annotations.PNG"/>
<br/>
<br/>
4.toview the swagger console with api documentation, in application.properties file swagger console's url should be mapped to its index.html file:
<br/>
<img src="./img_for_readme/swagger_config_application_properties.PNG"/>
<br/>
<img src="./img_for_readme/swagger_config_console_url_mapping.PNG"/>
<br/>
<br/>
5.the swagger console can be viewed in a browser under url [server-address:port]/[swagger-ui], like:
<br/>
<img src="./img_for_readme/swagger_config_swagger_ui.PNG" width="1000" />
<br/>
- the description from poin3, can be seen under "Schemas" option:
<br/>
<img src="./img_for_readme/swagger_config_schemas.PNG" width="1000" />

