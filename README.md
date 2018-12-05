# TaskAllocAut
Task allocation for multi-robot system with automaton operations

Based on the modified version of dk.brics.automaton package (https://github.com/huanfez/dk.brics.automaton), automaton described tasks are allocated to mulple robots. Each robot will obtain the local tasks it should perform and be able to swap to another robot according to the temporal requirements of task automaton. 

Each robot is associated with multiple capabilities for executing tasks. For example, robot 1 is assocaiated with {a, b, e }, robot 2 is assocaiated with {a, c, e } and robot 3 is assocaiated with {a, d, e }. All 3 robots are assigned to perform task automaton featured with event set {a, b, c, d, e}.

Consequently, the inputs are the defined robot capability set and automaton decribed tasks. The outputs are the optimal-cost associated task allocation solutions constrined with specific temporal logics.
