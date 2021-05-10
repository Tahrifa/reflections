Research paper: https://papers.nips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf
Machine learning offers a fantastically powerful toolkit for building useful complex prediction systems quickly. 
In this paper, it is argued that ML systems have a special capacity for incurring technical debt.
Because they have all of the maintenance problems of traditional code plus an additional set of ML-specific issues. 
In the paper, several ML-specific risk factors are explored to account for in system design. 
These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, configuration issues, changes in the external world, and a variety of system-level anti-patterns.
In Figure 1, it shows that only a small fraction of real-world ML systems is composed of the ML code, as shown by the small black box in the middle. 
The required surrounding infrastructure is vast and complex.
According to Figure 1, It may be surprising to the academic community to know that only a tiny fraction of the code in many ML systems is actually devoted to learning or prediction.
Technical debt is a useful metaphor.
But it unfortunately does not provide a strict metric that can be tracked over time.
