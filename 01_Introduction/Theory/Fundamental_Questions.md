# Fundamental Questions About Algorithms

Given an algorithm to solve a particular problem, there are three
fundamental questions.

## Three Questions

1. What is it supposed to do?
2. Does it really do what it is supposed to do?
3. How efficiently does it do it?

## Technical Terms

The three aspects are:

| Question | Technical Term |
|---|---|
| What is it supposed to do? | Specification |
| Does it really do what it is supposed to do? | Verification |
| How efficiently does it do it? | Performance Analysis |

---

## 1. Specification

The specification should formalize the crucial details of the problem
that the algorithm is intended to solve.

The specification may be based on a particular representation of the
associated data or may be presented more abstractly.

Typically, it specifies how the inputs and outputs of the algorithm
are related.

There is no general requirement that the specification is complete
or non-ambiguous.

---

## 2. Verification

For simple problems, it may be easy to see that an algorithm will
always work and satisfies its specification.

For more complicated specifications or algorithms, correctness may
not be obvious.

In such cases, effort is needed to verify whether the algorithm is
indeed correct.

### Testing

Testing a few particular inputs can sometimes be enough to show that
an algorithm is incorrect.

However, most algorithms have a huge number of possible inputs.

Therefore, testing particular cases alone is not enough to be sure
that an algorithm satisfies its specification.

### Correctness Proofs

Correctness proofs are needed to be sure that an algorithm satisfies
its specification.

The notes discuss proofs and useful ideas such as invariants, but
usually in an informal manner.

Formal verification techniques are complex and are normally left until
after the basic ideas have been studied.

---

## 3. Performance Analysis

The efficiency or performance of an algorithm relates to the resources
required by it.

Examples of resources include:

- How quickly it will run
- How much computer memory it will use

Performance usually depends on:

- The problem instance size
- The choice of data representation
- The details of the algorithm

Efficiency normally drives the development of new data structures
and algorithms.

The general ideas concerning efficiency are studied in Chapter 5.
