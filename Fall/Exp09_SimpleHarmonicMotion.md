<span id="lab:M9" label="lab:M9"></span>

# Background

!!!!!!!!!!!!!!! Re-lable springs as A and B, then use 1 and 2 to
represent stretched lengths

When the magnitude of the net force acting on a body is linearly related
to the displacement of the body and is acting in a direction opposite to
the displacement, the body will oscillate in simple harmonic motion
around the point where the net force is zero. We will investigate the
one-dimensional motion of a mass which is constrained by a net force
*F* =  − *k**x*. This linearly related force is said to be obeying
Hooke’s Law. That is to say, if the mass is displaced a distance *x*, a
restoring force will act in a direction opposite to the displacement
with a magnitude equal to the spring constant, *k*, times the magnitude
*x*. The independence of the period on the amplitude and the effect of
energy loss mechanisms on the motion will also be examined.

Consider the system illustrated in
Fig. <a href="#M09Fig01" data-reference-type="ref"
data-reference="M09Fig01">1</a>. The mass is assumed to be resting on a
frictionless surface and is constrained by the two springs shown.

<div class="center">

<figure>
<embed src="Experiment07Figures/Figure01.pdf" id="M09Fig01"
style="width:5.5in" />
<figcaption aria-hidden="true">System sketch for Harmonic Motion
experiment.</figcaption>
</figure>

</div>

The springs each apply a force according to Hooke’s Law as follows
$$\\begin{aligned}
  F_1 & = & -k_1\\, x - F_0\\\\
  F_2 & = & -k_2\\, x + F_0.\\end{aligned}$$
When *x* = 0, each spring pulls an equal and opposite amount
*F*<sub>0</sub> resulting in a net force of
*F* = *F*<sub>1</sub> + *F*<sub>2</sub> = 0 at the center equilibrium
position.

When the mass is displaced to some point *x*, the net force *F*(*x*) is
given by
*F*(*x*) = *F*<sub>1</sub>(*x*) + *F*<sub>2</sub>(*x*) =  − (*k*<sub>1</sub>+*k*<sub>2</sub>)*x*.
These two springs acting together in this manner produce a force
*F*(*x*) =  − *k*<sub>*e**f**f*</sub>*x*, where
*k*<sub>*e**f**f*</sub> = *k*<sub>1</sub> + *k*<sub>2</sub>, or we can
say that the force on the mass acts as if one spring was tied to it with
an effective spring constant *k*<sub>*e**f**f*</sub>.

If we displace the mass to some position *x* = *A* and release it at
time *t* = 0, we can determine how the mass will move as a function of
time under the influence of the restoring force *F*(*x*). Using Newton’s
Second Law and the definition of the acceleration *a*, we can write
$$\\label{eq:M09fx}
  F(x) = m\\, a = m \\frac{{\\rm d}^{2}x}{{\\rm d} t^{2}} = -k x.$$
In order to find a solution to this equation, we need to find a function
*x*(*t*) whose second derivative is the same as the function itself,
give or take a constant or two. One such function *x*(*t*) is
*x*(*t*) = *A*cos (*ω**t*).
where *A* and *ω* are constants. In order to evaluate the constants we
observe what the function *x*(*t*) must be at known points. One such
point is *t* = 0 where *x* = *A*, that is the release point of the
displaced mass. If we substitute the function *x*(*t*) into
Eqn. <a href="#eq:M09fx" data-reference-type="ref"
data-reference="eq:M09fx">[eq:M09fx]</a>, we will find that it satisfies
the equation if
$$\\label{eq:M09omega}
  \\omega = \\sqrt{\\frac{k}{m}}.$$

The quantity *ω* is called the angular frequency. From
Eqn. <a href="#eq:M09xt" data-reference-type="ref"
data-reference="eq:M09xt">[eq:M09xt]</a>, we see that the position of
the mass oscillates between the points  + *A* and  − *A* as the cosine
function oscillates between  + 1 and  − 1 as a function of time. The
cosine makes one complete oscillation from  + 1 to  − 1 to  + 1 when the
quantity *ω**t* goes through 2*π* radians. The elapsed time for this one
complete oscillation is *T*, the period. Thus *ω**T* = 2*π*, or
$$\\omega = \\frac{2\\pi}{T}.$$

