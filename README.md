# Create: Resource Tweaks

Adds various recipes intended to make some basic non-renewable resources, well, renewable.

## Product Chains

This mod takes a product chain approach, fleshing out a production process for Zinc and Copper that emulates the Iron and Gold processes in base Create, without altering any existing recipes.

These product chains are listed below - steps added or changed are in **bold**

### Iron
Cobblestone → Gravel → Iron Nuggets

### Copper
Limestone → **Dripstone Block** → **Copper Nuggets**

### Zinc
Cobblestone → Gravel → Sand → Soul Sand → Scoria → **Scorchia** → **Zinc Nuggets**

### Gold
Cobblestone → **Calcite** → Diorite → Granite → Red Sand → Gold Nuggets

## Tuff Creation

**Heated Compacting:** Cobbled Deepslate + Gravel + Dripstone Block + Scorchia + Red Sand + Lava (100mb) → **5x Tuff**

Tuff now acts as a capstone upgrade to Create's metal generation, combining the pre-metal outputs of all four product chains into a single, higher-yield process.

In base Create, crushing Tuff gives a 10% chance for each of the four metal nuggets. Because this recipe outputs **5 Tuff per craft**, crushing the batch yields an expected **0.50 nuggets of each metal**—a significant efficiency boost over processing the inputs individually.

The default Tuff Crushing recipe is completely untouched, preserving compatibility with addons that inject extra outputs into it (such as *Create: Crafts & Additions*, which adds Electrum Nuggets).

### Tuff vs. Processing Directly

Figures are expected averages, per input item or per run.

| Metal | Input | Direct process | Direct yield | Via Tuff (per batch) | Increase |
|---|---|---|---|---|---|
| Iron | Gravel | Washing | 0.12 nuggets (12% x 1) | 0.50 nuggets | 4.2x |
| Copper | Dripstone Block | Crushing | 0.24 nuggets (12% x 2) | 0.50 nuggets | 2.1x |
| Zinc | Scorchia | Crushing | 0.36 nuggets (12% x 3) | 0.50 nuggets | 1.4x |
| Gold | Red Sand | Washing | 0.36 nuggets (12% x 3) | 0.50 nuggets | 1.4x |
| **Total** | One of each | | **1.08 nuggets** | **2.00 nuggets** | **1.85x** |

## Recipes

Every new recipe is listed below.

**No changes are made to existing recipes.**

| Process | Inputs | Output | Notes |
| :--- | :--- | :--- | :--- |
| **Compacting** | 1× Cobblestone + 1× Nether Quartz + 100mb Lava | 2× Calcite | More efficient alternative to crafting Diorite in Gold production |
| **Compacting (Heated)** | 4× Cobblestone | 1× Cobbled Deepslate | Requires a heated Blaze Burner |
| **Compacting (Heated)** | 1× Cobbled Deepslate + 1× Gravel + 1× Dripstone Block + 1× Scorchia + 1× Red Sand + 50mb Potion of Infestation | 5× Tuff | Requires a heated Blaze Burner |
| **Crushing** | 1× Dripstone Block | 2× Copper Nuggets *(12% chance)* | Crushing Wheels only; leaves default Clay Ball Milling recipe intact |
| **Crushing** | 1× Scorchia | 3× Zinc Nuggets *(12% chance)* | Crushing Wheels only |
| **Filling (Spout)** | 1× Scoria + 100mb Lava | 1× Scorchia | Dye-free alternative to Black Ink (or *Create: Dragons Plus* bulk coloring) |
| **Filling (Spout)** | 1× Limestone + 250mb Water | 1× Dripstone Block | — |