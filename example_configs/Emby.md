# Configuration for Emby
##  Settings > Plugins > LDAP

(note you must install the LDAP plugin from the Catelog & reboot Emby first)

---

### LDAP server address
```
localhost
```
Replace `localhost` with your LLDAP host

### Host Base DN
```
cn=%s,ou=people,dc=example,dc=com
```
### LDAP server Port number:
```
3890
```
Replace `3890` with your LLDAP port

### Bind DN
```
uid=admin,ou=people,dc=example,dc=com
```
### Bind credentials
```
Your password from your LDAP config
```
### User search base
```
ou=people,dc=example,dc=com
```
### User search filter
```
(uid={0})
```

Replace `dc=example,dc=com` with your LLDAP configured domain for all occurances
