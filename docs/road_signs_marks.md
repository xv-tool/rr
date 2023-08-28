
# Road signs, lights

* New `objects` tag add and name as `StopSign`.
* NOTE: object has now id=1 and thus next road id is change to 2, i.e. road id=2
* Respectively other object ids are incremented.
```xml
    </lanes>
    <objects>
        <object id="1" name="StopSign" s="1.3216497477178834e+02" t="-5.4112584968920032e+00" zOffset="1.5240478515625000e-01" hdg="-1.5778968706834358e+00" roll="0.0000000000000000e+00" pitch="0.0000000000000000e+00" orientation="-" type="none" height="0.0000000000000000e+00" width="0.0000000000000000e+00" length="0.0000000000000000e+00" validLength="0.0000000000000000e+00" dynamic="no"/>
    </objects>
</road>
<!-- previous road above -->
<!-- New road started -->
<road name="OriginReferenceRoad" length="1.0000000000000000e+02" id="2" junction="-1">

```
* No `objects` tag and thus no `stopsign`
* Note the next road id here is id=1
```xml
    </lanes>
</road>
    <!-- previous road above -->
    <!-- New road started -->
<road name="OriginReferenceRoad" length="1.0000000000000000e+02" id="1" junction="-1">
  ...
</road>
```