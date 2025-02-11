<span id="lab:M3" label="lab:M3"></span>

# Background

**Projectile motion** is the motion of an object thrown or projected
into the air, subject only to acceleration as a result of gravity. The
applications of projectile motion in physics and engineering are
numerous. Some examples include meteors as they enter Earth’s
atmosphere, water in a water fountain, and the motion of any ball in
sports. Such objects are called *projectiles*, and their path is called
a **trajectory**.

We can represent a projectile’s motion through kinematics which utilize
its position, time, velocity, and acceleration. The kinematic equations
we will use during this lab assume both ***constant acceleration***
effects of air resistance are ***negligible*** (generalized in the next
four equations with *x* representing position along any given
dimension):

*v* = *v*<sub>0</sub> + *a**t*

$$\\label{eq:M03Kinematic_02}
  x = x\_{0} + v\_{0}t + \\frac{1}{2}at^{2}$$

*v*<sup>2</sup> = *v*<sub>0</sub><sup>2</sup> + 2*a*(*x*−*x*<sub>0</sub>)

$$\\label{eq:M03Kinematic_04}
  x = x\_{0} + \\frac{1}{2}(v\_{0} + v)t$$

Today, we will analyze both one- and two-dimensional trajectories, where
*x* will represent the horizontal direction, and *y* the vertical.
Gravity (which pulls objects down towards the center of the Earth) will
be assumed to be the only source of acceleration acting on our
projectiles; as such, the acceleration of a projectile is
*a*<sub>*y*</sub> =  − *g* and *a*<sub>*x*</sub> = 0. Since horizontal
acceleration terms are zero, we can represent horizontal motion by:

*v*<sub>0*x*</sub> = *v*<sub>*x*</sub> = constant velocity,   *x* = *x*<sub>0</sub> + *v*<sub>*x*</sub>*t*

Then, depending on the information we have available to us, we can
represent vertical motion by:

*v*<sub>*y*</sub> = *v*<sub>0*y*</sub> − *g**t*

$$\\label{eq:M03Kinematic_vertical_02}
  y = y\_{0} + v\_{0y}t - \\frac{1}{2}gt^{2}$$

*v*<sub>*y*</sub><sup>2</sup> = *v*<sub>0*y*</sub><sup>2</sup> − 2*g*(*y*−*y*<sub>0</sub>)

$$\\label{eq:M03Kinematic_vertical_04}
  y = y\_{0} + \\frac{1}{2}(v\_{0y} + v\_{y})t$$

<u>**Free Fall / Downward Trajectory (First experiment)**</u>

In the previous lab, we determined the acceleration due to gravity via
the tilted air track to take advantage of a longer time frame to measure
a small fraction of the acceleration due to gravity. This week, we will
determine the acceleration due to gravity more directly by considering a
one-dimensional trajectory (i.e. free fall).

The experimental setup will involve a free-fall timer where a metal ball
is dropped from a release mechanism as shown in
Fig. <a href="#M03_simpleProjectileLauncher_Exp1" data-reference-type="ref"
data-reference="M03_simpleProjectileLauncher_Exp1">1</a>. When the metal
ball is in then mechanism, it provides a closed circuit; once the ball
is released and the circuit opens, the computer automatically starts
timing *t*<sub>initial</sub>. The ball then hits the receptor pad on the
floor, closing the circuit and stopping the timer at
*t*<sub>final</sub>. Using the recorded time difference
*t* = *t*<sub>final</sub> − *t*<sub>initial</sub>, and the initial
height *y*<sub>0</sub> as measured from the bottom of the ball to the
top of the receptor plate (which is at the final height
$y = 0\\,\\meter$), we can rearrange
Eqn. <a href="#eq:M03Kinematic_vertical_02" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_02">[eq:M03Kinematic_vertical_02]</a>
to determine acceleration due to gravity.

$$\\label{eq:M03Kinematic_freefall_g}
  0 = y\_{0} + 0 - \\frac{1}{2}gt^{2}\~\~\~=\>\~\~\~\\frac{2y\_{0}}{t^2} = g$$

<div class="center">

<figure>
<img src="Fall/Experiment03FiguresNEW/M3_Exp1.png"
id="M03_simpleProjectileLauncher_Exp1" style="width:4.9in"
alt="Example of the free fall apparatus used in Exp. 1. Note the release screw will be what you tighten or loosen to hold or release the ball from the release mechanism." />
<figcaption aria-hidden="true">Example of the free fall apparatus used
in Exp. 1. Note the release screw will be what you tighten or loosen to
hold or release the ball from the release mechanism.</figcaption>
</figure>