If the period is the time it takes the mass to make one complete cycle,
the frequency will be *f* = (1/*T*) or *ω* = 2*π**f*. Using
Eqn. <a href="#eq:M09omega" data-reference-type="ref"
data-reference="eq:M09omega">[eq:M09omega]</a> we can write the period
as
$$\\label{eq:M09period}
  T = 2 \\pi \\sqrt{\\frac{m}{k}}.$$
Note that the period of oscillation is independent of the amplitude *A*
of the oscillation for this case where there are no energy loss
mechanisms.

When the system is started, the mass was displaced a distance *A* and
then released. When the system is displaced that distance *A*, a certain
energy is given to the system in the form of potential energy stored in
the springs in the amount of *U* = (1/2)*k**A*<sup>2</sup>. Thereafter,
this initial energy is the total mechanical energy of the system, and
without any energy loss mechanisms, the total energy remains constant.
Thus, as the mass moves, it exchanges potential and kinetic energy. If
no energy is lost, the mass will always oscillate between the same
amplitude  + *A* and  − *A*. It will also have the same maximum kinetic
energy which occurs at the *x* = 0, or equilibrium position. You can see
from Eqn. <a href="#eq:M09xt" data-reference-type="ref"
data-reference="eq:M09xt">[eq:M09xt]</a> and its derivatives, that the
displacement, velocity, and acceleration of the mass are related as:
$$\\begin{aligned}
  x(t) &=&  A          \\cos(\\omega t),\\\\
  v(t) &=& -A \\omega   \\sin(\\omega t),\\\\
  a(t) &=& -A \\omega^2 \\cos(\\omega t).\\end{aligned}$$
The maximum values of *v*(*t*) and *a*(*t*) are dependent on the
amplitude *A*. Assume now that there is some energy loss mechanism
present as the mass oscillates, e.g. some friction on the surface on
which the mass is sliding or some air drag on the mass. If energy is
lost to such a nonconservative force, then the total energy of the
system will decrease. As the total energy decreases, the amplitude,
along with the maximum velocity and acceleration will also decrease.
Since neither the period nor the frequency of oscillation are functions
of the amplitude, they should remain constant. This kind of motion is
called damped harmonic motion.

The opposite effect is also true. If a little bit of energy is added
during each cycle, then the total energy of the system will increase and
be manifested by an increase in amplitude and still no change in period.

In the laboratory, we will measure the spring constants of two almost
identical springs by applying a known force and measuring the stretching
(the displacement) of each of the springs. These two springs will then
be configured with a mass on a frictionless surface (a glider on an
airtrack) as illustrated in
Fig. <a href="#M09Fig01" data-reference-type="ref"
data-reference="M09Fig01">1</a>. We will set the mass in motion by
releasing it from a displacement point and measuring the period of
oscillation. This measured period will be compared with the calculated
value obtained from
Eqn. <a href="#eq:M09period" data-reference-type="ref"
data-reference="eq:M09period">[eq:M09period]</a>.

The independence of the period on amplitude will be examined by
measuring the period for the mass started with various amplitudes. We
will also observe the behavior of the motion of the oscillating mass in
a case where the energy loss mechanism will be dramatically increased by
placing a sail on the glider to increase the air drag.

# Experimental Procedure

Before assembling the glider and springs on the airtrack, we will
determine the spring constants of the two springs. These very light
springs are capable of stretching 20 times their rest length. Please be
very careful not to damage them through careless handling or
overstretching.

<figure>
<embed src="Experiment07Figures/Figure02.pdf" id="M09Fig02"
style="width:6in" />
<figcaption aria-hidden="true">Experimental Method to measure <span
class="math inline"><em>Δ</em><em>y</em></span> for a spring in
Experiment M-<a href="#lab:M9" data-reference-type="ref"
data-reference="lab:M9">[lab:M9]</a></figcaption>
</figure>

-   For each spring perform the following steps to determine its average
    spring constant *k*<sub>spring *n*</sub>. Refer to
    Fig. <a href="#M09Fig02" data-reference-type="ref"
    data-reference="M09Fig02">2</a>.

    1.  Orient the 2-meter stick with the zero end at the top. It is
        only the change in *y* with force that matters in this
        measurement.

    2.  Attach one end of the spring to the ring stand and allow the
        spring to hang free with no mass hanging. Record
        *y*<sub>0</sub>.

    3.  Carefully hang enough mass on a weight holder on the end of the
        spring until it extends a total displacement of
        $\\sim 0.95 \\meter$ from *y*<sub>0</sub> and record the exact
        distance *y*<sub>1</sub> and mass used as *m*<sub>1</sub> (don’t
        forget the hanger is 50 grams itself). Take the measurements
        with the spring and any weights hanging stationary.

    4.  Add a additional mass to the weight holder on the end of the
        spring until it extends a total displacement of
        $\\sim 1.55 \\meter$ from *y*<sub>0</sub> and record the exact
        distance *y*<sub>2</sub> and mass used as *m*<sub>2</sub> (don’t
        forget the hanger is 50 grams itself). Take the measurements
        with the spring and any weights hanging stationary.

    5.  Calculate and record the two values of *k* for the current
        spring. The first is
        *k*<sub>1,spring1</sub> = *m*<sub>1</sub> *g*/(*y*<sub>1</sub>−*y*<sub>0</sub>).
        The second is
        *k*<sub>2,spring1</sub> = *m*<sub>2</sub> *g*/(*y*<sub>2</sub>−*y*<sub>0</sub>).

    6.  Repeat the above steps for the second spring to find
        *k*<sub>1,spring2</sub> and *k*<sub>2,spring2</sub>.

-   Calculate the average values for *k*<sub>spring1</sub> and
    *k*<sub>spring2</sub> and then determine the effective spring
    constant
    *k*<sub>*e**f**f*</sub> = *k*<sub>spring1</sub> + *k*<sub>spring2</sub>
    that will be acting on the glider.

-   Turn on the air supply to the airtrack and allow it to flow for
    several minutes.

-   Measure the mass of the larger glider and place it on the track.

-   **CASE 1:** Use the scale on the track and a corner of a glider to
    determine various displacements along the track.

    1.  Assemble the larger glider on the track and attach the springs
        to the glider and the ends of the track as in
        Fig. <a href="#M09Fig01" data-reference-type="ref"
        data-reference="M09Fig01">1</a>. Again please be careful not to
        overstretch the springs or allow them to snap back.

    2.  To determine the period of oscillation of the mass, displace the
        mass 10  from its equilibrium position and release it. When the
        mass returns to its starting point, start the stopwatch at the
        zero velocity point. Allow the mass to oscillate through 10
        complete cycles and stop the stopwatch at the zero velocity
        point at the end of the tenth cycle. That will be essentially
        the starting point. Record the time for the ten cycles and
        divide by 10 to obtain the period.

    3.  Using the same cart, find the period for starting amplitudes of
        15, 20, 25, and 30 .

    4.  Calculate the expected period from
        Eqn. <a href="#eq:M09period" data-reference-type="ref"
        data-reference="eq:M09period">[eq:M09period]</a> and compare it
        with each of the measured values for the different starting
        amplitudes.

-   **CASE 2 & 3:** Measure the mass of the small glider with and
    without the sail-holder and sail. Reassemble the system with the
    smaller glider without the sail assembly on the track.

    1.  Using the same measuring technique as used with the larger
        glider, determine the period for a starting amplitude of 10 .
        Record the time for ten cycles and divide by 10 to obtain the
        period.

    2.  Using the same cart, find the period for starting amplitudes of
        15, 20, 25, and 30 .

    3.  Calculate the expected period from
        Eqn. <a href="#eq:M09period" data-reference-type="ref"
        data-reference="eq:M09period">[eq:M09period]</a> and compare it
        with each of the measured values for the different starting
        amplitudes.

    4.  Place the paper sail assembly on the glider.

    5.  Use a starting amplitude of 25  from the equilibrium position.
        Record both the equilibrium position and your starting point;
        determine and record the amplitude (should be 25 cm). Each of
        the following steps will be started from this same amplitude
        point.

        1.  Displace the glider with its sail to the starting point and
            release it. At the end of the fifth cycle, capture the
            glider by gently pressing your finger on the edge of the
            glider as gets to its maximum amplitude point, i.e. *v* = 0.
            Record the amplitude. Be sure to use the same point on the
            glider that you used to determine the equilibrium point and
            the 25  starting point. Measure the total time for the
            cycles and divide by the number of cycles measured to obtain
            the average period. Compare this with the expected period
            from Eqn. <a href="#eq:M09period" data-reference-type="ref"
            data-reference="eq:M09period">[eq:M09period]</a>. (Use the
            total mass of the glider and sail assembly as the mass.)

        2.  Repeat step (A) five more times, each time starting the
            glider from the 25  point and allowing it to cycle five more
            cycles than the previous measurement. **Only 1 trial needed
            per number of cycles.**

# Data Analysis

Create tables for each of the two springs to measure the spring constant
by measuring the extension of the spring at two different displacements
from *y*<sub>0</sub>, $\\sim 0.95 \\meter$ and $\\sim 1.55 \\meter$.

-   Create a table for each spring with a row for each displacement
    trial including:

    -   The height *y*<sub>0</sub> of the bottom of the loop on the
        spring (no mass)

    -   the applied mass (including hanger)

    -   the gravitational force due to the mass

    -   the height *y*<sub>*n*</sub> of the bottom of the loop on the
        spring with the mass

    -   the displacement *y*<sub>*n*</sub> − *y*<sub>0</sub> due to the
        mass

    -   the spring constant

Now that the springs are characterized, create tables for the
measurement of oscillations of gliders on the air track.

-   Create separate tables for the large and small gliders including the
    common data of the glider masses and their expected periods. Create
    a row for each trial. There are 15 trials for each glider — from
    three repetitions (trials) for each of the five initial amplitudes
    (cases). **NOTE: Have each group member measure at the same time to
    be able to save time while still getting 3 trials per amplitude (if
    there are groups of two people, have someone hold two stopwatches to
    get the 3 trials).**

    -   the starting amplitude (displacement from equilibrium) in meters
        (0.10, 0.15, 0.2, 0.25, and 0.3 )

    -   the time for ten cycles

    -   determined period

-   For each glider calculate the mean and standard deviation of the
    period.

The third experiment in this lab focuses on measuring the damped
oscillation of the small glider with a sail.

-   Record the mass of the small glider with the sail assembly,
    calculate the expected period and observe the resting location of
    the glider *A*<sub>0</sub>. Calculate and record the starting point
    $A_0 + 0.250\\,\\meter$. **Reminder, only 1 trial needed per number
    of cycles.**

-   Create a row for each of the 6 number-of-cycles trials including:

    -   the number of cycles

    -   the ending point

    -   the ending amplitude (ending point minus equilibrium point)

    -   the total time

    -   the average period

-   Plotting:

    -   For all three cases produce a graph of the period *T* (*y*-axis)
        vs. the amplitude *A* (*x*-axis).

    -   For the third case produce a graph of the amplitude *A*
        (*y*-axis) vs. the number of cycles (*x*-axis). Use the starting
        amplitude *A*<sub>0</sub> as the value for zero cycles.

    -   Draw a line-of-best-fit through the data points for each plot.

# Post-Lab Submission — Interpretation of Results

-   Make sure to submit your finalized data table (Excel sheet)

-   For all three cases, do the the measured periods of the glider agree
    with the expected value?

-   What are the uncertainties? How would those uncertainties affect the
    measured period?

-   Comment (qualitatively) on the behavior of the curves from each
    plot. Do the trends make sense?

-   From the damped-oscillator plot, what do you expect amplitude of the
    glider to be after 50 cycles?

-   Does the amplitude affect the period? Why or why not?

-   How does the period depend on the mass of the glider? Is this
    expected?

-   How does an increased air drag affect the result for the period? How
    does the amplitude depend on the number of cycles (relate this to
    energy conservation)?

-   What are possible systematic errors for today’s experiments?
