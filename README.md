# LibreNMS
# --- WIP!!!! ---

## Dependencies
This role assumes that `podman` is installed, configured and running on the system where LibreNMS will be installed.

## Components
All additional services/components listed below will be installed by this role in `podman` containers.


### DB - MariaDB
Installed in `podman` container.
Perform the entire configuration by changing the parameters below.
The default values of these parameters are defined in `defaults/main.yaml`:
*  librenms.db_volume
*  librenms.db_config_volume
*  librenms.db_container_name
*  librenms.db_container_image
*  librenms.db_container_tag
*  librenms.db_root_password
*  librenms.db_password
*  librenms.db_name
*  librenms.db_user
*  librenms.db_systemd

See in the `defaults/main.yaml` file there are all variables with default values.
### Memcached

### Redis - key/value DB

### rrdtool with cache