</div>

<u>**Horizontal Trajectory (Second experiment)**</u>

<div class="center">

<figure>
<img src="Fall/Experiment03FiguresNEW/M3_ExpOptions_quarter_size.png"
id="M03_simpleProjectileLauncher" style="width:5.9in"
alt="Left) Position of launcher for lower height in Experiment 2. Right) Position of launcher for higher height in Experiment 2. Right) Position of launcher for angled launches in Experiment 3 where the ball’s initial position is the same as the higher height position." />
<figcaption aria-hidden="true">Left) Position of launcher for lower
height in Experiment 2. Right) Position of launcher for higher height in
Experiment 2. Right) Position of launcher for angled launches in
Experiment 3 where the ball’s initial position is the same as the higher
height position.</figcaption>
</figure>

</div>

Note: For this experiment as well as the third experiment later on,
while we could use our determined value for gravity, for simplicity, we
will instead use the accepted value of
$g = 9.803\\,\\meter\\per\\second\\squared$ for Fairfield, CT.

In this second experiment, we will **1)** first investigate the
horizontally launched trajectory of the same metal ball used in the
first experiment (launched at 90$\\degree$ relative to *g*, or
0$\\degree$ relative to the floor). Then **2)** we will attempt to
estimate where the ball will land when launched from a different height
and see how accurate we are.

This setup will involve a marble launcher that can slide into a large
holder at different initial heights *y*<sub>0</sub> (and later for the
third experiment, different angles, see
Fig. <a href="#M03_simpleProjectileLauncher" data-reference-type="ref"
data-reference="M03_simpleProjectileLauncher">2</a>). Height
*y*<sub>0</sub> will be measured from the bottom of the ball
(effectively the bottom inside of the launcher’s barrel) to the floor.
Once the ball is released, it will begin a two-dimensional trajectory
accelerated solely by gravity in the *y* direction.

<u>**-1-)**</u> The distance in the *x* direction will be measured from
the center of the ball in the uncocked position (a plum bob can be used
to find the ball’s initial position on the floor) to the average landing
position on the floor after the given number of trials. The ball will
mark up paper with carbon paper; we will circle this scatter shot and
estimate the average position of all trials from the given case, and
then measure the distance with a 1 or 2 meter stick to determine *x*.

After investigating how far the ball travels in the *x* direction from a
given height, we can determine characteristics about the
launcher-and-ball system to estimate how far in the *x* direction we may
expect the ball to travel in the second part of this experiment when we
launch it from a different initial height. To estimate how far the ball
will travel, we can use
Eqn. <a href="#eq:M03horizontalKinematic" data-reference-type="ref"
data-reference="eq:M03horizontalKinematic">[eq:M03horizontalKinematic]</a>
to determine *x*. However, to do so, we will need to for how long and
how fast it was moving (distance traveled = speed × time). Since we know
the initial height *y*<sub>0</sub> of the ball, we can determine the
time *t* it took to fall to the floor in the *y* direction due solely to
gravity *g* by rearranging
Eqn. <a href="#eq:M03Kinematic_vertical_02" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_02">[eq:M03Kinematic_vertical_02]</a>
to solve for *t*, knowing that $v\_{0y} = 0\\,\\meter\\per\\second$ and
treating the floor as $y = 0\\,\\meter$:

$$\\label{eq:M03Kinematic_vertical_time}
  0 = y\_{0} + 0 - \\frac{1}{2}gt^{2}\~\~\~=\>\~\~\~\\sqrt{\\frac{2y\_{0}}{g}} = t$$

Now that we know the time *t* of the trajectory, and treating the
uncocked position as $x\_{0} = 0\\,\\meter$, we can use
Eqn. <a href="#eq:M03horizontalKinematic" data-reference-type="ref"
data-reference="eq:M03horizontalKinematic">[eq:M03horizontalKinematic]</a>
to determine the horizontal velocity *v*<sub>*x*</sub> when released:

$$\\label{eq:M03Kinematic_horizontal_velocity_01}
  x = 0 + v\_{x}t\~\~\~=\>\~\~\~\\frac{x}{t} = v\_{x}$$

<u>**-2-)**</u> For the second part of this experiment, we move the
launcher to the higher $0\\degree$ slot ($\\sim20\\,\\centi\\meter$
higher), and we want to determine how far it will travel in the *x*
direction. This leads us back to
Eqn. <a href="#eq:M03horizontalKinematic" data-reference-type="ref"
data-reference="eq:M03horizontalKinematic">[eq:M03horizontalKinematic]</a>
where we want to solve for *x*<sub>higher height</sub> (where again,
$x\_{0} = 0\\,\\meter$ in the uncocked position):

