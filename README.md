# base-terrain-feature-silk

The `Silk` terrain feature: a special resource a square can hold.

For example: Civ2's Silk, found on Forest.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Silk from '@civ-clone/base-terrain-feature-silk/Silk';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Silk);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
