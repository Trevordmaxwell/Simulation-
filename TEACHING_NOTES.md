# Catalytic-converter teaching aid revision

## Learning goals

A learner should be able to explain that:

1. A gasoline three-way catalytic converter addresses carbon monoxide, unburned hydrocarbons, and nitrogen oxides.
2. Reactants adsorb temporarily, bonds rearrange on the surface, products desorb, and the catalytic site is regenerated.
3. A catalyst provides a lower-energy pathway; it does not change the starting or ending energy of the reaction.
4. Atoms are conserved, and catalyst metal atoms do not become part of the normal products.
5. “Less harmful” does not mean harmless: catalytic converters do not eliminate carbon dioxide.

## Major changes

- Added the missing NO/CO reduction example so all three jobs of a three-way converter are represented.
- Added a qualitative activation-energy graph with a step-linked highlight.
- Added a balanced before/after particle graph and atom-conservation ledger.
- Made molecule counts agree with each balanced equation by grouping repeated molecules with ×N badges.
- Added a four-stage progress control, clearer Back/Next behavior, keyboard navigation, and accessible labels.
- Added pollutant context, a comprehension check, and a model-limits disclosure.
- Kept the application dependency-free as a small static bundle for GitHub Pages.

## Suggested classroom use

1. Start with carbon monoxide and ask whether the metal appears in the products.
2. Pause at “Stick & activate” and connect temporary surface bonding to the lower-barrier energy pathway.
3. At “Rearrange,” use the atom ledger to check conservation before revealing the products.
4. Compare hydrocarbon oxidation with NO reduction and ask which example is oxidation, reduction, or both.
5. End with the quick check and the caveat that carbon dioxide remains a greenhouse gas.

## Accuracy and scope notes

- Surface mechanisms are deliberately schematic, not claims about a single elementary mechanism.
- Propane is used as a representative hydrocarbon because it gives a familiar balanced equation.
- The NO example uses `2 NO + 2 CO → N₂ + 2 CO₂`, rather than implying that NO simply decomposes in isolation.
- The energy diagram is qualitative and explicitly marked as not to scale.
- The application is framed as a gasoline-engine three-way catalyst; diesel and lean-burn after-treatment systems differ.

## Manual test checklist

- Switch among all three reaction tabs and confirm the equation, diagrams, particle graph, atom ledger, and context update.
- Move forward and backward through all four steps; Back should be disabled at step 1.
- From step 4, choose “Run another cycle” and confirm the cycle count increments while metal atoms used up remains zero.
- Test at approximately 390 px and 1280 px viewport widths.
- Navigate with Tab and confirm visible focus and usable controls without a mouse.
- With focus outside a control, test Left Arrow, Right Arrow, and R.