*x* = 0 + *v*<sub>*x*</sub>*t*    = \>   *x*<sub>higher height</sub> = *v*<sub>*x*</sub>*t*<sub>higher height</sub>

We know the ball’s velocity *v*<sub>*x*</sub>, but we no longer know the
time. However, similar to before, we can solve for
*t*<sub>higher height</sub> by plugging *y*<sub>0,higher height</sub>
into
Eqn. <a href="#eq:M03Kinematic_vertical_time" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_time">[eq:M03Kinematic_vertical_time]</a>:

$$\\label{eq:M03Kinematic_vertical_time_higher_height}
  \\sqrt{\\frac{2y\_{0\\text{,higher height}}}{g}} = t\_{\\text{higher height}}$$

This subsequent value for time *t*<sub>higher height</sub> can be used
in Eqn. <a href="#eq:M03Kinematic_horizontal_velocity_02"
data-reference-type="ref"
data-reference="eq:M03Kinematic_horizontal_velocity_02">[eq:M03Kinematic_horizontal_velocity_02]</a>
to then calculate a theoretical distance
*x*<sub>higher height, theoretical</sub>. We will then launch the ball
from this higher height see how accurate we estimated
*x*<sub>higher height, theoretical</sub>. The experimentally determined
*x*<sub>higher height, experimental</sub> will be measured in the same
way as the first part of this experiment (circling and estimating the
center of the scattershot).

<u>**Angled Trajectory (Third experiment)**</u>

The third part of this experiment is similar to the 2nd part of the
second experiment in that we are staying at the higher height, but now
investigating the trajectories when launched from different angles,
namely, how far in the *x* direction do they reach? The large, launcher
holder is designed to hold the ball at rest (uncocked) in the same
position (height) regardless of angle, so you should be able to use your
previously determined *y*<sub>0,higher height</sub> as your value for
the ball’s initial height (see
Fig. <a href="#M03_simpleProjectileLauncher" data-reference-type="ref"
data-reference="M03_simpleProjectileLauncher">2</a> right).

By launching at an upward angle *θ*, we are now giving some of the
initial velocity to both *x* and *y* directions. Once again, as there is
no acceleration in the *x* direction, we will ultimately use
Eqn. <a href="#eq:M03horizontalKinematic" data-reference-type="ref"
data-reference="eq:M03horizontalKinematic">[eq:M03horizontalKinematic]</a>
to determine *x*<sub>*θ*</sub>. However, we need to know both
*v*<sub>*x**θ*</sub> and *t*<sub>*θ*</sub>. The velocity will merely be
the horizontal component of the launch angle:

*v*<sub>*x**θ*</sub> = *v*<sub>*x*</sub>cos *θ*

<div class="center">

<figure>
<img src="Fall/Experiment03FiguresNEW/M3_Exp3.png"
id="M03_simpleProjectileLauncher_Exp3" style="width:3.9in"
alt="Example of the upward and downward portions you’ll analyze in Experiment 3 for an angled launch." />
<figcaption aria-hidden="true">Example of the upward and downward
portions you’ll analyze in Experiment 3 for an angled
launch.</figcaption>
</figure>

</div>

To solve for the time, however, we can characterize motion in the *y*
direction to determine for how long the ball is in the air. As shown in
Fig. <a href="#M03_simpleProjectileLauncher_Exp3" data-reference-type="ref"
data-reference="M03_simpleProjectileLauncher_Exp3">3</a>, we can find
that total time by breaking the trajectory into parts (i.e.
*t*<sub>*θ*</sub> = *t*<sub>up</sub> + *t*<sub>down</sub>) where
*t*<sub>up</sub> is the time for upward travel to the peak height, and
*t*<sub>down</sub> is the time for downward travel to the floor from
that peak height. **UPWARD PORTION)** Starting with
Eqn. <a href="#eq:M03Kinematic_vertical_01" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_01">[eq:M03Kinematic_vertical_01]</a>,
where we know for the upward travel portion the initial velocity in the
*y* direction is
*v*<sub>0*y*</sub> = *v*<sub>0*y* higher height</sub> = *v*<sub>*x*</sub>sin *θ*
and at the peak of the trajectory (end of the upward travel)
$v\_{y} = v\_{y\\text{peak}} = 0\\,\\meter\\per\\second$, thus:

