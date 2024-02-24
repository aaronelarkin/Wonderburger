Aaron L, 24/02/2024

Please refer to main document for images of process used and repository states after each merge.

Local repository states are from the 'aaronelarkin' account.


## Steps (after creating pull requests for each branch created for each ingredient):
- 'We' identified that all pull requests included the particular ingredient on the second line. Conflicts are inevitable.
- 'We' agreed upon an ordering of ingredients (Cheese, Bacon, Egg) between buns
- 'We' agreed upon approving pull requests in this order

- main branch on remote repo:
    top bun
    bottom bun

## Approving pull requests:

### Cheese
- Pull request for Cheese approved. No conflicts arose.
- main branch on remote repo:
    top bun
    Cheese
    bottom bun 

### Bacon
- Pull request for Bacon currently denied. Conflicts arose because Bacon was trying to replace Cheese on line two.
- Resolved the conflict in GitHub editor by shifting Bacon to line three and bottom bun to line four.
- Pull request merge was now possible and completed.
- main branch on remote repo:
    top bun
    Cheese
    Bacon
    bottom bun 

### Egg
- Pull request for Egg currently denied. Conflicts arose because Egg was trying to replace Cheese on line two.
- Resolved the conflict in GitHub editor by shifting Egg to line four bottom bun to line five.
- Pull request merge was now possible and completed.
- main branch on remote repo:
    top bun
    Cheese
    Bacon
    Egg
    bottom bun 

## Local repo results
Local repo of the ingredient-specific branches are still:
    top bun
    Specific Ingredient e.g. Bacon
    bottom bun

Local repo of the main branches before pulling:
    top bun
    bottom bun

Local repo of the main branches after pulling:
    top bun
    Cheese
    Bacon
    Egg
    bottom bun