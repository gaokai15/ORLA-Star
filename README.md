
This is the project webpage of ORLA\*: Mobile Manipulator-Based Object Rearrangement with Lazy A\*. Source Codes and Paper Will be Available Soon.

## Problem Introduction
<p align="center">
<img src="https://github.com/gaokai15/ORLA-Star/assets/53358252/fac6d8f3-1cd4-40ca-bf87-ca27ffdeea4e" width="500" >
</p>
In this paper, we investigate the problem of Mobile Robot Tabletop Rearrangement (MoTaR), where a robot with a mobile base is tasked to move objects from an initial arrangement to a desired goal arrangement on a confined tabletop.

<p align="center">
<video width="400" height="400" autoplay muted loop>
<source src="https://github.com/gaokai15/ORLA-Star/assets/53358252/18d77ed2-d65b-42d7-9ce7-583f482a41b0" type="video/mp4"> 
</video>
</p>

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
    <td>
      <p align="center">
      Examples
      </p>
    </td>
    <td>
      <p align="center">
      <img src="https://github.com/gaokai15/ORLA-Star/assets/53358252/70f5f107-7ebf-4571-8e91-7efc1c6f4740" height="200" width=auto>
      </p>
    </td>
    <td>
      <p align="center">
      <img src="https://github.com/gaokai15/ORLA-Star/assets/53358252/4d49917d-9f6f-44ed-b336-ca0ea81c7d63" height="200" width=auto>
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p align="center">
      Features
      </p>
    </td>
    <td>
      Rearrangement on a small table, where the robot can stay at a fixed position.
    </td>
    <td>
      Rearrangement on a large table, where the robot needs to travel around for pick and places.
    </td>
  </tr>
  <tr>
    <td>
      <p align="center">
      Considered Costs
      </p>
    </td>
    <td>
      <strong>End-effector (EE)</strong> travel distance + # pick-n-places
    </td>
    <td>
      <strong>Mobile base (MB)</strong> travel distance + # pick-n-places
    </td>
  </tr>
  </table>

## Highlights and Contributions
**[Studied Problem]** We seek time-optimal solutions to **Mobile Robot Tabletop Rearrangement (MoTaR)**.

**[A\* with Lazy Buffer Allocation]** We propose **Object Rearrangement with Lazy A\* (ORLA\*)**, which employs the idea of lazy buffer allocation into the A\* framework to search for optimal rearrangement plans minimizing the cost function.

**[Pose Stability Estimation]** To estimate the feasibility of a buffer pose, especially when we want to temporarily place an object on top of others, we propose a learning model, **StabilNet**.



  
