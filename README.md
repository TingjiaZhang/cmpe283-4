# cmpe283-4


What did you learn from the count of exits? Was the count what you expected? If not, why not?
Comparing withnested paging, shadow paging requires VMM to be more involved. In nested paging, guest manage own page tables(CR3). Shadow paging models are more complex, it has more code and more interactions. So the number and types of exits should be more than nested paging.

What changed between the two runs (ept vs no-ept)?
With EPT,the VM Sometimes called “SLAT. Without EPT, it has more quits
