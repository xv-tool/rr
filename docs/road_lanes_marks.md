# Road lanes, marks

* After changing to white broken lanes
* Select `lane Marking Tool` -> Select center lane line -> 
* From `assets/Markings/`  
* select and drag `FreewayDashedSingleWhite.rrlms` to the center lane line.
* Saved to xodr, got the diff
* Observation
  * xml tag of `roadMark` is updated
  * roadMark `type` is change to `broken` from `solid solid`
  * roadMark `color` is change to `white` from `yellow`

  ```xml
  <center>
    <lane id="0" type="none" level="false">
      <roadMark sOffset="0.0000000000000000e+00" type="broken" width="1.2500000000000000e-01" material="standard" weight="standard" color="white" laneChange="none">
        <type name="" width="1.2500000000000000e-01">
          <line length="3.6600000858306885e+00" space="1.0979999542236328e+01" width="1.2500000000000000e-01" sOffset="0.0000000000000000e+00" tOffset="0.0000000000000000e+00"/>
        </type>
      </roadMark>
      <userData code="vectorLane"/>
    </lane>
  </center>
  ```
  * Previous
  ```xml
  <center>
    <lane id="0" type="none" level="false">
      <roadMark sOffset="0.0000000000000000e+00" type="solid solid" width="1.2500000000000000e-01" material="standard" weight="standard" color="yellow" laneChange="none">
        <type name="" width="1.2500000000000000e-01">
          <line length="1.4224358364753982e+02" space="0.0000000000000000e+00" width="1.2500000000000000e-01" sOffset="0.0000000000000000e+00" tOffset="-6.2500000000000000e-02"/>
          <line length="1.4224358364753982e+02" space="0.0000000000000000e+00" width="1.2500000000000000e-01" sOffset="0.0000000000000000e+00" tOffset="6.2500000000000000e-02"/>
        </type>
      </roadMark>
      <userData code="vectorLane"/>
    </lane>
  </center>
  ```
