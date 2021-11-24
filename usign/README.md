## Source: https://openwrt.org/docs/guide-user/security/release_signatures

Look through the signatures at: https://git.openwrt.org/?p=keyring.git;a=tree;f=usign

Look at the RAW data for each file and create a file for the release you want in the usign directory.

For example:
```console
vi usign/f94b9dd6febac963
    untrusted comment: Public usign key for 19.07 release builds
    RWT5S53W/rrJY9BiIod3JF04AZ/eU1xDpVOb+rjZzAQBEcoETGx8BXEK
```

At some point I will figure out how to just wget/curl all of the files into the usign directory in a script.

