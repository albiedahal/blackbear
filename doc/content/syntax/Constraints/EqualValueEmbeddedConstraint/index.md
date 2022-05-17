# EqualValueEmbeddedConstraint

The `EqualValueEmbeddedConstraint` block is used to construct a set of `EqualValueEmbeddedConstraint` objects for applying these constraints on multiple sets of blocks and on multiple variables with minimal input. These individual `EqualValueEmbeddedConstraint` objects are used to define constraints that tie the values of variables at the nodes in a single block to the containing elements in another block. Prescribing this input can be tedious of these constraints are to be defined for multiple blocks and variables, because many input blocks would be required. The `EqualValueEmbeddedConstraint`  block simplifies that process by allowing for multiple blocks and directions to be defined in a single input file block.

## Constructed Objects

This block sets up multiple [EqualValueEmbeddedConstraint](/constraints/EqualValueEmbeddedConstraint) objects.

## Example Input Syntax

!listing test/tests/actions/EqualValueEmbeddedConstraintAction.i block=Constraints/EqualValueEmbeddedConstraint/batch

!syntax parameters /Constraints/EqualValueEmbeddedConstraint/EqualValueEmbeddedConstraintAction

!syntax inputs /Constraints/EqualValueEmbeddedConstraint/EqualValueEmbeddedConstraintAction

!bibtex bibliography
