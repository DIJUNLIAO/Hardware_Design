<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>

# Electrical Circuits I

## Basic Introduction

### Circuit

Circuits is a network that connecting electrical elements by using wires. Usually, in this course, we use ideal elements and wires.

### Currents and Voltage

Electrical current $( I )$ is caused by the movements of electrical charges $( Q )$,  current is defined as the number of charges go through a cross section of wire per time unit. The actual direction of current is the direction that direction of positive charge move. The unit of electrical current is called *Ampere* $(A)$.

$$
I=\frac{\mathrm{d}Q}{\mathrm{d}t}
$$

Electrical voltage $( V )$ is the difference of electrical potential between two points in electrical field (the energy needs to move electrical charges from one point to another).  The unit of electrical voltage is called *volt* $(V)$.

### Reference Direction and Actual Direction

Reference direction is a direction specified. 

For electrical current direction, if the reference direction is same as the actual direction, then the current will bigger than 0 $(i>0)$, otherwise, it will smaller than 0 $(i<0)$.

For electrical voltage direction, usually we specified that its direction is the direction from a high potential to a low potential (in a electrical field). In a electrical circuit, it is the direction from the positive electrode $(+)$ to the negative electrode $(-)$ of a source.

For an element, if the reference direction of its current is same as the direction of its voltage (from $+$ to $-$), we called its current and voltage associated reference direction, otherwise, it is called non-associated reference direction.

### Electrical Power and Electrical Energy

Electrical power is the work that the current done per time unit, the unit of it is *Watt* $( W )$:

$$
\mathrm{d}W=u \mathrm{d} q=ui\mathrm{d}t
$$

As we just say, energy is the work done by electrical field force by moving electrical charge from one point to another in electrical field, the unit of it is *Joule* $( J )$. it can be represented as:

$$
W(t)=\int\mathrm{d}W=\int_{q(t_0)}^{q(t)}u\mathrm{d}q=\int_{t_0}^{t}u(\xi)i(\xi)\mathrm{d}\xi
$$

Note that here it is called absorbed energy of an element, and the direction of current and voltage must be associated. Otherwise, it will called emit energy.
