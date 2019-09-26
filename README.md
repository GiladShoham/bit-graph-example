## Description
An example for bit graph command.

## Structure
This project has few components:
1. card
2. card-header
3. card-body
4. test-utils
5. sort-array

card-header and card-body are dependencies of card. (grey arrow)
test-utils is *dev* dependency of card. (red arrow)
sort-array is dependency of test-utils (grey arrow)

## Run
`clone project`
`bit graph -i ./graph.pn`