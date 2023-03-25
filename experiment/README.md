### Aim
<p>Write a Program for the generation of basic signals such as unit impulse, unit step, ramp, exponential, sinusoidal and cosine.</p>

### Theory
<p>In this experiment user will generate the basic signals such as unit impulse function, unit step function, exponential function, ramp function and sinusoidal function using the pre-written MATLAB code.</p>
<p>The unit impulse function is mathematically defined as </p><img src = "./images/unit impulse.PNG">
<p>where unity at <i>t=&#964;<sub>0</sub></i> represents the area of impulse function. Since, the width of the impulse function <i>&#916;t&#8594;0</i> , therefore, theoretically impulse function point towards infinity at <i>t=&#964;<sub>0</sub>;</i> and hence the area becomes unity. However, for signal generation through codes width of impulse <i>&#916;</i>cannot be made 0 due to finite step size of time parameter, therefore, generally a triangular pulse of very small width instead of impulse function is plotted.</p>
<p>Similarly, unit step function is defined mathematically as </p> <img src="./images/unit step.PNG">
<p>Therefore, it will take a constant value equals to 1 for t&#62;0 , otherwise 0.</p>
<p>The definition of ramp function is </p>
 <p>                   </p>   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;<b> <i>r(t) &#61; t.u(t)</i></b>
 <br><br>

<p>where, u(t) is defined in the above unit step equation. Therefore, a signal will be generated as a line of unit slope for t>0 and it is 0 for t<0. </p><br>
<p>For exponential signal (e<sup>at</sup> for all &lsquo;<em>t</em>&rsquo;) based on the exponent &lsquo;a&rsquo; either a increasing exponential or a decreasing exponential signal will be plotted.</p>
<p>Sinusoidal signal is having its mathematical form as s(t)=A sin⁡(2πft+φ)</p>
<p>So, based on the amplitude and frequency parameters a sinusoid of various amplitude and frequency will be generated. The plot will be obtained for φ=0  .</p>

### Procedure
<p>To start the experiment user have to open the simulator and then select the desired signal to be generated from the drop-down menu. Once the user select the signal then a corresponding MATLAB code will open in command window.<br> After that user have to press the start button provided at the bottom of code window and then click on to the next for line-by-line execution of code.<br> Based on the selected signal, user may have to enter the various parameter in command window for which a slider will be opened. The slider will have a pre-defined range for the particular parameter to be entered.<br> After selecting a particular value on the slider, click on ok button. As the codes executes line-by-line the user can see the variables created in the Workspace window.<br>  Finally, after execution of entire code, time-domain waveform of selected signal will be plotted in the Plot window. User either reset the program to execute the same code for different value of parameters or select the different signal from drop-down menu to generate different signals.  </p>

### Pre Test
1 An impulse δ(t-2) will have<BR>
A.  An impulse of magnitude of 2 V at t = 0<BR>
B.  impulse of unit magnitude at t = -2<BR>
C.  An impulse of unit magnitude at t = 0<BR>
D.  An impulse of unit magnitude at t = 2<BR>
Ans: D<BR><br>
2 To get the decreasing exponential function (e^at) the exponent &lsquo;a&rsquo; should be<BR>
A. <em>a</em>&lt;1<BR>
B. <em>a</em>&gt;1<BR>
C. <em>a</em>&lt;0<BR>
D. -1&lt;<em> a</em>&lt;1</li><BR>
Ans: C<BR> <br>
3The slope of the function defined by y=2t is<BR>
A. Cannot determine<BR>
B. 2<BR>
C. -2<BR>
D. 2t<BR>
Ans: B<BR><br>
4For sinusoidal signal time period (T) and frequency (f) are related as<BR>
A. f &times;T= 1<BR>
B. f = T<BR>
C. f = 1/T<sup>2</sup><BR>
D. None of the above<BR>
Ans: A<BR>

<p>In this section we keep some questions(MCQ based generally) to test student&rsquo;s&nbsp; prior knowledge</p>

### Post Test
1 Which MATLAB command is used to take the input from console-<br>
A. input<br>
B. disp<br>
C. enter<br>
D. console<br>
Ans: A<br><BR>

2 Which parameters decide the length of time vector?<br>
A.	Upper limit<br>
B.	Lower and upper limit<br>
C.	Lower and upper limit, and step size<br>
D.	Step size<br>
Ans: C<br><br>
3.	If a sinusoidal wave completes 5 cycles in 100 msec, then the frequency of wave is?<br>
A.	100 Hz<br>
B.	50 Hz<br>
C.	0.05 Hz<br>
D.	500 Hz<br>
Ans: B<br><br>
4. An unit step function u(t) will have its magnitude<br>
A.	Equal to 1 for all ‘t’<br>
B.	Equal to 1 for ‘t>1’<br>
C.	Equal to 1 for ‘t>0’<br>
D.	Equal to 1 for ‘t<0’<br>
Ans: C<br><br>

### References
[1]. Alan V. Oppenheim, Alan S. Willsky, and S. Hamid Nawab, “Signals and Systems,” Prentice Hall, 2nd Edition, 1996.<br>
[2]. B. P. Lathi, “Principles of Linear Systems and Signals,” Oxford University Press, 2nd Edition (International Version), 2009.<br>
[3]. S. Salivahanan, C Gnanapriya "DIGITAL SIGNAL PROCESSING," Tata McGraw-Hill, 2nd Edition, 1996.<br>
[4]. John G. Proakis, Dimitris G. Manolakis "Digital Signal Processing," Pearson, 4th Edition, 2007.
