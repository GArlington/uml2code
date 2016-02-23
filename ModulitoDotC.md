#what is modulito.c

# Introduction #

Modulito.c is a file that should be able to do the basic work between the code and the xml definition.


# Details #

Modulito.c should have this methods and vars:
```

int major_version, minor_version;``````

struct info {``````

lang_name;``````

ext;``````

}``````

``````

void reset()``````

int ref_uml( char *path )``````

int include_file( char *path )``````

int include_dir( char *path )``````

int code2uml()``````

int uml2code()``````
