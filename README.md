# Prime test

**42 C fundamentals** · Returns 1 for a prime integer and 0 otherwise, checking candidate divisors.

## Build and use

```sh
cc -Wall -Wextra -Werror -c ft_is_prime.c
```

The command builds an object file; this repository has no standalone main program.

## Implementation note

This is a function-only exercise. Inputs below 2 return 0; the straightforward half-range scan favors clarity over speed.

Source: [`ft_is_prime.c`](ft_is_prime.c). [License](LICENSE).
