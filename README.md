# ORLA-Star
The webpage for Project: ORLA\*: Mobile Manipulator-Based Object Rearrangement with Lazy A\*. Source Codes and Paper Will be Available Soon.

## Problem Introduction
<p align="center">
<img src="https://github.com/gaokai15/ORLA-Star/assets/53358252/fac6d8f3-1cd4-40ca-bf87-ca27ffdeea4e" width="500" >
</p>
In this paper, we investigate the problem of Mobile Robot Tabletop Rearrangement (MoTaR), where a robot with mobile base is tasked to move objects from an initial arrangement to a desired goal arrangement on a confined tabletop.
<video width="400" height="400" autoplay muted loop>
<source src="https://github.com/gaokai15/ORLA-Star/assets/53358252/18d77ed2-d65b-42d7-9ce7-583f482a41b0" type="video/mp4"> 
<p>Your browser does not support the video tag.</p>
</video>

We study two different scenarios of MoTaR:
<table>
  <tr>
    <td></td>
    <td>
      <strong>EE (End-Effector) Scenario</strong>
    </td>
    <td>
      <strong>MB (Mobile Base) Scenario</strong>
    </td>
  </tr>
  <tr>
    <td>Examples</td>
    <td>
      <img src="![small_scene](https://github.com/gaokai15/ORLA-Star/assets/53358252/70f5f107-7ebf-4571-8e91-7efc1c6f4740)" height="300" >
    </td>
    <td>
      <img src="![large_scene](https://github.com/gaokai15/ORLA-Star/assets/53358252/4d49917d-9f6f-44ed-b336-ca0ea81c7d63)" height="300" >
    </td>
  </tr>
  <tr>
    <td>Features</td>
    <td>
      Rearrangement on a small table, where the robot can stay at a fixed position.
    </td>
    <td>
      Rearrangement on a large table, where the robot needs to travel around for pick and places.
    </td>
  </tr>
  <tr>
    <td>Considered Costs</td>
    <td>
      <strong>End-effector (EE)</strong> travel distance + # pick-n-places
    </td>
    <td>
      <strong>Mobile base (MB)</strong> travel distance + # pick-n-places
    </td>
  </tr>
  </table>
