# Gitea Runner
This role installs the Gitea ACT Runner on a system of your choosing, it requires the system to be configured with Podman and it will allow testing Ansible roles (among other things no doubt).

Note that this role might also work with Forgejo, but that has not been tested!

## Requirements

* Fully configured and functioning Podman installation on your server
* Fully functional Gitea instance (you need to get a registration token from it)

## Usage

1. Get a registration token from Gitea by going to https://gitea.example.nl/admin/actions/runners
2. Configure the role with at least the following:

```
gitea_runner_instance_url
gitea_runner_registration_token
```

3. Run the role
4. Presto!
