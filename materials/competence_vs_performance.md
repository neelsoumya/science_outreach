# How can we test AI models? Competence vs Performance

A goal in AI is to measure progress and `benchmark` AI models. To this end Ai researchers have designed a slew of tests. 

Let us examine what these tests actually try to tease apart. For any test, we (the human designers) have an underlying conception of an ability or a _concept_ or _skill_ that we are trying to test for.

This underlying skill or ability is called _competence_.

The actual score on that test is called _performance_.



## Intelligence and Skill

What is intelligence?

Marcus and Hutter define intelligence as the ability or skill to achieve goals in a wide range of environments.

Intelligence can also be _task specific_. That is a penguin has evolved in an environment. It is intelligence enough to solve tasks such as hunting for fish and swimming in water. It does not have a need to run on land or fly. Hence it is not very good in these environments.


                    +---------+
                    |  AGENT  |
                    | Human,  |
                    | animal, |
                    | or AI   |
                    +---------+
                         |
                    takes actions
                         |
                         v
                +----------------+
                |  ENVIRONMENT   |
                | Chess, science,|
                | conversation,  |
                | physical world |
                +----------------+
                         |
                    provides feedback
                         |
                         v
                   +---------+
                   |   GOAL  |
                   | What the |
                   | agent is |
                   | trying to|
                   | achieve  |
                   +---------+
                         |
                         v
                  Measure success
                    (REWARD)

## A new test?

Current intelligence tests do no test for skills such as those that help you generalize to a new environment or a new task. This is what Francois Chollet called broad generalization.

There is a need for tests that probe for precisely this kind of intelligence. For example, can an agent trained in a 2 dimensional environment generalize to a 3 dimensional environment? Can an agent still navigate an environment if there are changes (such as new obstacles)?


What will competence look like for such as _test_?


## Neologisms




