# Getters - Vehicles

The vehicles getter gives information about all vehicles.

```ts
import { useVehiclesGetter } from '@Server/getters/vehicles.js';

const getter = useVehiclesGetter();

// Get all vehicles in range of a position
const vehiclesInRange = getter.inRange(new alt.Vector3(0, 0, 0), 5);
```