$$\\label{eq:M03Kinematic_vertical_time_03_v2_pt1}
  v\_{y\\text{ peak}} = v\_{0y\\text{ higher height}} - gt\~\~\~=\>\~\~\~0 = v\_{x}\\sin{\\theta} - gt\_{\\text{up}}\~\~\~=\>\~\~\~\\frac{v\_{x}\\sin{\\theta}}{g} = t\_{\\text{up}}$$

**DOWNWARD PORTION)** Then for the downward travel, we need to first
know how high we travelled during the upward portion (i.e.
*y*<sub>0,higher height</sub> to *y*<sub> peak</sub>) so we can use
Eqn. <a href="#eq:M03Kinematic_vertical_02" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_02">[eq:M03Kinematic_vertical_02]</a>
later to determine the time it took to fall from
*y*<sub> peak</sub> to *y*<sub> floor</sub>. Since we know our initial
height *y*<sub>0</sub> = *y*<sub>0,higher height</sub>, initial velocity
*v*<sub>0</sub> = *v*<sub>0*y* higher height</sub> = *v*<sub>*x*</sub>sin *θ*,
and the time it took to get *t*<sub>up</sub> there from
Eqn. <a href="#eq:M03Kinematic_vertical_time_03_v2_pt1"
data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_time_03_v2_pt1">[eq:M03Kinematic_vertical_time_03_v2_pt1]</a>,
we can use
Eqn. <a href="#eq:M03Kinematic_vertical_02" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_02">[eq:M03Kinematic_vertical_02]</a>
to solve for the final height of the upward travel *y*<sub>peak</sub>:

$$\\label{eq:M03Kinematic_vertical_time_03_v2_pt2}
  y\_{\\text{peak}} = y\_{0\\text{,higher height}} + v\_{x}\\sin{\\theta}t\_{\\text{up}} - \\frac{1}{2}gt\_{\\text{up}}^{2}$$

Now that we know *y*<sub>peak</sub>, we can use
Eqn. <a href="#eq:M03Kinematic_vertical_02" data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_02">[eq:M03Kinematic_vertical_02]</a>
to solve for *t*<sub>*d**o**w**n*</sub>, this time with the final height
$y\_{\\text{floor}} = 0\\,\\meter$, initial height of
*y*<sub>peak</sub>, and the initial velocity
$v\_{y\\text{ peak}} = 0\\,\\meter\\per\\second$.

$$\\label{eq:M03Kinematic_vertical_time_03_v2_pt3}
  y\_{\\text{floor}} = y\_{\\text{peak}} + v\_{y\\text{ peak}} - \\frac{1}{2}gt\_{\\text{down}}^{2}\~\~\~=\>\~\~\~0 = y\_{\\text{peak}} + 0 - \\frac{1}{2}gt\_{\\text{down}}^{2}\~\~\~=\>\~\~\~\\sqrt{\\frac{2y\_{\\text{peak}}}{g}} = t\_{\\text{down}}$$

**HORIZONTAL DISTANCE)** Finally, we have the total time
*t*<sub>*θ*</sub> = *t*<sub>up</sub> + *t*<sub>down</sub> from
Eqns. <a href="#eq:M03Kinematic_vertical_time_03_v2_pt1"
data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_time_03_v2_pt1">[eq:M03Kinematic_vertical_time_03_v2_pt1]</a>
and  <a href="#eq:M03Kinematic_vertical_time_03_v2_pt3"
data-reference-type="ref"
data-reference="eq:M03Kinematic_vertical_time_03_v2_pt3">[eq:M03Kinematic_vertical_time_03_v2_pt3]</a>
and the initial velocity *v*<sub>*x*</sub> from
Eqn. <a href="#eq:M03Kinematic_horizontal_velocity_03"
data-reference-type="ref"
data-reference="eq:M03Kinematic_horizontal_velocity_03">[eq:M03Kinematic_horizontal_velocity_03]</a>
to incorporate into
Eqn. <a href="#eq:M03horizontalKinematic" data-reference-type="ref"
data-reference="eq:M03horizontalKinematic">[eq:M03horizontalKinematic]</a>
to determine the theoretical distance *x*<sub>*θ*</sub> the ball with
travel in the *x* direction for any given angle *θ*:

*x*<sub>*θ*</sub> = *v*<sub>*x*</sub>cos *θ**t*<sub>*θ*</sub>

# Experimental Procedure

