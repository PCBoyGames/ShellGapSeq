# ShellGapSeq
A Shellsort gap optimizer written in Java.

## Params
 - `--length`: (int) The array length to try and optimize for.
 - `--testtry`: (int) The number of shuffles to use per value per iteration when trying the gaps.
 - `--itertry`: (int) The maximum amount of iterations that can be run when optimizing the gaps.
 - `--seqlen`: (int) The length of the gap sequence.
 - `--dist`: (String) The name of the initial distribution to try.
 - `--detail`: (None) If this param is present, all values per iteration will be shown, not just the new bests.
 - `--silent`: (None) If this param is present, no output details will be shown until the code has fully run.
 - `--seed`: (long) The seed to use for the shuffles per value per iteration when trying the gaps.
   - also accepts String "vary"
 - `--distseed`: (long) The seed to use when forming the initial distribution for randomized setups.
   - also accepts String "vary"
 - `--selseed`: (long) The seed to use when selecting random items to iterate on.
   - also accepts String "vary"
 - `--inter`: (None) If this param is present, enter Intermediation mode.
