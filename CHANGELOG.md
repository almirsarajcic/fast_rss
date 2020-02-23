# CHANGELOG

## [0.2.0]

### User

- Map is returned with string keys instead of atom keys
- Now between 6.12x - 50.09x faster than next fastest tested option

### Internal

- Removed Jason dependency
- Returning elixir map directly instead of returning a stringified JSON and then using Jason to convert it to an elixir map

## [0.1.4]

- Convert RSS feed into map with atom keys
- Between 2.85x - 22.05x faster than next fastest tested option