## EXPERIMENT 1 – Free Fall / Downward Trajectory

1.  **OVERALL GOALS:**

    -   Investigate projectile motion in one-dimension (*y*).

    -   Conduct 5 trials of the free-fall and determine acceleration due
        to gravity using one-dimensional kinematics.

    -   *POINT TO CONSIDER*: Will this experiment be more or less
        accurate in measuring *g* than the previous lab using gliders on
        a tilted air track?

    -   *NOTE*: There are only 4 setups, please share, and once you’re
        done taking your data, move on to ensure other groups have a
        reasonable chance to use the apparatus.

    -   PASCO TIMER Precision: 0.0001 seconds

2.  Create a data table for this experiment:

    -   Common data section with the accepted value of *g*, the ball
        height *y*<sub>0</sub>, and the ball height’s estimated
        uncertainty *δ**y*.

    -   With **five rows** (1 for each of the 5 free-fall trials). Also
        include additional **rows** for the average *g* value, the ±
        uncertainty in gravity *δ**g*, the magnitude difference compared
        to the accepted *g* *DISCUSSION POINT for later*: How well does
        you average value of *g* ± *δ**g* agree with the accepted value
        of *g*?).

    -   Include **six columns** for

        -   Initial time *t*<sub>initial</sub>

        -   Initial time uncertainty *δ**t*<sub>initial</sub>

        -   Final time *t*<sub>final</sub>

        -   Final time uncertainty *δ**t*<sub>final</sub>

        -   Total elapsed time
            *t* = *t*<sub>final</sub> − *t*<sub>initial</sub>

        -   Total elapsed time uncertainty
            *δ**t* = *t*<sub>final</sub> − *t*<sub>initial</sub>

        -   Calculated *g*

3.  CAPSTONE will be set up with the Free-Fall Adapter which, whenever
    the circuit opens or closes, will record the time that event
    occurred.

4.  Place your metal ball from your marble launcher into the spring
    loaded holder at one of the four setups. You will need to push the
    metal tab in and then hand-tighten the holding/release screw to hold
    the ball in place.

5.  Ensure the receptor pad is beneath the ball such that it hits close
    to the open side.

6.  Measure the height the ball will fall; the initial height
    *y*<sub>0</sub> is measured from the bottom of the ball to the top
    of the receptor plate which has a final height $y = 0\\,\\meter$ if
    you place the meter stick on the receptor pad.

7.  Press Record in CAPSTONE. You can let it run and it’ll continue
    collecting data even when you reset the ball for additional trials;
    or restart for each trial, just be aware of which data points are
    related to your drop.

8.  Unscrew the holding/release screw to allow the ball to fall.

9.  Record your *t*<sub>initial</sub> and *t*<sub>final</sub> times.

10. Repeat the drop for a total of 5 free-fall trials. Determine the
    total elapsed times *t* for each trial.

11. Using
    Eqn. <a href="#eq:M03Kinematic_freefall_g" data-reference-type="ref"
    data-reference="eq:M03Kinematic_freefall_g">[eq:M03Kinematic_freefall_g]</a>,
    calculate the value of *g* for each of your trials (benefit here of
    calculating *g* from each trial: you can more easily notice any
    outlier data).

12. Determine your average *g* from the preceding values.

13. Estimate your uncertainty in *g*, as represented by
    *δ**g* = *g*<sub>test</sub> − *g*, (i.e. how confident \[±\] you are
    in what you measured – e.g. distance, time). Plug in each
    measurements’ uncertainties to make your test value of
    *g*<sub>test</sub> as calculated with
    Eqn. <a href="#eq:M03Kinematic_freefall_g" data-reference-type="ref"
    data-reference="eq:M03Kinematic_freefall_g">[eq:M03Kinematic_freefall_g]</a>
    as big as possible (i.e. larger numerator, smaller denominator).
    Determine *δ**g*.

14. Compare your average *g* to the accepted value of
    $g = 9.803\\,\\meter\\per\\second\\squared$; what is the total
    difference?

15. Does you average *g* ± *δ**g* cover the difference from the accepted
    value and agree, or not?

## Horizontal Trajectory (Second experiment)

1.  **OVERALL GOALS:**

    -   Investigate projectile motion in two-dimensions when launched
        horizontally.

    -   For simplicity and to decrease error propagation, **for the rest
        of lab, assume and use** the accepted value of
        $g = 9.803\\,\\meter\\per\\second\\squared$ for Fairfield, CT
        rather than your previously determined value.

    -   Characterize the trajectory from the marble launcher at initial
        height.

    -   Calculate the theoretical trajectory (distance *x*) for a
        different height; place a bullseye at your expected location and
        compare your experimental landing scattershot to the theoretical
        distance.

    -   Conduct 20 launches for each height; estimate the experimental
        landing scattershot by circling your carbon-paper dots and
        estimating the center of the scattershot.

