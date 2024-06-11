# software-correctness-course-materials

This repository contains lecture slides for the *Software Correctness* Course at Aarhus University.

Below is the schedule for the course, with links to the PDF files of associated lecture slides.

## Week 1: Introduction

The purpose of the course is explained. Taking the view that software development is an engineering activity, we argue how reasoning about software contributes to its correctness.  The use of Sireum, Logika and Slang is motivated, and a small example is considered to allow the students to become slowly familiar with Sireum.

* [Slides](slides/01_Introduction.pdf)
  
## Week 2: Tracing Facts

Beginning with how values are traced through programs, with which the students are very familiar, it is motivated how facts, as generalizations of values, are traced through programs.  At first only sequences of assignments are considered, and reasoning is practiced based on axiomatic semantics, interpreting programs as predicates and symbolic execution.  By the end of this week the students are comfortable with reasoning about simple programs without executing them, using calculation and proof.

## Week 3: Conditionals

The students learn how control flow is used to trace facts though programs containing if-statements. As the preceding week, the different ways of reasoning are discussed.  This approach is also followed in the coming weeks.  Compared to the programs of Week 2, the formulas considered become larger and most students are not accustomed to this. It is practiced, how to read and manipulate such formulas.  This skill is an essential prerequisite for the coming weeks!
    
## Week 4: Contracts (Test)

The use of contracts is motivated discussing the obligations of caller and callee. After the usual terminology and the contract syntax have been introduced, it is discussed how contracts support testing. Equivalence partitioning and boundary value analysis are applied to contracts, and symbolic execution is used to derive test cases for contracts accompanied by an implementation.  The students see how the methodology benefits their software development skills while being prepared to carry out verification proofs.

## Week 5: Contracts (Proof)

Compositional proofs of Slang programs are considered.  The students make extensive use of pre- and post-conditions, and learn how come up with these when verifying larger programs.
    
## Week 6: Loops and Recursion

The interrelated concepts of induction, recursion and iteration are discussed.  Facts are traced through recursive functions and while loops, leading to the concept of (inductive) invariant.  Termination and the use of variants are discussed.

## Week 7: Unfolding and Fixpoints

In order to be able to discuss bounded analysis of loops and recursion, unfolding and fixpoints are discussed.  At this stage the students must be comfortable with handling large formulas.  The main reason for moving slowly in the beginning of the course is to prepare the students for this. 
Logika provides specific features to support reasoning by unfolding,  permitting the students to check the result of ``manual'' unfolding against Logika's.

## Week 8: Loops and Recursion Testing

In Week 6 verification of loops and recursive functions by proof has been discussed.  Based on unfolding introduced in Week 7, bounded testing of loops and recursive functions and its relationship to the approach by proof is discussed. Symbolic execution is used to derive test cases.  Because of the unfolding this is just the same as in Week 4.

## Week 9: Sequences and Arrays

Sequences (that can also be used like arrays in Slang) are introduced. More complex contracts and programs are verified making use of formulas making extensive use of quantification.  The modification of formulas with quantifiers is challenging.  So, the students must be confident about the verification methodology and the use of Logika at this stage.

## Weeks 10--11: Verification Examples and Practice

Various examples with sequences and structured data-types are considered and more intricate algorithms verified.  In order to succeed with this, the students practice how annotate their programs with facts and invariants starting from contracts, and how to use programs as proofs.  The students get some familiarity with verification and proof methodology.

    
