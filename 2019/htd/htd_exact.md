---
layout: page
title: PACE 2019 (Track Hypertree&nbsp;Width/Exact)
sidebar_link: false
sidebar_sort_order: 6
---

## Exact 2a. Hypertree Width/Exact
### Requirement: 
The hypertree decomposition has to be optimal, i.e., of hypertree width. 

### Description:
We anticipate submissions to be based on a provably optimal algorithm, although we do not make this a formal requirement. 
Instead, if your submission halts on some instance within the allotted time and *produces a solution* that is *known* to be **non-optimal**, the submission will be **disqualified**. 
We also do not prescribe the algorithmic paradigm that is to be used; if a SAT or SMT-solver based submission consistently outperforms more direct approaches, this will be valuable information.

### Instances

Download: 
- [Download Public Instances (Exact)](/files/pace2019-htd-exact-public.tar.bz2)
- [Download Public + Private Instances (Exact)](https://doi.org/10.5281/zenodo.3354606)


There are 100 public benchmark instances, labeled htd-exact_001.hgr, htd-exact_003.hgr, ... to htd-exact_199.hgr. 

 
Larger numbers in the filename should (as a rule of thumb) correspond to harder instances. The odd instances are public and the even instances will be provided later (secret). 

For verification purposes, we also publish the sha1sum of the public archive:

SHA1 sum | filename 
--- | --- 
478afc600c11f98b20c969ecd5ff4a1badbabebc  | pace2019-htd-exact-public.tar.bz2

For individual files we refer to [Download SHA1 sums](/files/pace2019-htd-exact-public-shasums.txt)

### Evaluation 
- timeout: 30 minutes per instance
- measure: tba; but likely PAR-10, where timed-out runs are counted as 10 times the given timeout time.
- objective: minimize the measure
