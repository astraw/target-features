# target-features

Return list of enabled cpu target features.

Example:

```
fn main() {
    println!("{:?}", target_features::target_features());
}
```

Could print various results:

- `["fxsr", "sse", "sse2"]`
- `["aes", "avx", "avx2", "bmi2", "fma", "fxsr", "lzcnt", "popcnt", "rdseed", "sha", "sse", "sse2", "sse3", "sse4.1", "sse4.2", "ssse3", "xsave", "xsavec", "xsaveopt", "xsaves"]`

This code is derived from
https://gist.github.com/AngelicosPhosphoros/4f8c9f08656e0812f4ed3560e53bd600 .
