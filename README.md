# search_combos
Search a list of values and find combinations matching a target sum.

This is a simple Python module use to find combinations that sum up a target value. Main usage is to match customer payments to open invoices.

Some considerations:
- The module is designed to be executed manually in a terminal, so it's mainly optimized to allow easy input and provide progress feedback.
- All values should be integers. If you need decimals, multiply the values by the need factor to transform them to integers before feeding them to the module.
- To simplify the generation of check scripts, list values are passed as space separated strings.
- It allows to search for multiple targets in one run.
- It allows to search for a combined targets based on the list of initial targets.
- It allows negative values, so it can be fed a list positive and negative values to be combined.
- The module assumes that the most probably combinations include almost all input values, thus the search starts with the highest combinations. This can be changed using an input parameter to the search function.
- A range of values can be passed to the search function to limit the search to a certain amount of combinations. For example, limit the search to combinations of 10 to 15 values. This can be used to interrupt a search and restart later, skipping already searched combinations.
- To be continued...
