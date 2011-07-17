[Fowler-Noll-Vo hash](http://en.wikipedia.org/wiki/Fowler_Noll_Vo_hash)
====================

```java
import com.bitlove.fnv.FNV;

(new FNV).fnv1a_64("blah".getBytes()) => java.math.BigInteger = 14233852691173593346
```

Supported hashes are fnv1_32, fnv1_64, fnv1a_32, and fnv1a_64.

Test cases were taken from [here](http://www.isthe.com/chongo/src/fnv/test_fnv.c).

There is also a [Ruby version](https://github.com/jakedouglas/fnv-ruby).
