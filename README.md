# PID-controller
<h3>PID controller for a 1st order system</h3>
<p>

<P>Trnasfer Function(H(S)) =           0.3</P>
<P>                                  ------------   </P>
 <P>                                  0.3 + S0.04</P>
                                
Input x(t) = u(t)  
X(S)  = 1/S

Y(S) = H(S)X(S)
Y(S) =  0.3/(0.3+0.04S)S

y(t) = [1-exp(-7.5)t]u(t)

<img src="Open loop model.PNG" alt="Open loop model">
<img src="OPEN LOOP.png" alt="Open loop response">
Time constant T =  0.04/0.3 = 0.133s

<img src="closed loop model.PNG" alt="closed loop model">
<img src="PID model.PNG" alt="PID loop model">
Kp = 40
KI = 50
KD = 0.01
<img src="PID.png" alt="CLOSED LOOP PID RESPONSE">

</p>

