Dirdiff
=======

Efficiently compute the differences between two directories.

Intended to work on large directories.

Not intended to display the diff of the files' content.

```
Usage: dirdiff [OPTIONS] <DIR1> <DIR2>

Arguments:
  <DIR1>
          First directory to diff from

  <DIR2>
          Second directory to diff from

Options:
  -j, --jobs <JOBS>
          Number of parallel threads to use.

          Use 0 or no option for auto-detection.

  -h, --help
          Print help information (use `-h` for a summary)

  -V, --version
          Print version information
```