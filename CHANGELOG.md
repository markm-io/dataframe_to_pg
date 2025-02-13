# Changelog

## v0.1.12 (2025-02-13)

### Bug fixes

- Update type determination for int64dtype in writer.py to use is_integer_dtype ([`862df90`](https://github.com/markm-io/dataframe_to_pg/commit/862df9051a0ef945a4b33287a27183af2015b558))

## v0.1.11 (2025-02-13)

### Bug fixes

- Reorder type determination for pandas datetimetzdtype and int64dtype in writer.py ([`e17ede8`](https://github.com/markm-io/dataframe_to_pg/commit/e17ede81a2e507f02847f07fedd736b40aa87ec3))

## v0.1.10 (2025-02-13)

### Bug fixes

- Correct attribute name from 'column' to 'columns' in writeresult dataclass ([`c4cb5a2`](https://github.com/markm-io/dataframe_to_pg/commit/c4cb5a2e62cd3df16840444d7de1aea30864fff8))

## v0.1.9 (2025-02-13)

### Bug fixes

- Add writeresult dataclass to encapsulate dataframe write results and enhance yield_chunks functionality ([`4771974`](https://github.com/markm-io/dataframe_to_pg/commit/47719741978100515e2c1e02ef7c315d3b1f7586))

## v0.1.8 (2025-02-13)

### Bug fixes

- Remove debug print statement for table name and columns in writer.py ([`38eaf4c`](https://github.com/markm-io/dataframe_to_pg/commit/38eaf4c44443b10d3ce06295fa4542ceffa3124c))

## v0.1.7 (2025-02-13)

### Bug fixes

- Enhance type determination for pandas datetimetzdtype and streamline dataframe processing ([`aa46478`](https://github.com/markm-io/dataframe_to_pg/commit/aa46478f314c31df9a9b8914e2a17b0e22140693))

## v0.1.6 (2025-02-13)

### Bug fixes

- Add support for pandas datetimetzdtype in type determination for dataframe writer ([`2977326`](https://github.com/markm-io/dataframe_to_pg/commit/297732631d9a2a7e2e306d74751e306196983874))

## v0.1.5 (2025-02-13)

### Bug fixes

- Refine type determination for pandas int64dtype in dataframe writer ([`3713345`](https://github.com/markm-io/dataframe_to_pg/commit/371334578c2e745c67aaed4c6dab86f33d208110))

## v0.1.4 (2025-02-13)

### Bug fixes

- Enhance type determination to support pandas int64dtype in dataframe writer ([`6a71f3e`](https://github.com/markm-io/dataframe_to_pg/commit/6a71f3e0055a8a671e688a00cb5b36b63122a50a))

## v0.1.3 (2025-02-13)

### Bug fixes

- Correct argument name for truncate limit in clean_names method ([`784fefd`](https://github.com/markm-io/dataframe_to_pg/commit/784fefd13df850f37e91b06f406a032485bd0c47))

## v0.1.2 (2025-02-13)

### Bug fixes

- Streamline dataframe type determination and clean column names logic ([`ec13b76`](https://github.com/markm-io/dataframe_to_pg/commit/ec13b765d55ae30e21f6464888893f860e9e2968))

## v0.1.1 (2025-02-13)

### Bug fixes

- Update package versions in lock file and add janitor for name cleaning ([`78bb3c9`](https://github.com/markm-io/dataframe_to_pg/commit/78bb3c9b6b2a0f2ce3b0afe0e4ef4f075179f2a2))

## v0.1.0 (2025-02-02)

### Features

- Add yield_chunks parameter to control chunked processing of records (#4) ([`835ff2f`](https://github.com/markm-io/dataframe_to_pg/commit/835ff2f7d99d001fe73aac3bdb19997fcf359001))

## v0.0.2 (2025-02-01)

### Bug fixes

- Correction to table creation to use the engine instead of the connection ([`26ed491`](https://github.com/markm-io/dataframe_to_pg/commit/26ed491653e8e975af2e4c36b5bf6ec5640f97b7))

## v0.0.1 (2025-02-01)

### Bug fixes

- Add in column cleaning utilizing pyjanitor ([`8a10a44`](https://github.com/markm-io/dataframe_to_pg/commit/8a10a44eb1710422a728764cb936664d3bbdaae2))
- Initial code commit ([`f599b45`](https://github.com/markm-io/dataframe_to_pg/commit/f599b451fb233c6bdc2ba81ed951f1f47897bfda))

## v0.0.0 (2025-02-01)

### Documentation

- Add @markm-io as a contributor ([`b08f1ba`](https://github.com/markm-io/dataframe_to_pg/commit/b08f1bab1da9fd7a0e92a332b8cb2793eb6c2292))
