<p>In this experiment user will generate the basic signals such as unit impulse function, unit step function, exponential function, ramp function and sinusoidal function using the pre-written MATLAB code.</p><br>
<p>The unit impulse function is mathematically defined as </p><p><img src="unit impulse.png"></p>
<p>where unity at <i>t=&#964;<sub>0</sub></i> represents the area of impulse function. Since, the width of the impulse function <i>&#916;t&#8594;0</i> , therefore, theoretically impulse function point towards infinity at <i>t=&#964;<sub>0</sub>;</i> and hence the area becomes unity. However, for signal generation through codes width of impulse <i>&#916;</i>cannot be made 0 due to finite step size of time parameter, therefore, generally a triangular pulse of very small width instead of impulse function is plotted.</p>
<p>Similarly, unit step function is defined mathematically as </p> <img src = "unit step.png">
<p>Therefore, it will take a constant value equals to 1 for t&#62;0 , otherwise 0.</p><br>
<p>The definition of ramp function is </p>
 <p>                   </p>     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;<b> <i>r(t) &#61; t.u(t)</i></b>
 <br><br>


<p>where, u(t) is defined in the above unit step equation. Therefore, a signal will be generated as a line of unit slope for t>0 and it is 0 for t<0. </p><br>
<p>For exponential signal (e<sup>at</sup> for all &lsquo;<em>t</em>&rsquo;) based on the exponent &lsquo;a&rsquo; either a increasing exponential or a decreasing exponential signal will be plotted.</p>
<p>Sinusoidal signal is having its mathematical form as s(t)=A sin (2πft+fi)</p><br>
<p>So, based on the amplitude and frequency parameters a sinusoid of various amplitude and frequency will be generated. The plot will be obtained for φ=0  .</p>
