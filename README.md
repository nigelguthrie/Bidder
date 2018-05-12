# Bidder
Bid a Bridge-hand

Parameters: bridge-hand, system-file-name, bidding-record-file-name, new-calls)
Process:
1. Evaluate
   a. HCP
   b. Suit-lengths.
   c. Winners,
   d. Hand type (Pudding = (4333), Balanced = (4432), Dull = (5332), Empty = (4441), Freak = (5+5+), Long = (6+)
   
2. Look-up (System-file, Bidding-record, new-calls, Evaluation).
3. Terminate and close if 3 passes.
4. Update bidding-record with LHO new-call OXO new-call, RHO new-call, your new-call).
