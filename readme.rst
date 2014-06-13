
Bicycle Dynamo Measurements
===========================

I've been doing a lot of research and work toward developing a solid
way of keeping plugged-in while away from home, and have now acquired
a pretty substantial quantity of electricity-producing devices, and I'd
like to see what the differences are between each device.

Until now, I've been relying upon an `AXA HR Traction`_ coupled with a
`Lightcharge`_ for producing DC power (via USB) while touring, but
wanting to do a little more touring, I've began the process of upgrading
to instead use a `Shimano Alfine Dynamo Hub (DH-S501)`_ coupled with a
`B&M E-WERK`_.

Equipment
---------

For producing AC current:

* `AXA HR Traction`_
* `Shimano Alfine Dynamo Hub (DH-S501)`_

For converting the AC current into DC:

* `Lightcharge`_
* `B&M E-WERK`_

Experiments
-----------

Tuesday, 10 June
~~~~~~~~~~~~~~~~

* Measured various devices connected to both the B&M E-WERK and the
  Lightcharge using the AXA HR Traction as a power source.

  * As expected, the Lightcharge is current limited at 250mA.
  * Unfortunately, I wasn't able to get more than 180mA out of the
    E-WERK, and I'm not precisely sure why.

* In an attempt at isolating what might be causing the E-WERK to produce
  less current than I had expected -- I had thought maybe it might be
  able to produce a full amp if I pedaled hard enough -- I recruited TJ
  to use his Oscilliscope to make a few observations regarding both the
  AC power source and each of the DC power converter outputs.

  * The Dynamo itself produces a square-like wave, and as I pedal
    faster, the frequency increases.
  * The Ligtcharge produces 5v almost instantaneously when I begin
    pedaling, and the current dissipates immediately.
  * The E-WERK produces 5v almost instantaneously, too, when I begin
    pedaling, but the current takes quite a while to dissipate.

Further Research
++++++++++++++++

* In an attempt at getting an idea of how much current I will be able to
  expect to draw from the E-WERK, TJ has suggested that we eliminate the
  dynamo from consideration, and instead utilize his function generator
  to produce a predictable power source.
* He has also suggested that we may be able to calculate the maximum
  theoretical amperage by attaching a "load box" to the dynamo.


.. _AXA HR Traction: http://www.axa-stenman.com/en/bicycle-components/lighting/dynamos/hr-traction/
.. _Lightcharge: http://www.bike2power.com/lightcharge-bicycle-hub-usb-charger.html
.. _B&M E-WERK: http://www.peterwhitecycles.com/ewerk.asp
.. _Shimano Alfine Dynamo Hub (DH-S501): http://bike.shimano.com.sg/publish/content/global_cycle/en/sg/index/products/city___comfort_bike/alfine/product.-code-DH-S501.-type-..html
