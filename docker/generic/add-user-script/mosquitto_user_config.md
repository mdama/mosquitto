# Adding User Without Restart the mosquitto docker container

## On host server, below command must be executed. 
```bash
/home/speedyweb/docker/mqtt-add-user.sh username="SAMPLE_USER_NAME" password="SAMPLE_PASSWORD" acl="SAMPLE_ACL_DEFINITION"
```
## Explanation of parameters

- **_username_:**  MQTT Username definition.
- **_password_:**  MQTT password of user.  
- **_acl_:** If `acl_file /acl` definition exist on mosquitto.conf, "acl" definition can be added by this parameter. For detail "acl" definitions http://www.steves-internet-guide.com/topic-restriction-mosquitto-configuration/
