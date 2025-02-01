1. Create basic pizza with at least:
```
features
    Pizza
        mandatory
            Dough
            Cheese
            Sauce
                alternative
                    ...
        optional
            ...
```
2. Create some constraints according to features e.g.,
`Pineapple => Ham`
3. Introduce attributes with at least one that allows numerical operations e.g.: Calories, Price, Fat
4. Create sum(Attribute) < X constraint
5. Create group cardinality over optional ingredients
6. Make Cheese an Integer feature add Unit attribute and limit Cheese with a constraint
7. Create String attribute (e.g. Greetings on box)
8. Limit Length of String attribute, box does not have infinite space
9. Open configurator to show new dependencies