2.  Create a data table for this experiment:

    -   Common data section with the accepted value of *g*.

    -   Section for the case at a the lower initial height containing:

        -   the ball height *y*<sub>0</sub>

        -   the ball height’s estimated uncertainty *δ**y*<sub>0</sub>

        -   distance *x*

        -   distance uncertainty *δ**x* based on the radius of the
            circle you draw around the scattershot

    -   Additional sections for derived time of the trajectory *t* and
        velocity *v*<sub>*x*</sub>

    -   Additional sections for:

        -   Height of the ball at the higher $0 \\degree$ slot height
            *y*<sub>0,higher height</sub>

        -   Time of the trajectory from a higher height
            *t*<sub>higher height</sub>

        -   Theoretical distance
            *x*<sub>higher height, theoretical</sub> (calculated with
            Eqn. <a href="#eq:M03Kinematic_horizontal_velocity_02"
            data-reference-type="ref"
            data-reference="eq:M03Kinematic_horizontal_velocity_02">[eq:M03Kinematic_horizontal_velocity_02]</a>)

        -   Experimentally measured distance
            *x*<sub>higher height, experimental</sub>

        -   Estimated uncertainty in the experimental distance
            *δ**x*<sub>higher height, experimental</sub> (essentially ±
            the radius of the circle drawn around your scattershot)

        -   Difference (magnitude) between the theoretical and
            experimental *x* distances

3.  Place the marble launcher in the holder in the lower $0\\degree$
    slot (uncocked to represent where the ball will be once the piston
    is no longer accelerating the ball up to speed)

4.  Measure the height the ball will fall; place the metal ball into the
    launcher as the initial height *y*<sub>0</sub> is measured from the
    bottom of the ball to the floor (though the bottom of the inside of
    the barrel can also be used as the bottom of the ball location if
    that is easier to measure).

5.  <span id="M03_launchStepStart" label="M03_launchStepStart"></span>
    Conduct a couple test launches by pulling the piston to the first or
    second notches (whichever position provides the shorter,
    $\\sim 1\\,\\meter$, *x* distance). Take mental note of where the
    ball is generally landing.

6.  Get a piece of paper and tape it in the approximate location, and
    place (no tape needed) a piece of carbon paper on top (no need to
    tape that one) so the ball can mark up the paper when it lands.

7.  Conduct **20 launches** onto the paper/carbon paper.

8.  Put aside the carbon paper and mark the dots with a marker or
    something else that makes it apparent which dots are your data
    points for this height. Draw a rough circle surrounding the
    scattershot and visually estimate the center by drawing a cross hair
    to represent the center of the scatter.

9.  Measure the experimental distance *x* from the center of the ball at
    rest in the barrel (uncocked) to the cross hair center that you drew
    in your scatter shot on the floor. To translate the initial location
    of the ball in the barrel to the floor, you can use a plum bob to
    make a straight line down to the floor, from which you can more
    easily measure *x*

10. <span id="M03_launchStepEnd" label="M03_launchStepEnd"></span> From
    your circle around your scattershot, estimate your uncertainty in
    distance *δ**x*

11. Move the marble launcher to the higher $0 \\degree$ slot and
    remeasure the initial height *y*<sub>0,higher height</sub>

12. Now calculate the theoretical distance
    *x*<sub>higher height, theoretical</sub> using
    Eqns. <a href="#eq:M03Kinematic_vertical_time" data-reference-type="ref"
    data-reference="eq:M03Kinematic_vertical_time">[eq:M03Kinematic_vertical_time]</a>
    –  <a href="#eq:M03Kinematic_vertical_time_higher_height"
    data-reference-type="ref"
    data-reference="eq:M03Kinematic_vertical_time_higher_height">[eq:M03Kinematic_vertical_time_higher_height]</a>

