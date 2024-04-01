watchtower
==========

Installs watchtower as a docker container.


Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):


```
watchtower_image: containrrr/watchtower:latest
```
The version of the watchtower image to run as a container.

```
watchtower_host_config_path: /etc/watchtower
```
Host path where the watchtower configuration will be stored.

```
watchtower_container_user: watchtower
```
user who will run the container

```
watchtower_notification_url: telegram://TOKEN@telegram?chats=CHAT-ID
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - iasensio.watchtower

License
-------

MIT

