# BLAKE2s128sum
## b2s128sum Parallel Implementation written in Go

### Usage: 
<pre>b2s128sum [-v] [-c &lt;hash.ext&gt;] [-r] -k &lt;secret&gt; -t &lt;file.ext&gt;

  -c string
        Check hashsum file.
  -k string
        Key. (default "null")
  -r    Process directories recursively.
  -t string
        Target file/wildcard to generate hashsum list.
  -v    Verbose mode. (The exit code is always 0 in this mode)</pre>
  
## License

This project is licensed under the ISC License.

##### Copyright (c) 2020-2021 Pedro Albanese - ALBANESE Lab.
