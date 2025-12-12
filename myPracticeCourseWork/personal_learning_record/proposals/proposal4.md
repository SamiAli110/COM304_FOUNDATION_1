 
[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [IT Proposals](../proposals/README.md) 
 
# Council Proposal 2

## Explanation of this proposal
This proposal recommends transitioning the council's on-site software system, which is currently hosted on physical servers in the local server room, into a secure cloud-based environment. Traditional on-premises servers require ongoing maintenance, physical space, cooling, and routine hardware replacement. Which, in the long run, can become costly. These systems tend to age; they become increasingly vulnerable to failures, power loss, along performance issues, all of which can disrupt essential public services.

Cloud computing offers a modern alternative by hosting applications, databases, and storage all on remote servers, which are managed by specialist cloud providers, for example, Microsoft Azure, AWS, and Google Cloud. These platforms provide availability, redundancy across multiple data centres, automatic backups, and strong cybersecurity protections.

The benefits of migrating the council's system into the cloud are :
1. Improve reliability and service uptime
2. Reduce physical hardware costs
3. Strengthen disaster recovery
4. Supports recovery in case of disaster
5. Flexible and hybrid working
6. Allow staff to access the system remotely from approved devices
7. Reduce reliance on ageing server room


Cloud systems also provide scalable computing power, meaning the council is only charged for what is being used and gives them the ability to expand or reduce capacity as needed.

This proposal aligns with the UK government's "Cloud First" policy, which encourages public sector organisations to adopt cloud solutions where appropriate.

## Technologies and research relevant to this proposal
*Which class sessions and personal research refer to technology in this proposal? Link to examples.*

Cloud computing, which was covered and introduced in session 10. Cloud concepts such as virtualisation, remote storage, and cloud service models. These ideas help us understand how the system will run on a remote infrastructure rather than on local hardware. 

Another session that this links to is Session 8 OS, also known as Operating Systems. Virtual machines used in cloud platforms rely on the same OS principles studied in session 8, including process management, memory control, file systems, and hardware abstraction.

Networking fundamentals are covered in sessions 4 and 5. Network reliability is essential for cloud usage. The networking sessions covered IP addressing, routing and DNS, Ports and protocols, authentication, and firewall rules. All of these are incredibly crucial when connecting on-site devices to cloud-hosted services.

Cybersecurity is also really important when considering this proposal, as cloud migration requires strong security measures, including encryption, multi-factor authentication (2FA), identity management, and regular auditing. This is backed up by NCSC.
[https://www.ncsc.gov.uk/collection/cloud/the-cloud-security-principles]

During the Session on Git and version control, Git was introduced version control, which cloud platforms heavily rely on:
1. Controlled software updates
2. Tracking system changes
3. Maintaining deployment history

Additional research on important matters for this proposal:
1. Cloud costs models
2. Data centre redundancy
3. UK councils' adoption case studies
NHS cloud Adoption case study:
[
](https://digital.nhs.uk/services/cloud-centre-of-excellence)
[
](https://www.ncsc.gov.uk/collection/cloud/the-cloud-security-principles)
## Initial Analysis of the Proposal
*Use some simple analysis tools to help you think through whether the proposal is a good idea*
Migrating to the cloud offers long-term efficiency, reliability, and security improvements. However, the transaction must be planned carefully to avoid disruption. However, not all systems will migrate easily, so a phased approach may be required. Staff training will also be essential to ensure new tools and workflows are adopted successfully.
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
        <li>Reduced hardware maintenance needs.</li>
        <li>improved reliabilty and uptime</li>
        <li>Stronger disaster recovery options</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Migration may require external expertise</li>
        <li>Potential downtime during transition</li>
        <li>Potential downtime during transition</li>
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
        <li>modernises council infrastructure</li>
        <li>supports hybrid and remote working</li>
        <li>Long term cost effciency</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Cyber attacks targeting cloud services</li>
        <li>Vendor lock in risks</li>
        <li>increasing subscription fees over time</li>
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
        <li>Must meet GDPR and public sector security standards</li>
        <li>Supports government cloud first initiatives</li>
        <li>Data residency and sovereignty must be considered</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Reduces hardware costs</li>
        <li>Predictable cloud based pricing</li>
        <li>initial investment for migration and training</li>
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
        <li>Supports flexible working hours</li>
        <li>Improves remote access to servers</li>
        <li>Reduces downtime risk</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Easier maintenance and updates</li>
        <li>Scalable infrastructure</li>
        <li>Access to Cybersecurity tools</li>
      </ol> 
    </td>
  </tr>
</table> 

## Questions to ask about the proposal
*Without knowing how exactly the council will implement this proposal, what questions should be raised?*

* question 1
Which cloud provider best fits the council's requirements?
* question 2
How will confidential data be protected and encrypted?
## Evaluation of the proposal
*Provide a brief evaluation based on what you know*

The proposal to migrate the council software into the cloud is forward-looking and incredibly beneficial. It improves reliability, supports modern working practices, reduces physical hardware risk, and follows national digital transformation guidance. Although migration requires investment and planning, the long-term advantages to efficiency, security, and scalabil
