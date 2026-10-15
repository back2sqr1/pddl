# Notes

PDDL - Planning domain definition language (PDDL) -
allow for a definition of a planning problem.

Actions have a condition and change properties of the environment

Ex: We have a laid property and depends on a function "Build wall" to be true.
One big query like object.

Durative action: An action with a specified duration to the amount of time the action.

Conditions on the start of the action - end of the action - and duration

Also there are numbers starting from version 2.1.

Derived predicates - predicates that are based on other predicates - reusing
predicates rather than a predicate formula

For ex: Plan on runway - pilot in plane are both predicates
Then plane can take off is a derived predicate

Timed initial literals - allows for expressing of facts that will become true
later on.

Soft constraint - where we would like something to happen but we are ok with it
not happening. Also assigns cost to each preference

PDDL+ added two core concepts - Processes and Events
Processes are something which always happens when preconditions are met.
Event - instant version of a process (happens only one)

Apptainer - is a way to use containers
