Formal methods = formal specification + formal verification

Formal specification (FS)

As part of defect prevention Formal => prevent/reduce defect injection due to imprecision, ambiguity, etc Briefly covered as related to FV
Ideas:
1.Formal specification
Correctness focus Different levels of details 3Cs: complete, clear, consistent Two types: descriptive & behavioral
2.Descriptive formal specifications
Logic: pre-/post-conditions Math functions Notations and language support: Z, VDM, etc
3.Behavioral formal specifications: FSM, Petri-Net, etc

Formal verification (FV)
 As part of QA, but focus on positive "Prove absence of fault" People intensive
Several commonly used approaches 
Ideas:
1.Formal verification: proof of correctness
Formal specs: as pre/post-conditions Axioms for components or functional units Composition (bottom-up, chaining) Development and verification together
2.Other related approaches
Semi-formal verification Model checking Inspection for correctness
Basics:
1.Basic approaches
Floyd/Hoare axiomatic Dijkstra/Gries weakest precond (WP) Mills’ prog calculus/functional approach
2.Basis for verification
logic (axiomatic and WP) mathematical function (Mills) other formalisms
3.Procedures/steps used
bottom-up (axiomatic) 
backward chaining (WP)

Model checking

Behavioral specification via FSMs Proposition: property of interest expressed as a suitable formula 
Model checker: algorithm/program to check proposition validity
Proof: positive result
Counterexample: negative result
