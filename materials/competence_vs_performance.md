# How can we test AI models? Competence vs Performance

A goal in AI is to measure progress and `benchmark` AI models. To this end Ai researchers have designed a slew of tests. 

Let us examine what these tests actually try to tease apart. For any test, we (the human designers) have an underlying conception of an ability or a _concept_ or _skill_ that we are trying to test for.

This underlying skill or ability is called _competence_.

The actual score on that test is called _performance_.

_Competence_ can also refer to the [knowledge or internal capacity of a system](https://www.pnas.org/doi/10.1073/pnas.1905334117) [2].


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

Machines might use completely new concepts that we have not anticipated. In certain cases, we might need a new vocabulary or new worlds (`neologisms`) to describe these concepts [3].



## Connection to explanations

Ultimately our quest for understanding how intelligent a system is maybe connected to a need to [explain](https://www.science.org/doi/abs/10.1126/science.aem0071).

Explanations are like _models_. All of them might be wrong, but some are useful.

>Explanations are made, not found (Lombrazo explains in her book [1])


## Species fair comparisons of LLMs and humans

- New tests and benchmarks may be required

For example, LLMs do not `see` like we do. So is this a fair comparison to give them the same test?

We can create a new benchmark that will test LLMs and humans on an equal footing. We can even design a new human participant study that will (for example) give humans just json strings to read (and not images).



## Generalization capabilty as a measure of competence

- Test broad generalization ( to another domain such as 2D to 3D) to test _competence_. This is broad generalization as defined by Francois Chollet [4].

This can be tested in a number of different environments such as ARC-AGI-3 and the Animal AI testbed [5].

## Mechanistic intepretability as a new measure of competence

## Mutate tasks to probe competence


## Towards a more rigorous definition of competence


## Why study this?

This would, we hope, lead to a more general theory of intelligence.


This would also aid explainability research as LLMs and advanced AI gets deployed in mission critical areas such as healthcare, robotics, home automation, etc.


## References

[1] We have some explaining to do, Science, Chaz Firestone, 2026 https://www.science.org/doi/abs/10.1126/science.aem0071

[2] Performance vs. competence in human–machine comparisons, Chaz Firestone, PNAS, 2020, https://www.pnas.org/doi/10.1073/pnas.1905334117 

[3] Apply Rich Psychological Terms in AI with Care (2019).  Henry Shevlini, Marta Halina. Nature Machine Intelligence, 1: 165-167.

[4] Francois Chollet On the Measure of Intelligence

[5] The Animal-AI Environment: A Virtual Laboratory for Comparative Cognition and Artificial Intelligence Research (2025). With Konstantinos Voudouris et al. Behavior Research Methods, 57(107), 1-23.
