# Backopier
Uses [librsync](https://github.com/librsync/librsync) to do delta / incremental backups

https://github.com/mirfatif/Backopier/assets/33040459/5ef73eab-63b0-40ca-9471-a96aef6de635

https://github.com/mirfatif/Backopier/assets/33040459/4fe27558-e782-470c-b0cb-3dd2d696f2d0

```
Usage:
 -a,--save-dac             Backup DAC meta (uid, gid, mode) too
                           (slows down syncing)
 -c,--crash-file <arg>     File to write exception stack traces
 -d,--delete-ext           Delete extraneous files
                           (slows down syncing, not for every sync)
 -f,--file <arg>           File with the list of files to sync
 -h,--help                 Show this help
 -i,--id-file <arg>        File with client id
 -j,--jni-dir <arg>        JNI libs dir
 -k,--black-file <arg>     File to read and write blacklisted files
 -l,--log-file <arg>       File to write final summary
    --list <arg>           Dry run - list files to be synced
 -m,--max-mem <arg>        Max memory size to hold files in RAM
                           (default 50MB)
 -n,--max-conn <arg>       Max no. of parallel connections with server
                           (default is the no. of CPUs)
 -q,--no-denial            Quit on access denied to any file
 -s,--symlinks             Backup symlinks too
                           (slows down syncing)
 -t,--tmp-dir <arg>        Temporary directory for syncing
 -v,--verbose-file <arg>   File to save verbose results
```
