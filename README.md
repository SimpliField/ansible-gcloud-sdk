Gcloud sdk
=========

Setup gcloud sdk

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
gcloud_service_email: "email"
gcloud_project_id: "project ID"
gcloud_client_id: "client ID"
gcloud_private_key: "private key, on a single line using \n (e.g. '-----BEGIN PRIVATE KEY-----\nSDFSDSFD\nSDFFSDFD...'), found in JSON service key; use single quotes !"
gcloud_private_key_id: "private key id found in JSON service key"
```

Dependencies
------------

There is no dependencies

Example Playbook
----------------

```
- hosts: servers
  roles:
  - role: simplifield.gcloud-sdk
```

License
-------

BSD
