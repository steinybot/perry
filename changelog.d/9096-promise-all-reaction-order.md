### Fixed

- `Promise.all` now preserves registration order when its input already has `.then()` reactions, while retaining the allocation-free fast path for reaction-free promises.
