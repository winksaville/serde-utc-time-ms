# Serialize and deserialize between time in milli-seconds and UTC RFC 2339 time

For example: "1970-01-01T00:00:00.000+00:00" <-> 0

```
pub fn de_string_to_utc_time_ms_condaddtzutc<'de, D: Deserializer<'de>>( deserializer: D) -> Result<i64, D::Error>
pub fn se_time_ms_to_utc_string<S>(time_ms: &i64, s: S) -> Result<S::Ok, S::Error>
```

# License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
