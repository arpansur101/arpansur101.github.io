---
layout: page
title: Design of a Bangla Calendar Clock
description: Undergraduate level
img: assets/img/B_clock.png
importance: 6
category: Academic Projects
related_publications: true
---


In this project, we have developed a calender clock that displays time (in a 12 hour format), part of the day, date in Bangla language. We used Dot Led Matrix arrays as the display of our calendar clock. We used ESP32 microprocessor as our main controlling unit and RTC module for real time clock tracking. Our clock supports 3 diffrent calender format (Gregorian, Bangla and Hizri) with periodic **internet time synchronization** from pool.ntp.org website.  As a result, our project is less vulnerable to time lagging due to RTC failure. The top part of display shows the time while bottom part shows the date in scrolling motion.


</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/B_clock.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Snapshot of our calender clock.
</div>



The [working demonstration][DEMO] and [video presentation][PRES] is hyperlinked here.



[DEMO]:https://www.youtube.com/watch?v=NF0Ag7Rxupc
[PRES]:https://www.youtube.com/watch?v=SqKxKtwfgTs