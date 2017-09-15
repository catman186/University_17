# Topic 0: Mathematics used in this Course (Week 1-2)

## Topology

mainly see notes hand-written in notebook.

* compact sets
* open and closed sets
* subsets

### Compact Sets

**Definition**

In general topology, **compactness** is a property that generalizes the notion of a subset of Euclidean space being **closed** (that is, containing all its limit points) *and* **bounded** (that is, having all its point within some fixed distance of each other).

Subsets of $R^{n}$ is called compact if it is **closed** and **bounded**

* Any open interval is $R$ (or any open ball in $R^{n}$) is not compact (may be bounded, but is not closed).
* Any closed and bounded interval in $R$ (any closed ball in $R^{n}$) is compact.
* All of $R^{n}$ is not compact (it is not bounded)


### Continuity

* Most economics applications: assume functions we deal with are continuous.
* $f$ is continuous if a small movement in $D$ does not cause a big jump in $R$.

**Definition:** 

A function $f:R \rightarrow R$ is continuous at point $x^{0}$ if, for all $\varepsilon >0$, there exists a $\delta >0$ such that $d(x,x^{0})<\delta$ implies $d(f(x),f(x^{0}))<\varepsilon$. A function is called a continuous function if it is continuous at every point in its domain. 

(Simply, a function is continuous if a small movement in the domain doesn't cause a big movement (like super big) in the range.)

