# Cloud

**Ansible playbooks for cloud.iad.zhdk.ch.h**

## Stack

- [dokku](http://dokku.viewdocs.io/dokku/)
- [dokku-mongo](https://github.com/dokku/dokku-mongo)
- [dokku-redis](https://github.com/dokku/dokku-redis)

## Secrets

Secrets are stored in the `secrets.yml` file in the root of the repository.

```yml
wiki_user: user
wiki_password: password
wiki_base: http://whatever.atlassian.net/
lab_smtp_user: user
lab_smtp_password: password
lab_admin_password: password
lab_terminal_password: password
```