13. Repeat
    steps <a href="#M03_launchStepStart" data-reference-type="ref"
    data-reference="M03_launchStepStart">[M03_launchStepStart]</a> to <a href="#M03_launchStepEnd" data-reference-type="ref"
    data-reference="M03_launchStepEnd">[M03_launchStepEnd]</a> to
    determine experimentally the distance with its uncertainty at the
    higher height (i.e. *x*<sub>higher height, experimental</sub> and
    *δ**x*<sub>higher height, experimental</sub>). **ADDITIONALLY:
    Before any launches from the higher height, draw a bullseye at the
    theoretical distance you expect the balls at the higher height to
    land to visually see how close we get. You can draw both a cross
    hair for the distance and estimate how big the scatter will be (to
    discuss later in
    Sec. <a href="#M3_InterpretationProjectile" data-reference-type="ref"
    data-reference="M3_InterpretationProjectile">3</a>).**

14. Calculate the difference between you theoretical and experimental
    values of *x* at the higher height.

15. DISCUSSION POINT (covered in
    Sec. <a href="#M3_InterpretationProjectile" data-reference-type="ref"
    data-reference="M3_InterpretationProjectile">3</a>): Does your
    experimental distance of the higher height agree with what you
    expected from your theoretical calculation? In other words, does
    *x*<sub>higher height, experimental</sub> ± *δ**x*<sub>higher height, experimental</sub>
    overlap with *x*<sub>higher height, theoretical</sub> (i.e. does
    your uncertainty cover the difference between the experimental and
    theoretical values?)?

## Angled Trajectory (Third experiment)

1.  **OVERALL GOALS:**

    -   Investigate projectile motion in two-dimensions when launched at
        a non-zero angle (for now, we’ll use the 45slot; if labs go well
        this semester, we may add additional angles).

    -   Continue to use the accepted value of
        $g = 9.803\\,\\meter\\per\\second\\squared$ for Fairfield, CT
        rather than your previously determined value.

    -   Calculate the theoretical trajectory (distance *x*) for a
        non-zero angle; place a bullseye at your expected location and
        compare your experimental landing scattershot to the theoretical
        distance.

    -   Compare the theoretical trajectory’s *x* distance to the
        experimentally determined distance.

    -   Conduct 20 launches for each angle; estimate the experimental
        landing scattershot by circling your carbon-paper dots and
        estimating the center of the scattershot, with your uncertainty
        represented by the radius of the drawn circle.

2.  Create a data table for this experiment:

    -   Common data section with the accepted value of *g* and any
        values you will need from previous experiments to determine the
        theoretical distance at a given angled launch *x*<sub>*θ*</sub>
        (Eqns. <a href="#eq:M03Kinematic_horizontal_velocity_03"
        data-reference-type="ref"
        data-reference="eq:M03Kinematic_horizontal_velocity_03">[eq:M03Kinematic_horizontal_velocity_03]</a> to <a href="#eq:M03Kinematic_vertical_time_03_v2_pt4"
        data-reference-type="ref"
        data-reference="eq:M03Kinematic_vertical_time_03_v2_pt4">[eq:M03Kinematic_vertical_time_03_v2_pt4]</a>).

    -   Additional sections for:

        -   Theoretical distance *x*<sub>*θ*, theoretical</sub>
            (calculated with
            Eqn. <a href="#eq:M03Kinematic_vertical_time_03_v2_pt4"
            data-reference-type="ref"
            data-reference="eq:M03Kinematic_vertical_time_03_v2_pt4">[eq:M03Kinematic_vertical_time_03_v2_pt4]</a>)

        -   Experimentally measured distance
            *x*<sub>*θ*, experimental</sub>

        -   Estimated uncertainty in the experimental distance
            *δ**x*<sub>*θ*, *e**x**p**e**r**i**m**e**n**t**a**l*</sub>
            (essentially ± the radius of the circle drawn around your
            scattershot)

        -   Difference (magnitude) between the theoretical and
            experimental *x* distances

3.  Place the marble launcher in the holder in the $45\\degree$ slot

4.  Use your previously measured *y*<sub>0,higher height</sub> as the
    height the ball will fall for any angled launches (e.g.
    *y*<sub>0,higher height</sub> = *y*<sub>*θ*,higher height</sub>).

5.  <span id="M03_launchStepStart_exp3"
    label="M03_launchStepStart_exp3"></span> Calculate the theoretical
    distance *x*<sub>, theoretical</sub> using
    Eqns. <a href="#eq:M03Kinematic_horizontal_velocity_03"
    data-reference-type="ref"
    data-reference="eq:M03Kinematic_horizontal_velocity_03">[eq:M03Kinematic_horizontal_velocity_03]</a> to <a href="#eq:M03Kinematic_vertical_time_03_v2_pt4"
    data-reference-type="ref"
    data-reference="eq:M03Kinematic_vertical_time_03_v2_pt4">[eq:M03Kinematic_vertical_time_03_v2_pt4]</a>

