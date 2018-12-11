# OPTIC: Optimising Preferences and Time-Dependent Costs
[return to homepage](../../../readme.md) | [Report a problem with this guide](https://github.com/nergmada/pddl-reference/issues/new/choose)


Year Published: 2012

Paper: [Temporal Planning with Preferences and Time-Dependent Continuous Costs](https://www.aaai.org/ocs/index.php/ICAPS/ICAPS12/paper/view/4699/4708) [Benton, J. Coles, A. Coles, A.]

Preceded By: POPF

OPTIC is a temporal planner for use in problems where plan cost is determined by preferences or time-dependent goal-collection costs. Such problems arise in a range of interesting situations, from scheduling the delivery of perishable goods, to coordinating order-fulfillment activities in warehouses.

## Support
OPTIC Supports the following features:

|Requirement                    |OPTIC|
|-------------------------------|-|
|**PDDL1.2**
|:strips                        |Yes
|:typing                        |Yes
|:disjunctive-preconditions     |No
|:equality                      |Yes
|:existential-preconditions     |No
|:universal-preconditions       |No
|:quantified-preconditions      |No
|:conditional-effects           |Yes
|:action-expansions             |No
|:foreach-expansions            |No
|:dag-expansions                |No
|:domain-axioms                 |No
|:subgoal-through-axioms        |No
|:safety-constraints            |No
|:expression-evaluation         |No
|:fluents                       |Not PDDL1.2 Definition
|:open-world                    |No
|:true-negation                 |No
|:adl                           |No
|:ucpop                         |No
|**PDDL2.1**
|:numeric-fluents               |Yes
|:durative-actions              |Yes
|:durative-inequalities         |Yes
|:continuous-effects            |Yes
|:negative-preconditions        |No
|**PDDL2.2**
|:derived-predicates            |No
|:timed-initial-literals        |Yes
|**PDDL3.0**
|:preferences                   |Yes
|:constraints                   |Maybe
|**PDDL+**
|:time                          |Yes

## Downloading and Compiling OPTIC
For more information on how to download, compile and use OPTIC, please visit the [OPTIC Homepage](https://nms.kcl.ac.uk/planning/software/optic.html)