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

Machines might use completely new concepts that we have not anticipated. In certain cases, we might need a new vocabulary or new worlds (`neologisms`) to describe these concepts.



## Connection to explanations

Ultimately our quest for understanding how intelligent a system is maybe connected to a need to [explain](https://www.science.org/doi/abs/10.1126/science.aem0071).

Explanations are like _models_. All of them might be wrong, but some are useful.

Explanations are made, not found (Lombrazo explains in her book [1])


## References

[1] We have some explaining to do, Science, Chaz Firestone, 2026 https://www.science.org/doi/abs/10.1126/science.aem0071

 