6.  Before any launches from the higher height, tape a paper and draw a
    bullseye at the theoretical distance you expect the balls at the
    given angle to land to visually see how close we get. You can draw
    both a cross hair for the distance and estimate how big the scatter
    will be.

7.  Conduct a few test launches by pulling the piston to the same notch
    you’ve been using in Experiment 2 to be able to use the same exit
    velocity as previously determined

8.  If need be, tape additional paper in the location from the test
    launches. Place (no tape needed) a piece of carbon paper on top (no
    need to tape that one) so the ball can mark up the paper when it
    lands.

9.  Conduct **20 launches** onto the paper/carbon paper.

10. Put aside the carbon paper and mark the dots with a marker or
    something else that makes it apparent which dots are your data
    points for this height. Draw a rough circle surrounding the
    scattershot and visually estimate the center by drawing a cross hair
    to represent the center of the scatter.

11. Measure the experimental distance *x* from the center of the ball at
    rest in the barrel (uncocked) to the cross hair center that you drew
    in your scatter shot on the floor. The initial position of the ball
    in the *x* direction translated to the floor should be the same as
    Experiment 2 (to save you some time). Remeasure if that’s no longer
    the case (e.g. you’ve accidentally moved the launcher holder)

12. From your circle around your scattershot, estimate your uncertainty
    in distance *δ**x*

13. <span id="M03_launchStepEnd_exp3"
    label="M03_launchStepEnd_exp3"></span> Calculate the difference
    between you theoretical and experimental values of *x* at the given
    angle.

14. If there are additional angles assigned, move the marble launcher to
    the respective angle and repeat
    steps <a href="#M03_launchStepStart_exp3" data-reference-type="ref"
    data-reference="M03_launchStepStart_exp3">[M03_launchStepStart_exp3]</a> to <a href="#M03_launchStepEnd_exp3" data-reference-type="ref"
    data-reference="M03_launchStepEnd_exp3">[M03_launchStepEnd_exp3]</a>
    if needed.

15. DISCUSSION POINT (covered in
    Sec. <a href="#M3_InterpretationProjectile" data-reference-type="ref"
    data-reference="M3_InterpretationProjectile">3</a>): Does your
    experimental distance of the given angle(s) agree with what you
    expected from your theoretical calculation(s)? In other words, does
    *x*<sub>*θ*, experimental</sub> ± *δ**x*<sub>*θ*, experimental</sub>
    overlap with *x*<sub>*θ*, theoretical</sub> (i.e. does your
    uncertainty cover the difference between the experimental and
    theoretical values?)?

# Post-Lab Submission — Interpretation of Results

-   Make sure to submit your finalized data table (Excel sheet)

-   What type of system do the kinematic equations represent?

-   Experiment 1:

    -   What are your results (*g* ± *δ**g*), and how do they compare to
        the accepted value in Fairfield, CT?

        -   In other words, for Experiment 1, COMPARE your experimental
            result of *g* to the accepted values. Does *g* ± *δ**g*
            overlap (and therefore agree) with the accepted value?

    -   What are the uncertainties of Experiment 1?

    -   Would a different sized marble change your derived value of *g*?
        Why or why not?

-   Experiment 2:

    -   What were your results for the horizontal trajectories at both
        lower and higher heights?

    -   Does your experimental distance of the higher height agree with
        what you expected from your theoretical calculation?

        -   In other words, does
            *x*<sub>higher height, experimental</sub> ± *δ**x*<sub>higher height, experimental</sub>
            overlap with *x*<sub>higher height, theoretical</sub> (i.e.
            does your uncertainty cover the difference between the
            experimental and theoretical values?)?

    -   What uncertainties might make this difference larger or smaller?

    -   Was your bullseye target accurate to the experimental results?

-   Experiment 3:

    -   What were your results for the trajectories from a non-zero
        angle(s)?

    -   Does your experimental distance agree with what you expected
        from your theoretical calculation?

        -   In other words, does
            *x*<sub>*θ*, experimental</sub> ± *δ**x*<sub>*θ*, experimental</sub>
            overlap with *x*<sub>*θ*, theoretical</sub> (i.e. does your
            uncertainty cover the difference between the experimental
            and theoretical values?)?

    -   What uncertainties might make this difference larger or smaller?

    -   Was your bullseye target accurate to the experimental results?

-   What is the precision of your equipment?

-   What are possible systematic errors for today’s experiments?
