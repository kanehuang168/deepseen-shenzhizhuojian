# Fictional recovery-page failure

Known: the page says failed; a polling read timed out. Unknown: supplier acceptance, execution status, billing and final footage. Competing explanations are a read failure, a real execution failure and work still in progress.

First inspect the original authoritative job and ledger read-only and check the actual entry/version. Until then do not resubmit, refund or alter status. If a read-only timeout is confirmed, preserve an unknown/pending status and recover the same task rather than rebuilding generation.

Real acceptance would reproduce recovery after a temporary network loss: same ID, no duplicate charge, eventual result retrievable. Disappearing error text or health alone is insufficient. This example describes a plan; these queries and changes were not executed.
