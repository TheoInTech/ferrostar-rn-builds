# ferrostar-rn-builds

Prebuilt React Native packages of [Ferrostar](https://github.com/stadiamaps/ferrostar) (BSD-3-Clause, © Stadia Maps), for the EVOne driver app until Stadia Maps publishes them to npm.

Each release holds the three packages built, unmodified, from one Ferrostar release tag:

- `@stadiamaps/ferrostar-uniffi-react-native`
- `@stadiamaps/ferrostar-core-react-native`
- `@stadiamaps/ferrostar-maplibre-react-native`

| Release | Ferrostar tag | Commit |
|---|---|---|
| `0.59.0` | `0.59.0` | `a499f24389554f2420c927f2aa29623221474087` |

`SHA256SUMS` lists each file's SHA-256. Consumers pin each download by its integrity hash, so a changed file is refused.

These are Ferrostar's own code only; see `LICENSE.txt`. Nothing here is supported by Stadia Maps. Use Stadia's npm packages once they exist.
