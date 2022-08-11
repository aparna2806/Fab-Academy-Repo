#week-10 & week13
<h5> April 5 </h5>
<h3> Input and Output Devices </h3>
<h3> Task </h3>
Allowing communication between two components on a pcb or breadbord or rasberry pi. We have to make a circuit where there is back and forth information transfer about the state of the button (digital) the potentiometer(analog) It is time to fabricate it ( finish the design - mill it - solder it).

<h3>Milling Process:</h3>
<li>The first time when we cut Dafni was around to help. But we didn't know that the image was horizontal and we placed the plate vertically. For this reason, we had to repeat it.</li>
<li>We cross checked again if all our images were of the same length and width when we convereted them in imkscape.</li>
<h3>Learnings:</h3>
<li>The section is aimed at INPUTS (sensors) and for OUTPUTS (motors, LEDs)</li>
<li>We touched upon the basics of electronics such as amperage, voltage and current.</li>
<li>We saw different kinds of motors we can find (DC, steppers and MOSFETs, servomotors...), then LEDs, piezo and some others.
<h3>Process</h3>
<li>Borka and I teamed up again as we decided to learn electronics together. Jeremy was super helpful when we had silliest of the doubts</p>
<li>We wanted to make something simple as we lost touch with arduino and the basics of it (last we did was during tech beyond myth class).</li>
<li>We pulled out potentiometer and led from the kit we received. Later on, some resistors, jumper wires and huzzah32 adafruit.</li>
<li>Making connections was fairly easy. But we were thinking of how to make them talk if they are on two different pcb or breadboard.</li>
<li>Bluetooth could be one option. But we ran into multiple troubles trying to achieve that. So we took a step back.
<li>After some time, we got to know that there is TX RX connection system also that could be explored if we want to pass on information from one board to another.</li>
<li>Working with endmill was a little tricky. I didn't know how to tighten and loosen it at the start.</li>
<li>Finally, we wrote code for declaring the components to the pin they are connected to and then initialising it.</li>

<li>We did a small project which helps us to get familiar with this topic and learn the basics for further development, so I designed a PCB board for a potentiometer output, which controls the LED brightness.</li>

<li>Trying to understand how to send messages through RX and TX: </li>
<p align="center">
<img title="miro" alt="brainstorm" src="/images/11.png" width="560"/>
<li>Our Arduino code: </li>
<p align="center">
<img title="miro" alt="brainstorm" src="/images/12.png" width="560"/>
<p align="center">
<img title="miro" alt="brainstorm" src="/images/28.png" width="560"/>
<p align="center">
<li>Video where Borka and I are changing the brightness of LED with a potentiometer that's on a different board can be found here - https://drive.google.com/file/d/1hSKlAS_nKLKWMcwf_82Jps-esQRxoBUt/view?usp=sharing </li>
