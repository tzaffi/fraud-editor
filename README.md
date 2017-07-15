# WYSYWIG Fraud Rule Editor

## GOAL

A scaffolded JSON editor for creating, testing and analyzing fraud rules.

### Should be able to:
1. Create rules by:
    * choosing from a bouquet of signals and operators
    * defining fail conditions
    * specifying if is a stoprule and whether all or any of its conditions must fail
    * nesting with additional rules as many levels as desired
    * schema should make it impossible to create illegal rules
1. Test rules by:
    * providing a SQL query that produces an array of signal objects
1. Analyze rules by replaying the rule historically:
    * specify date range
    * compute the number of false positive and false negatives
    * compute expected precision and marginal precision
    * compute expected *revenue loss* and *loss reduction*
    

## NICE TO HAVES

* Generate and/or use
    * [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html)
    * [PFA](http://dmg.org/pfa/docs/motivation/)
* Use for customer predictive analytics as well

## Links

* Current version based on JSONEDITOR
   * [github](https://github.com/josdejong/jsoneditor)
   * [demo](http://jsoneditoronline.org)
* Better alternative by Jeremy Dorn? 
   * Can specify a schema interactively that generates a form
   * [github](https://github.com/jdorn/json-editor)
   * [demo]
