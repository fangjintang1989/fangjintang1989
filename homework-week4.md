Control Flow Testing (CFT)

CFT Technique

Test preparation Build and verify the model (CFG)
Test cases: CFG ) path to follow
Outcome checking: what to expect and how to check it Other steps: Standard (Chapter 7)
Test planning & procedure preparation Execution: normal/failure case handling Analysis and Followup
Some specific attention in standard steps Confirmation of outcome and route in analysis and followup

CFT: Path Definition

Test cases: CFG ) path to follow
Connecting CFG elements together in paths Define and select paths to cover Sensitize (decide input for) the paths

CFT: Path Selection

Path selection (divide & conquer)
Path segment definition Sequential concatenation Nesting of segments Unstructured construction: difficult Eliminate unachievable/dead paths
(contradictions and correlations) "Divide": hierarchical decomposition for structured programs
"Conquer": Bottom-up path definition one segment at a time via basic cases for nesting and sequential concatenation

CFT: Sensitization

Path sensitization/realization
Logic: constant predicates Algebraic: variable predicates Use simple, obvious test cases Rely on good application knowledge
run through first
add other cases later Obtain input values (test point)
select for non-unique solutions Alternative solutions via DFT later
Trouble sensitize => check others first
Unachievable? Model/specification bugs? Nothing above => failure
