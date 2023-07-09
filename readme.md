# serialize-d

serialize-d is a data serialization provider.

Notice: serialize-d is deprecated and will NOT recieve further updates; please switch to [ninox-d_data](https://github.com/Bithero-Agency/ninox.d-data)

## License

The code in this repository is licensed under AGPL-3.0-or-later; for more details see the `LICENSE` file in the repository.

## The core

The core itself contains:
- `SerializerBuffer`: a basic buffer for serialization
- `serialize(value, serializer)` and `deserialize(inp, serializer)` to quickly serialize or deserialize

## Subpackages

Each serialization format is provided via a subpackage:
- `serialize-d:json`: provides serialization support from/to JSON