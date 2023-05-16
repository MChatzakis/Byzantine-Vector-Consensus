# Leader-Based Byzantine-Vector-Consensus
Theoretical analysis and algorithm development for Byzantine Vector Consensus in partially synchronous environments.

This repository contains the paper and presentation of the work "On the complexity of Byzantine Vector Consensus", by Manos Chatzakis (emmanouil.chatzakis@epfl.ch), Jovan Komatovic and Rachid Guerraoui, at DCL Lab of EPFL. It also contains some preliminary papers essential to understand the contribution of this work. 

## Context
In Byzantine vector consensus, every process proposes a value and eventually all correct processes decide a vector of $n-f$ values, where $n$ is the processes of the system and $f$ is the number of processes that are Byzantine, and thus they may operate in an adversary or arbitrary way. 

The best practical solution to this problem is known to have communication complexity of $O(n^3)$ and latency of $O(f)$. 
An improvement to this solution regarding the communication complexity is known to be $O(n^2 \log n)$ but the latency of $O(n^f)$ makes it highly impractical. 

Our proposed algorithm achieves Byzantine vector consensus with communication complexity of $O(n^2 \sqrt{n})$ and latency of $O(n \sqrt{n})$

## Summary


## About


