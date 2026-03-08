## 💡 True Dynamic Light (Visual Mod)
*Real-time lighting effects for held items, entities, and projectiles.*

### 🟢 Verified
* **Multi-Tier Performance**: Automatically adjusts quality based on server memory (Low, Mid, High, SuperHigh).
* **Held Item Lighting**: Players holding torches, lanterns, or lava buckets emit light.
* **Off-hand Support**: Lighting now works for items in the off-hand.
* **Torching to Off-hand**: Long-clicking (item use) with a light-emitting item moves it to the empty off-hand.
* **Entity Illumination**: Blazes, Magma Cubes, and Glow Squids naturally emit light.
* **Dropped Item Lighting**: Light-emitting items on the ground still function as light sources.
* **HeartBeat System**: Torches and fire-based sources have a realistic flickering effect.
* **Underwater Support**: Sea lanterns and other water-loggable items work submerged.
* **Dynamic Fire Lighting**: Entities on fire emit light while burning.

### 🟡 Needs Refinement
* **Raycasting Accuracy**: Lighting occasionally clips through thin walls or corners.

### ⚪ To-Do
1. **Projectile Lighting**: Glowing projectiles (like Flaming Arrows or Fireballs) should emit light while in flight.
3. **Colored Lighting**: (Experimental) Use different light block intensities or particles to simulate colored light for Soul Torches or Redstone.
4. **Custom Item Tags**: Allow other mods to register light-emitting items via tags (e.g., `dynamic_light:15`).
5. **Armor Illumination**: Wearing specific armor (like a "Glow Helmet") should provide light.
6. **Dimming Effect**: Gradually decrease light intensity as a source (like a torch) "burns out" if a durability system is implemented.
7. **Performance Toggle**: Add an in-game command to manually switch between performance tiers.
8. **Block-to-Light Mapping**: Expand the `ItemIlumination` list to include all 1.21+ light-emitting blocks (e.g., Trial Spawners, Vaults).

---
