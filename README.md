# Load-Test-of-a-DC-Series-Motor
<!-- wp:paragraph -->
<p><strong>Equipment/Software:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true,"type":"1"} -->
<ol type="1"><li>MATLAB</li></ol>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p><strong>Lab Experiment</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Following Circuit is simulated in MATLAB.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":233,"width":777,"height":315,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large is-resized"><img src="https://electronicinstruction.files.wordpress.com/2021/04/image.png?w=601" alt="" class="wp-image-233" width="777" height="315"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>First of all, 160V Armature Voltage applied with 5% load, that gives speed of 1340 rpm. Then armature voltage increases and set at voltage at which speed equal to the rated speed.<br>In this case, the armature voltage set to 181.5V that gives 1500rpom speed that is equal to rated speed.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Then Load is increases from 5% to 75% and corresponding speed and armature current is measured.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":235,"width":786,"height":415,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large is-resized"><img src="https://electronicinstruction.files.wordpress.com/2021/04/image-1.png?w=614" alt="" class="wp-image-235" width="786" height="415"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p><strong>Graphs</strong></p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":236,"width":777,"height":454,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large is-resized"><img src="https://electronicinstruction.files.wordpress.com/2021/04/image-2.png?w=602" alt="" class="wp-image-236" width="777" height="454"/></figure>
<!-- /wp:image -->

<!-- wp:image {"id":238,"width":779,"height":459,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large is-resized"><img src="https://electronicinstruction.files.wordpress.com/2021/04/image-3.png?w=599" alt="" class="wp-image-238" width="779" height="459"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p><strong>Comments:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>What are the applications of series motor? (Mention at least five applications)</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>DC series motors are used where high starting torque required. These motors are only used where the variation of speed is possible. series motors are not suitable for constant speed applications.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>DC series motor is used in a vacuum cleaner, traction systems, sewing machines, cranes, air compressors etc.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Is it necessary to maintain the constant input voltage while performing load test?</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Yes, it is necessary to maintain the constant input voltage because it also changes the speed that cause interruption in measuring the speed by change load.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Can we run DC series motor at no load? If not, Why?</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>When the motor is connected across the supply mains without load, then it will draw a small current from supply mains. So now as low current will flow through the field winding as well as armature winding (as it is series motor) so main flux produced will be lesser, as before saturation point current is directly proportional to flux. So as main flux is lower, speed will tend to increase. As speed increases, back ems also increases and thus current drawn from the supply will become more and more lower and thus main flux will also become more and more lower and thus speed will tend to increase more and more and this continues till armature of motor has attained speed which is so high that due to centrifugal forces set up in the rotating parts damages armature.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>What is the important precaution in this experiment?</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>There should be some load connected to the machine.</li><li>The load shouldn’t be greater than 90% of the rated TL.</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p><strong>Is series motor a constant speed motor?</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>No, series motor is not a constant speed motor. Series motor speed highly depends upon mechanical load on it.<br>When load increases, motor armature draws more current. Same current flows through field to generate field flux. Motor speed is inversely proportional to the field flux hence as armature current increases, speed decreases.<br>Connecting field in series gives series motor an interesting characteristic i.e., as load increases speed decreases but proportionally torque increases. So, more load results more torque. This is the reason series motor is used where huge starting torque is require for e.g., ‘Starter Motor’ of the car.<br>Because of same characteristic, at no load, speed of series motor can become dangerously high to rip it apart by centrifugal force. Hence series motor should never be started on no load.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Why speed of a series motor decrease so drastically with load?</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>It is normal for a D.C. series motor to decrease in speed with increasing load. It is just like a moving vehicle which decreases its acceleration when its load increases. The more load you put in the machine the more energy it will consume. Another reason is the back emf produced.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>A motor has coils turning inside magnetic fields, and a coil turning inside a magnetic field induces an emf. This emf, known as the back emf, acts against the applied voltage that's causing the motor to spin in the first place, and reduces the current flowing through the coils of the motor.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>On higher loading of DC series motor i.e above 90%. There is reverse relation between speed and loading of motor. Explain the reason.</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>At High load Series motor behave as a generator that causes the speed of motor to increase.</p>
<!-- /wp:paragraph -->
