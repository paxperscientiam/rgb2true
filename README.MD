README
--

`rgb2true` accepts up to three space separated integers that fall in the range [0,255]. It will return a `printf` argument ready to use.


__Example__

``` shell
$./rgb2true 255 0 255
```

Returns the following:
``` shell
\x1b[38;2;255;0;255mTRUECOLOR\x1b[0m
printf "\x1b[38;2;255;0;255m%s\x1b[0m\n" "example text"
```




