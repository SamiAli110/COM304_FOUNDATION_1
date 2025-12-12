 
[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [IT Proposals](../proposals/README.md) 
 
# Council Proposal 4

## Explanation of this proposal
This proposal recommends deploying Raspberry Pi devices as Internet of Things, also known as IoT sensors, to count the number of visitors entering and exiting the council's libraries and museums. People counting supports several operational needs, including capacity monitoring, safety compliance, staffing decisions, and analysing peak visitor times. At this moment in time, many councils rely on manual counting, outdated hardware, or estimation. Using IoT technology would automate this process, provide accurate real data, and reduce staff workload.

A Raspberry Pi is a small, affordable computer capable of connecting to sensors such as infrared beams, ultrasonic distance sensors, or computer vision cameras. When installed at the entrances and exits of the council building, these devices can detect movement, log entries and exits, and securely send the data back to the council's central systems. This becomes a part of a wider "smart building" strategy that supports data-driven decision-making.

Key benefits for the council are:
1. Real-time occupancy tracking for safety and crowd management
2. Accurate visitor statistics to improve service planning
3. Automated data collection without requiring staff intervention
4. Scalability, since Raspberry Pis are inexpensive and easy to deploy
5. Integration with dashboards or analytics systems for reporting
This solution aligns with modern public sector digital transformation strategies, where IoT devices are increasingly used for building management, environmental monitoring, and improving operational efficiency.


## Technologies and research relevant to this proposal
*Which class sessions and personal research refer to technology in this proposal? Link to examples.*
IoT devices are part of a distributed network of small computing units connected to sensors. During the study for this proposal, which was  conducted, the findings were how IoT devices collect and transmit data, the role of edge computing sensor types (infrared, break beam, PIR, ultrasonic), network connectivity options, which are Wifi, Bluetooth, Ethernet, and data formats such as JSON or MQTT. This provides us with the foundation for how the Raspberry Pi operates as an automated counting sensor.

During the practical sessions with Raspberry Pi introduced key skills were introduced which are directly relevant to this proposal: installing and configuring operating systems, connecting networks, installing services such as Apache, running Python scripts and background services, and configuring GPIO pins for sensor inputs. This means Raspberry Pi acts as the "brain" of the IoT system, which allows sensors to interact with the council's network. 

IoT devices rely heavily on networking to transmit data. Key networking concepts include:
1. IP addresses for IoT devices
2. DHCP and static addressing
3. WIFI configuration
4. Firewalls to restrict device access
5. Sending data to central servers
This session supports the understanding of Raspberry Pi and how they will communicate with council systems. However, IoT devices can be really vulnerable if not properly secured. A way around these limitations is securing SSH access, limiting network permissions, and encrypting data transmission.



(https://learn.microsoft.com/en-us/azure/iot/iot-introduction)(https://www.ibm.com/think/topics/internet-of-things)
## Initial Analysis of the Proposal
Using Raspberry Pi as IoT people counters is cost-effective, scalable, and practical. It reduces manual counting and provides accurate data for operational planning. However, the council must consider sensor accuracy, network reliability, device security, and maintenance requirements. A pilot deployment would help determine the best sensor type and placement.
### SWOT Analysis
*You can use html tables in markdown*
 <table>
  <tr>
    <th>Strength</th>
    <th>Weakness</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Low cost hardware with high flexibility </li>
        <li>Automated real time vistor counting</li>
        <li>Easy integration with council data systems</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Requires reliable WiFi or network access</li>
        <li>Sensors may miscount if poorly positioned</li>
        <li>Ongoing updates and maintenance needed</li>
      </ol>
    </td>
  </tr>
  <tr>
    <th>Opportunity</th>
    <th>Threat</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Supports smart building initatives</li>
        <li>Enables long-term data analysis for service planning</li>
        <li>Can expand into environmental or security monitoring</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Cyber attacks targeting IoT/li>
        <li>Hardware faults or power issues may disrupt data collection</li>
        <li>Public tampering or vandalism risks</li>
      </ol> 
    </td>
  </tr>
</table> 

### PEST Analysis
*You can use html tables in markdown*

 <table>
  <tr>
    <th>Political</th>
    <th>Economic</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Supports modern public sector digital transformation policies </li>
        <li>Improves monitoring for health and safety regulations</li>
        <li>Enables evidence-based decision making for funding</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Low cost implementation compared to commercial systems</li>
        <li>Saves staffing resources long term</li>
        <li>initial setup requires purchasing sensors and devices.</li>
      </ol> 
    </td>
  </tr>
  <tr>
    <th>Social</th>
    <th>Technological</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Improves visitor experiences through better space management</li>
        <li>Supports accessible, well-managed public environments </li>
        <li>Reduces manual counting tasks for staff</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Uses modern IoT technologies</li>
        <li>Scales easily across multiple buildings</li>
        <li>Integrates with cloud dashboards and analytics tools</li>
      </ol> 
    </td>
  </tr>
</table> 

## Questions to ask about the proposal
*Without knowing how exactly the council will implement this proposal, what questions should be raised?*

* question 1
Will data be stored locally, on the council server, or in the cloud?
* question 2
How often will devices require updates and maintenance?
## Evaluation of the proposal
*Provide a brief evaluation based on what you know*

Using Raspberry Pi as IoT counters is a practical and modern approach that supports efficient library and museum management. An advantage is that it offers low-cost implementation, real-time data, and integration with digital systems. While factors such as sensor accuracy, device security, and maintenance must be considered, the long-term benefits to data collection and service planning make this a strong and valuable proposal for the council.
