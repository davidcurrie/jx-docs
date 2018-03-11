---
date: 2018-03-11T19:53:09Z
title: "jx get applications"
slug: jx_get_applications
url: /commands/jx_get_applications/
---
## jx get applications

Display one or many Applications and their versions

### Synopsis


Display applications across environments.

```
jx get applications
```

### Examples

```
  # List applications for all environments
  jx get apps
  
  # List applications and their URLs for all environments
  jx get apps -u
```

### Options

```
  -u, --url   Show the URLs rather than pod numbers
```

### SEE ALSO
* [jx get](/commands/jx_get/)	 - Display one or many resources

###### Auto generated by spf13/cobra on 11-Mar-2018