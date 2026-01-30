# Beyond the Dashboard: A Collaborative UI Framework for Autonomous Systems Engineering and Design Research

## Abstract

Developing robust autonomous driving systems requires the iterative evaluation of complex AI algorithms, a process fundamentally hampered by a persistent workflow gap between engineering, research, and design teams. Engineers struggle with high cognitive load during in-field data collection, while designers lack access to the live data and algorithm parameters needed to create and validate meaningful end-user human-machine interface (HMI) concepts. To bridge this critical gap, this paper presents a comprehensive case study on the development of an ``Engineering-UI'', a flexible, web-based framework created through a structured, multi-method collaborative design process involving academic institutions, two large original equipment manufacturers (OEMs), and a UX design agency. The Engineering-UI is architected to serve two critical, integrated functions: first, it provides engineers with intuitive, touch-based controls for in-field data collection, real-time algorithm evaluation, and system parameterization. Second, it acts as a powerful backend for design researchers, enabling the rapid deployment and transparent testing of diverse end-user UI concepts using live system data. We detail the iterative development of this framework and validate its flexibility across two distinct research platforms types: two camera and LiDAR equipped vehicles with vast sensor suites and a minimalist sensor-equipped bicycle with three sensors. We conclude by distilling a set of critical, actionable lessons learned from the real-world integration process, focusing on the friction of parallel development, the challenges of live-data performance, and the competing requirements of design and engineering. This work offers a practical model for effective interdisciplinary development. The source code will be made publicly available when the paper is published.

<table width="100%">
<td colspan="3" align="center">HMI in different settings:</td></tr>
  <tr>
    <td align="center">
      <img src="./docs/images/frame_sensors.png" alt="live-view with sensor warnings" />
      <br />
      <em>Live-view with sensor warnings</em>
    </td>
    <td align="center">
      <img src="./docs/images/frame_recording.png" alt="Basic recording setup" />
      <br />
      <em>Basic recording setup</em>
    </td>
    <td align="center">
      <img src="./docs/images/frame_flags.png" alt="flags with timestamp" />
      <br />
      <em>Flags with timestamp</em>
    </td>
  </tr>
  <tr>
  
</table>
