---

## 🧪 Experiment Plan

### Test Program

I will use the same C program for every optimization level.

```c
#include <stdio.h>

int main() {
    long long sum = 0;

    for (long long i = 0; i < 100000000; i++) {
        sum += i;
    }

    printf("Sum = %lld\n", sum);

    return 0;
}
