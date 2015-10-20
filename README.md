# handy-java
Some java snippets

~~~ { .base64 }
/Td6WFoAAATm1rRGAgAhARYAAAB0L+Wj4AjVAtldABfgfIR1MvbP1vQ+3nWHN7FMjzzo2L2E29zx
26C/V9JhnMjVIEXeQW2PZ9E7MxCErgWUHiIKS/zEkGjy7W7fbsGxd9ce5CGXw4JNCJuN7c0RBRj+
xN/JsrTLJnZwH8jH6vN2qLpJh22X9vGFgyL1/+bXl9atPJb+d1nbefyLvC5PqbIRk2xrLC7ZJWhi
txZqEOjm6+vTbaCMB1zYtWDYWJrywuFA7zVEmg5myNVP2y6ja0BGx3TS2S6SAdGGVeaeASaMkWUP
LWCVgJNLvqeMR3NSRBhpTuuHBzsspMtbcb33dFSwuwykU+14LoMIBBVNXF4SK6PzwjR0RpqZVWn6
oAmJinMdhIlvExMGoBx51JC2/UKhpdfn+SiFHB6uWnOB8C3EKqCbnvNCqj1JBzmlvGnLFKCVhYGz
5TjY9rmqdv50KDIOJSif/OFR9+qw8bNj62y4l8VpnAWN+j4mntr3LNMN8eGPt3TR/rBX3kSs16Ry
5+7Hhnp4zTwZ/4vSnOPAGeg2MooZ9TAFWt4UPCW7TmmgtM8w68pmqgNcgCNbgWQ0M4160PgD5n5w
IRdO6+1y3glxzX7JJYOKSygkVYgx5QWpuYhAro43EOOZWaZP+bsInOWgjRUfGUVqLxBTfzzeRkTH
SbIhNrvzIIcCMaQRYndZyfVsqJJp9QWcxl1Tu3oSNOyv9OQAqBTSWBOwwQ02Da6HKlldyYOpekSE
GZJ1nnjEZ0KM0EyJvGm0M/Ry+rvCja126bpsJsCwGtWuZYfu8MT9f6ZfcHOeoNrA3O9hJ2hKEUB1
QPBev0ItJq6SM+xw//1sDQ9C/XqbA4ryGYkpu7Shnk8qBbxmLmhD53S0iePhagQAgaIXY4OBbduD
bPGWmwRGAZ6AooQ5ha/oGZAT1G/MNiOP6txM9QFhrs99yraAg33ceWh+GkSmcxPF2jAo5AjxCZdS
GZIMAAt9zBtS0GWPuyjvVxpO+wAAAABk02lkcsrUmgAB9QXWEQAABfwxULHEZ/sCAAAAAARZWg==
~~~

Not java but still handy:

~~~ { .bash }
find . -name '*.hs' -print0 | xargs -n1 -0 sed -i -n '/^\s*$/d;H;${x;s/^\n//;s/\nimport[^\n]*\(\n [^\n]*\)*//g;p}'
~~~
