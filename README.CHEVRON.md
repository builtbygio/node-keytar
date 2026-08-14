# keytar (Chevron)

**Required exports** (github package credentials): Promise-returning
`getPassword`, `setPassword`, `deletePassword`, `findPassword`,
`findCredentials`.

Chevron rebuilds the addon with electron-rebuild (`--ignore-scripts`
skips any install hook). Do not switch the JS API to callbacks.
