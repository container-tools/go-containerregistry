## crane pull

Pull remote images by reference and store their contents in a tarball

```
crane pull IMAGE TARBALL [flags]
```

### Options

```
  -c, --cache_path string   Path to cache image layers
      --format string       Format in which to save images ("tarball", "legacy", or "oci") (default "tarball")
  -h, --help                help for pull
```

### Options inherited from parent commands

```
      --insecure            Allow image references to be fetched without TLS
      --osversion string    Specifies the OS version.
      --platform platform   Specifies the platform in the form os/arch[/variant] (e.g. linux/amd64). (default all)
  -v, --verbose             Enable debug logs
```

### SEE ALSO

* [crane](crane.md)	 - Crane is a tool for managing container images

