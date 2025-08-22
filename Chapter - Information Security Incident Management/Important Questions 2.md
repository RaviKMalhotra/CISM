Questions Q
Ravila, a new CISO in a healthcare organization, is reviewing incident response records from the past several years. Ravila has determined that minor incidents were managed with too much rigor and complexity, while major incidents weren’t dealt with thoroughly enough. What might be the cause of this?

Lack of training for incident responders

Inconsistent levels of response to incidents

Lack of a tiered incident response plan

Improperly tuned SIEM use cases

   C. This organization has an incident response plan that has one path of response for incidents of all severities. The result is this: incidents of high severity are treated too lightly, and incidents of low severity are treated with too much rigor.

   A, B, and D are incorrect. A is incorrect because lack of training would more likely result in response to all incidents being subpar. B is incorrect because this is another way of describing the question rather than a description of its cause. D is incorrect because security information and event management system (SIEM) use case tuning would not likely cause this phenomenon.

Which of the following is not a valid objection for using incident response plan “templates” to serve as an organization’s security incident response plan?

The templates will lack the specifics about business processes and technology.

The templates will lack the specific regulations the organization is required to comply with.

The templates will lack the names of specific departments and executives.

The templates will not specifically call on the organization’s crisis response plan.

   B. This objection, that the templates will lack the names of specific regulations that the organization is obligated to comply with, is the weakest objection to the use of templates and is therefore the correct answer.

   A, C, and D are incorrect. A is incorrect because the lack of specifics about business processes and technologies in use is a valid objection to the use of a template. It is critical that an incident response plan be very specific about existing business processes so that the steps in an incident response plan will properly call out existing processes in the steps to respond to a security incident. Similarly, it is critical that an incident response plan has specific information about the technologies in use, as incident response plan steps will often direct responders to utilize technology in place for troubleshooting, isolation, and mitigation. C is incorrect because the lack of specific names of departments and executives is a valid objection to the use of such a template. The names of specific departments are needed, so that incident responders understand which departments to work with during various stages of incident response. The names of executives are also useful, as executives do need to be informed about an incident in progress. D is incorrect because the lack of specific references to an organization’s crisis response plan is a valid objection to such a template. A security incident response plan certainly needs to call out the organization’s crisis response plan, as a highly severe security incident may need to trigger an organization’s crisis response plan.

The purpose of documenting the steps taken during the response to an actual security incident includes all of the following except which one?

Helps the organization understand how to respond more effectively during future incidents

Helps the organization understand whether incident responders followed incident response procedures

Helps the organization understand whether the organization recovered from the incident

Helps the organization understand whether the incident response was compliant with applicable laws

   C. Documenting the steps followed during the response to an actual incident does little to help the organization understand whether it actually recovered from the incident. Key personnel in the organization will know whether recovery was complete and successful and whether response steps were recorded or not.

   A, B, and D are incorrect. A is incorrect because documentation of the steps taken during the response to an actual incident does help the organization understand how to respond more effectively during future incidents. B is incorrect because documentation of the steps taken during the response to an actual incident does help the organization understand whether incident responders followed incident response procedures. D is incorrect because knowing what steps were taken during an actual incident does help the organization understand whether the incident responders’ actions were compliant with applicable laws—for instance, whether evidence was properly collected and protected and whether appropriate parties were notified.

Why should incident responders participate in incident response tabletop exercises?

Helps incident responders better understand incident response procedures

Helps incident responders find mistakes in incident response procedures

Helps incident responders understand how long it should take to respond to actual incidents

Helps incident responders memorize incident response procedures so they can respond more quickly

   A. Participation in incident response tabletop exercises helps incident responders become more familiar with incident response procedures. Talking through a simulated incident and thinking about each step in incident response helps responders better understand each step—how to perform it and why it is needed.

   B, C, and D are incorrect. B is incorrect because the identification of mistakes is not the primary purpose of an incident response tabletop exercise, although it does sometimes occur. C is incorrect because knowing the length of time required to respond to an incident is not a primary purpose of tabletop exercises. D is incorrect because memorization of response procedures is not an objective of tabletop exercises.

Why should incident responders be asked to review incident response procedures?

Helps incident responders memorize incident response procedures so they can respond more quickly

Helps incident responders understand how long it should take to respond to actual incidents

Helps incident responders better understand incident response procedures

Helps incident responders find mistakes in incident response procedures

   D. A primary purpose of incident response plan document review is to identify errors in response plans so that they can be corrected prior to an actual incident occurring.

   A, B, and C are incorrect. A is incorrect because memorization of response procedures is not an objective of a document review of an incident response plan. B is incorrect because gaining an understanding of the length of time required to respond to an incident is not an objective of a review of incident response documents. C is incorrect because the primary objective of a document review is not to help incident responders be more familiar with incident response procedures. That said, improved familiarity is a valuable by-product of such a review.

James, the CISO in an organization, has reviewed the organization’s incident response plans and disaster recovery plans and has determined that incident response plans do not include any provisions should a security incident occur during a declared disaster of the organization. What is James’s most appropriate response?

Declare a security incident.

Request that the next tabletop exercise take place at the emergency operations center.

No response is required because security incident response plans are not required for DR sites.

Request that incident response and disaster recovery teams update the IRPs to include procedures during emergency operations mode.

   D. The organization’s incident response plan needs to be updated to include procedures, contact information, and other relevant information to assist incident responders to respond to a security incident properly should one occur while the organization is in emergency operations mode.

   A, B, and C are incorrect. A is incorrect because the declaration of an incident is inappropriate; there is no incident happening here. B is incorrect because a tabletop exercise in the context of an emergency operations center, while potentially valuable, will be at least somewhat ineffective because there are no security incident response procedures to be followed should a security incident occur while in emergency operations mode. C is incorrect because security incidents certainly must be declared should an incident occur at a disaster recovery site.

Which step in an incident response plan is associated with tabletop exercises?

Remediation

Detection

Analysis

Planning

   D. Security incident response tabletop exercises are a part of planning. The actual exercise itself will include most of the steps of an actual incident so that responders will be more familiar with response procedures.

   A, B, and C are incorrect. Tabletop exercises are not limited to remediation, detection, or analysis, but are concerned with the entire life cycle of incident response.

Of what value is a business impact analysis (BIA) in security incident response planning?

Identifies the business owners associated with information systems and, therefore, the escalation path

Identifies the systems that require forensic examination during an incident

Indirectly identifies the most important information systems that require protection from threats

Directly identifies the location of the most critical data

   C. The BIA is a discovery and analysis activity that identifies the most critical business processes in an organization. The BIA also identifies information systems, service providers, and suppliers that support those business processes. In information security and security incident response, the BIA helps to identify an organization’s most important information systems.

   A, B, and D are incorrect. A is incorrect because the identification of business owners is a secondary benefit from the BIA. B is incorrect because the BIA does not determine the need for forensic examination. D is incorrect because the location of critical data is a by-product of the BIA, but is not necessarily critical for incident response.

Threat analysts in an organization have identified a potential malware threat in an advisory. Detection in production systems will necessitate configuration changes to antivirus systems on production servers. What approach is best for making these configuration changes?

Make the changes as soon as possible on production servers to stop the threat.

Test the changes on nonproduction servers and measure performance impact.

C.   Write a rule in intrusion detection systems to block the threat at the network layer.

Update antivirus signature files to permit detection of the threat.

   B. Testing configuration changes in a nonproduction environment is the best first step to ensure that the configuration changes will not adversely affect production systems, both in terms of transaction capacity and correct function.

   A, C, and D are incorrect. A is incorrect because there may be unintended consequences to the configuration changes that may affect server availability. C is incorrect because intrusion detection systems cannot block intrusions. D is incorrect because threat analysts have already determined that configuration changes are necessary (perhaps activating real-time file access detection that might be normally turned off).

Which methods are used to test security incident response plans?

Document review, tabletop simulation, actual incident

Document review, walkthrough, parallel test, cutover test

Document review, walkthrough, tabletop simulation, parallel test, cutover test

Document review, walkthrough, tabletop simulation

   D. The types of tests that can be performed for security incident response are document review (where one or more individuals review the document on their own), walkthrough (where two or more individuals discuss the steps in the security incident response procedure), and tabletop simulation (where an expert moderator progressively reveals a realistic security incident scenario, and incident responders and others discuss their response activities and the challenges encountered).

   A, B, and C are incorrect. A is incorrect because an actual incident is not considered a purposeful test of an incident response plan. B and C are incorrect because a parallel test and cutover test are used in disaster recovery planning.

In the European General Data Protection Regulation, how quickly must an organization report a security breach of PII to government authorities?

72 hours

48 hours

24 hours

4 hours

   A. The European GDPR requires that organizations report breaches of personally identifiable information (PII) to authorities within 72 hours. If the organization takes more than 72 hours to notify authorities, an explanation for the delay must accompany the notification.

   B, C, and D are incorrect. All are incorrect because organizations are required to notify authorities of a PII breach within 72 hours, not 48, 24, or 4 hours.

Ravila, a new CISO in a healthcare organization, is reviewing incident response records from the past several years. Ravila has determined that minor incidents were managed inconsistently from one incident to the next. Staff turnover has not been an issue. What is the most likely cause of this?

Insufficient capacity for storage of forensic evidence

Excessive meddling by executive management

Inattention to detail

Lack of detailed incident response playbooks

   D. Of the available choices, the most likely cause of inconsistent response to security incidents is the lack of detailed procedural documentation in the organization’s security incident response plan. These detailed procedures are commonly known as playbooks.

   A, B, and C are incorrect. A is incorrect because insufficient storage capacity for forensic evidence is not a likely cause of inconsistent responses to incidents. B is incorrect because meddling by executives is not a likely cause for an inconsistent response. C is incorrect because inattention to detail is not the most likely cause.

Who are the best parties to develop an organization’s security incident response plan?

Business leaders and the general counsel

Security consultants from an outside firm

Internal security specialists and technology subject matter experts

Regulators and security incident response subject matter experts

   C. The best parties to develop a security incident response plan are internal security specialists and experts in relevant information technology.

   A, B, and D are incorrect. A is incorrect because business leaders and general counsel, though essential personnel to participate in the response to a breach, are not the best parties to develop an organization’s security incident response plan. B is incorrect because, although outside experts may be qualified to write a general-purpose plan, those consultants won’t be familiar with the organization’s business processes and uses of information technology. D is incorrect because regulators do not develop security incident response plans for organizations they regulate.

Which sequence correctly identifies the steps in security incident response?

Detection, analysis, containment, eradication, recovery, closure

Analysis, containment, eradication, recovery, closure

Detection, containment, closure, recovery

Detection, analysis, eradication, closure, recovery

   A. Of the choices available here, the correct sequence of steps in security incident response is detection, analysis, containment, eradication, recovery, and closure.

   B, C, and D are incorrect. None of these represents the correct sequence of steps in security incident response.

Designated incident responders would be asked to attend planned incident tabletop exercises for all reasons except which one?

Tabletop exercises serve as training for incident responders.

Tabletop exercises are important for estimating the amount of time required to respond to security incidents.

Tabletop exercises help incident responders become familiar with incident response procedures.

Tabletop exercises help identify errors in incident response procedures.

   B. Tabletop exercises are generally not a suitable opportunity to determine the length of time to respond to an incident. Rather, incident response tabletop exercises are designed to help incident responders become more familiar with incident response procedures.

   A, C, and D are incorrect. These are all valid reasons for asking incident responders to attend tabletop exercises.

What is the best time frequency for conducting tabletop exercises?

When significant changes are made to the incident response plan

Annually

Annually, or when there are significant changes to the incident response plan

Upon inception of the initial incident response plan

   C. Incident response tabletop exercises should be performed at least annually, as well as when significant changes are made to incident response plans. The hiring of new incident responders would present another opportunity to conduct tabletop exercises.

   A, B, and D are incorrect. A is incorrect because tabletop exercises should be conducted at least annually. If no changes are made to the incident response plan, significant time could elapse between exercises. B is incorrect because annual tabletop exercises are insufficient if significant changes are made to the security incident response plan. D is incorrect because an incident response plan should be exercised at least annually and when significant changes are made to the plan.

Incident responders have been asked to review a newly developed incident response plan. Incident responders’ feedback suggests confusion regarding what is expected from them and others in the organization during an actual incident. What is the most likely cause of this?

The incident response plan lacks definitions of roles and responsibilities.

The incident response plan lacks a list of key contacts.

The incident responders have not yet been trained in the use of the plan.

Outsourced forensics services have not yet been defined.

   A. The incident responders are confused because roles and responsibilities are undefined. This is a critical deficiency in an IRP because there will be confusion when important decisions need to be made, including the declaration of an incident, escalation, and notification of regulators, affected parties, and law enforcement.

   B, C, and D are incorrect. B is incorrect because the absence of key contacts is not likely to produce this type of confusion. C is incorrect because the lack of training is unlikely to result in incident responders not knowing who is responsible for carrying out specific activities during an incident. D is incorrect because the absence of a forensic analysis firm is not likely to produce this apparently wider confusion.

A multinational organization that is developing its security incident response plan has created its matrix of severity levels based upon data sensitivity, operational criticality, and data location. Why is this severity level scheme feasible or infeasible?

The scheme is feasible because it identifies basic characteristics of its data sets.

The scheme is feasible because of its simplicity.

The scheme is not feasible because of its complexity.

The scheme is not feasible because it is not mapped to business functions.

   A. This scheme, while a bit complex, appears reasonable because it addresses the primary characteristics of data sets. The sensitivity of data is an indication of whether it is protected by regulation or private obligations; the operational criticality of data associates the data to revenue or organizational reputation; the location of data indicates local regulation or perhaps the identity of a local incident response team. Surely, simpler schemes are more common, but this is a multinational organization, which potentially introduces several operational complications.

   B, C, and D are incorrect. B is incorrect because this scheme is not as simple as most. C is incorrect because this scheme, while somewhat complex, can be workable. D is incorrect because there is insufficient information to reach this conclusion.

What is the main purpose for including an escalation process in an incident response plan?

Legal is notified only if regulators are required to be notified.

Executives are notified only if the incident is severe enough to warrant their involvement.

Legal is notified only if affected parties need to be notified.

It provides an additional set of resources to help the incident response team.

   B. The primary reason for escalation in an incident response plan is to provide a structured way for specific executives to be notified during a serious incident. A structured incident response plan will include incident severity levels that can be objectively identified; severity levels will have varying frequencies of communicated updates, named resources to assist, and executives to notify. Executives need to be aware of a serious incident because it is more likely to have long-term operational and reputational impacts on the organization.

   A, C, and D are incorrect. A and C are incorrect because notification of regulators, legal staff, and affected parties is but a narrow aspect of the need for escalation. D is incorrect because escalation, while it may indeed provide additional resources, is a function of the severity of the incident, not the desire for additional help.

The entirety of a service provider contract on incident response states, “Customer is to be notified within 48 hours of a suspected breach.” Why is this statement sufficient or insufficient?

The statement is insufficient because “suspected breach” is ambiguous.

The statement is insufficient because 48 hours is too long an interval.

The statement is sufficient because 48 hours is considered reasonable.

The statement is sufficient because “suspected breach” is a well-known industry term.

   A. The term “suspected breach” is ambiguous and should be defined more specifically. Otherwise, it would be too easy for an organization to consider nearly every activity a “suspected breach.”

   B, C, and D are incorrect. B is incorrect because 48 hours is a reasonable and standard interval for breach notification. C is incorrect because, even though 48 hours is a reasonable and standard interval for breach notification, the term “suspected breach” is ambiguous, so the statement is insufficient. D is incorrect because “suspected breach” is not a term that is interpreted consistently.

An organization has successfully completed training and walkthroughs of its incident response plan. What is the next best step?

Repeat training at regular intervals.

Conduct one or more tabletop exercises.

Wait for an actual incident to prove the effectiveness of training and walkthroughs.

Conduct a penetration test of production systems to measure response.

   B. After successfully completing the training of incident response personnel and a walkthrough of the incident response plan, the next activity that should take place is a tabletop exercise, which is a facilitated simulation of an actual incident to help the organization better understand whether its incident response plan is effective.

   A, C, and D are incorrect. A is incorrect because repeating training, while it may be useful, is not the next best step. C is incorrect because there are other preparatory activities that should take place, particularly tabletop exercises. D is incorrect because the main purpose of a penetration test is the identification of vulnerabilities, not a test of an organization’s incident response capabilities.

In a business-to-business service provider contract, which language is most reasonable for notification of a security incident?

Notify customer within 1 hour of a breach

Notify customer within 48 hours of a suspected breach

C.   Notify customer immediately after a breach

Notify customer within 48 hours of a breach

   D. Notification of a customer within 48 hours of a breach is the most reasonable language. The term “breach” will need to be clearly defined elsewhere in the contract.

   A, B, and C are incorrect. A is incorrect because notification within 1 hour is unreasonably fast for notification. B is incorrect because the term “suspected breach” is a potentially wide loophole. C is incorrect, as “immediately” is ambiguous and unreasonable.

Under what circumstances would a security incident be accompanied by the triggering of a disaster recovery plan?

When the RPO has been exceeded

When the IRP calls out the DRP

When the security incident renders the system unusable

When a disaster has also occurred

   C. A disaster recovery plan may need to be triggered after a security incident if one or more systems are incapacitated for any reason—whether that be damage by the intruder or the need to quiesce a system to permit a forensic analysis to be performed on it.

   A, B, and D are incorrect. A is incorrect because recovery targets such as the recovery point objective (RPO) are not used as triggers for disaster declaration. B is incorrect because the incident response plan (IRP) should reference a disaster recovery plan (DRP) to guide incident responders as they investigate a security incident. D is incorrect because it is not necessary for a separate disaster to occur to trigger a disaster recovery plan.

A network operations analyst has noticed a sharp increase in inbound traffic at the organization’s main edge router, to the extent that legitimate traffic can no longer be processed. What has the organization experienced?

Denial-of-service attack

Zero-day malware outbreak

Distributed denial-of-service attack

Configuration error

   A. The organization has experienced a denial-of-service (DoS) attack, in which illegitimate traffic has rendered a system as incapacitated so that it can no longer perform its function.

   B, C, and D are incorrect. B is incorrect because the description does not indicate a zero-day malware attack. C is incorrect because the description does not indicate a distributed denial-of-service (DDoS) attack. D is incorrect because the description does not indicate a configuration error—although, indeed, a configuration error may have made the attack possible.

An attacker has launched a Smurf attack against an organization’s web server, rendering it incapacitated. What kind of an attack is this?

SYN flood

Ransomware attack

Denial-of-service attack

Distributed denial-of-service attack

   D. A Smurf attack involves sending large numbers of ICMP packets to a target system.

   A, B, and C are incorrect. A is incorrect because a Smurf attack is not the same as a SYN flood. B is incorrect because a Smurf attack is a distributed denial-of-service attack, not a ransomware attack. C is incorrect because a Smurf attack is better characterized as a distributed denial-of-service attack rather than a denial-of-service attack.

Which of the following is the best description of the kill chain?

A teaching tool that helps people understand a cyberattack

A model that depicts a typical attack scenario

A method used by wiper malware

A method used by malware droppers

   B. In a general sense, a kill chain is a model that depicts a typical attack scenario, consisting of 1) target identification, 2) selection and deployment of forces, 3) attack on target, and 4) accomplishment of attack objective.

   A, C, and D are incorrect. A is incorrect because a kill chain is not merely a teaching tool, but a realistic model that depicts the stages of a typical attack. C and D are incorrect because the term “kill chain” does not signify any specific type of malware.

When is the best time to develop an incident response plan?

At the start of the next budget cycle

As soon as possible

When an attack is suspected

When an attack is confirmed

   B. An incident response plan should be developed as soon as possible, as it is nearly impossible to know when an attack is likely to occur. It is far better to be prepared than to be unprepared.

   A, C, and D are incorrect. A is incorrect because waiting for a future event to begin incident response plan development is unwise. C and D are incorrect because an incident response plan should be developed, tested, and used to train responders prior to an incident.

When is the best time to declare a security incident?

At the start of the next budget cycle

As soon as possible

When an attack is suspected

When an attack is confirmed

   C. A security incident should be declared when an attack is suspected, as this generally will trigger the initiation of investigative activities that may lead to confirmation of a breach.

   A, B, and D are incorrect. A and B are incorrect because a security incident should be declared as soon as one is known or suspected. D is incorrect because incident responders should not wait until the attack is confirmed to declare an incident.

Organizations should outsource security incident response for all of the following reasons, except:

Difficulty justifying the hire of qualified incident responders

Difficulty estimating the likelihood or impact of incidents

Difficulty affording the compensation for incident responders

Difficulty justifying the hire of workers with specialized skills

   B. Difficulty in estimating the likelihood or impact of an incident is not related to a decision to outsource security incident response.

   A, C, and D are incorrect. All are incorrect because they all are valid reasons for outsourcing security incident response.

What is the best method for a new security leader to examine an organization’s security incident response plan?

Hire an external auditor to examine the plan

Interview incident responders and solicit their opinion

Conduct a walkthrough and measure the results

Perform a gap analysis to compare the existing plan with the ideal plan

   D. Performing a gap analysis is the best available choice. The security leader can compare the characteristics of the existing plan with those of an ideal plan.

   A, B, and C are incorrect. A is incorrect because it should not be necessary to pay an external audit firm to audit a plan. B is incorrect because incident responders may or may not be qualified to opine on the effectiveness of an incident response plan. C is incorrect because a walkthrough may or may not reveal improvement areas in an existing plan.

What criteria should be used to select the types of incidents chosen for playbook development?

High-impact incidents least likely to occur

High-impact incidents most likely to occur

Incidents in scope of applicable regulations

Incidents that receive the most publicity

   B. The best criteria for developing incident response playbooks are those high-impact incidents that are most likely to occur. Examples may include ransomware attacks, business e-mail compromise, and stolen login credentials.

   A, C, and D are incorrect. A is incorrect because high-impact incidents that are least likely to occur do not warrant the development of an incident response playbook. C is incorrect because the scope of regulations is not necessarily a primary driver for incident response playbook development. D is incorrect because publicity should not be a primary driver for selecting the types of incidents for playbook development.

An organization is conducting a study to identify its most critical business processes. What is this study commonly known as?

Business impact analysis

Enterprise risk assessment

Vulnerability assessment

Enterprise gap assessment

   A. The organization is undergoing a business impact analysis (BIA), used in business continuity planning to identify the most critical business processes.

   B, C, and D are incorrect. B is incorrect because the purpose of an enterprise risk assessment is to identify the most significant risks. C is incorrect because the purpose of a vulnerability assessment is to identify weaknesses in systems, business processes, or procedures. D is incorrect because a gap assessment is performed to identify the differences between the existing state of a system or process and a standard.

“Accounts payable and accounts receivable functions will be unable to process, impacting the availability of services and supplies and resulting in reduced revenue” is an example of which of the following?

An SLA

A consequence

A statement of criticality

A statement of impact

   D. This is a statement of impact that is a part of a business impact assessment (BIA). A statement of impact describes the consequence of the loss of a critical asset in business terms.

   A, B, and C are incorrect. A is incorrect because this statement is not a service level agreement (SLA). B is incorrect because, although this statement describes a consequence, this is not the best answer. C is incorrect because this is not a statement of criticality.

What is the purpose of a criticality analysis?

A study of the vulnerabilities of a system or process

A study of the impact of the incapacitation of a system or process

A statement describing the consequences of the loss of a system or process

A study of the dependencies of a system or process

   B. A criticality analysis is a specialized risk assessment, focused on a particular system or process, to understand threats and vulnerabilities in the context of business continuity and disaster recovery planning.

   A, C, and D are incorrect. A is incorrect because a criticality analysis includes, but is not limited to, a study of the vulnerabilities of a system or process. C is incorrect because a statement of the consequences of the failure of a process or asset is known as a Statement of Impact. D is incorrect because a study of the dependencies of a system or process is a part of a Business Impact Assessment.

Which of the following is the best definition of maximum tolerable downtime?

The time since disaster onset in which the organization’s survival is at risk

The time in which the organization is required to disclose a breach

The time since disaster onset in which the organization must recover

The time in which an organization initiates a disaster recovery plan

   A. Maximum tolerable downtime (MTD), also known as acceptable interruption window (AIW), is the theoretical period of time since the onset of a disaster in which the organization’s survival is at risk.

   B, C, and D are incorrect. B is incorrect because MTD is not related to breach disclosure. C is incorrect because MTD is not a measure of recovery. D is incorrect because MTD is not a measure of initiation of a disaster recovery plan.

Which of the following best describes the metric maximum tolerable outage?

The dwell time between the onset and the declaration of a disaster

The theoretical period of time since the onset of a disaster in which the organization’s survival is at risk

The longest that an organization can operate in emergency operations mode

The greatest allowable loss of data in a disaster or breach scenario

   C. Maximum tolerable outage, or MTO, is the longest period of time that an organization can operate in emergency operations mode, otherwise known as disaster recovery mode. MTO drives the need to reestablish normal production operations within a specific period of time.

   A, B, and D are incorrect. A is incorrect because MTO is not a measure of dwell time between disaster onset and declaration. B is incorrect because this definition is known as maximum tolerable downtime (MTD). D is incorrect because the maximum data loss is known as recovery point objective, or RPO.

Which of the following is the best description of the greatest amount of acceptable data loss in a disaster scenario?

Recovery time objective

Recovery point objective

Service delivery objective

Maximum tolerable downtime

   B. The recovery point objective, or RPO, is the maximum data loss from the onset of a disaster.

   A, C, and D are incorrect. A is incorrect because the recovery time objective (RTO) is a measure of time from the onset of a disaster until the resumption of service. C is incorrect because the service delivery objective (SDO) is a measure of the level of quality of an alternate process or system. D is incorrect because maximum tolerable downtime (MTD) is the theoretical time from disaster onset that an organization’s survival is at risk.

Which position is responsible for determining RPO and RTO recovery targets?

Business continuity planner

Disaster recovery planner

IT architect

Business unit leader

   D. The establishment of recovery targets, including recovery point objective (RPO) and recovery time objective (RTO), is performed by the business unit leader or department head responsible for the operations of key business processes.

   A, B, and C are incorrect. A is incorrect because business continuity planners do not set RTO and RPO targets. B is incorrect because disaster recovery planners do not set RTO and RPO targets. C is incorrect because IT architects do not set RTO and RPO targets.

Disaster recovery planners and management have agreed that the acceptable throughput of a system in emergency operations mode can be one-half of the capacity of the primary system. This is expressed as:

Recovery capacity objective

Recovery point objective

Service delivery objective

Recovery time objective

   A. The measure of transaction throughput for a recovery system is expressed by the recovery capacity objective (RCapO).

   B, C, and D are incorrect. B is incorrect because the recovery point objective (RPO) is a measure of maximum data loss in a disaster scenario. C is incorrect because the service delivery objective (SDO) is a measure of quality of service of a recovery system. D is incorrect because the recovery time objective (RTO) is a measure of the time from disaster onset until a recovery system has resumed service.

For a given cost level, a disaster recovery planner has determined that the best achievable RTO for a system is 12 hours, even though management has set the RTO at 4 hours. What is the disaster recovery planner’s next step?

Inform management that the desired RTO can be met within budget.

Change the RTO from 12 hours to 4 hours.

Change the RTO from 4 hours to 12 hours.

Inform management that the desired RTO cannot be achieved within budget.

   D. A DR planner needs to inform management when desired recovery targets cannot be met with the resources provided. Management will need to either change the RTO to a larger figure or provide additional resources so that the RTO can be met.

   A, B, and C are incorrect. A is incorrect because the scenario states that the RTO cannot be met. B and C are incorrect because the DR planner should not be changing recovery targets.

The architecture of an alternate processing system to be used in the event of a disaster is best determined by:

Management

BC planners

DR planners

IT architects

   D. When recovery targets, including RPO and RTO, have been established by management, the architecture of an alternate processing system should be developed by IT architects.

   A, B, and C are incorrect. A is incorrect because management should not be determining the architecture of an alternate processing system, although management does specify recovery targets that will influence that architecture. B and C are incorrect because BC and DR planners are not the best parties to develop the architecture of an alternate processing system.

For disaster recovery purposes, why is book value not a preferred method for determining the value of assets?

Information assets have no book value.

Book value may vary based on location if a recovery site is located elsewhere.

Some assets may not be tracked for depreciation.

The cost to replace damaged or destroyed assets could exceed book value.

   D. For disaster recovery purposes, organizations should use replacement or redeployment cost versus book value for asset value. If assets are damaged or destroyed in a disaster, they must be replaced; costs for replacements may be much higher than book value.

   A, B, and C are incorrect. A is incorrect because this question is not specifically about information assets. B is incorrect because this is not a true statement. C is incorrect because this statement is not relevant.

For disaster recovery scenarios, which of the following methods for setting the value of computer equipment is most appropriate?

Recovery cost

Replacement cost

Lost revenue

Book value

   B. Replacement cost may be best suited for disaster recovery scenarios. In a disaster situation, computer equipment may need to be replaced rather than repaired.

   A, C, and D are incorrect. A is incorrect because recovery cost is not usually associated with computer equipment, but instead with information. C is incorrect because this is not the best method. If in cases where revenue derived from computer equipment is greater than its replacement value, this would underscore the need for rapid replacement or use of an alternative processing center. D is incorrect because it may be difficult to replace lost assets if only book value is available to obtain replacements.

How are security requirements integrated into disaster recovery plans?

Security requirements and controls are a part of the foundation of DR plans and capabilities.

Management selects the most important security controls and requirements to be a part of DR.

C.   The purpose of DR is different from cybersecurity and the two are not related.

Only those controls required by law are a part of DR plans and capabilities.

   A. All of an organization’s security policies, requirements, and controls apply equally to all environments, whether they are normal production environments or disaster recovery environments. At any time, an organization may be compelled to shift its processing from its primary processing facilities to a disaster recovery processing facility, making the DR facility the new (but usually temporary) primary facility. All controls for security and privacy apply to all systems in all locations.

   B, C, and D are incorrect. B is incorrect because security requirements and controls cannot be “cherry picked” to be included in DR sites based on management’s wishes. Instead, all requirements and controls apply to all information processing facilities, whether they are primary or recovery facilities. C is incorrect because security requirements and controls apply to all information processing facilities, whether they are primary or recovery facilities. D is incorrect because an organization may have requirements and controls in addition to those required by law that should be applicable to all information processing facilities.

What is the best approach to the development of an organization’s security incident response plan?

Developing separate security incident recordkeeping

Developing a general IR plan and leaving the details to subject matter experts

Developing detailed playbooks and relying on the organization’s crisis management plan

Leveraging the organization’s crisis management plan

   D. The best approach for developing any IR plan is to leverage existing processes wherever possible, including the corporate crisis management plan, an IT incident response plan, and emergency communications plans. Leveraging existing processes is more effective than building separate parallel processes.


   Q Questions
Why would an organization consider developing alerts on its security information and event management system, as opposed to using its existing daily log review procedure?

More accurate and timely awareness of security issues requiring action

Compliance with PCI DSS 3.2 requirement 10.6

Reduce costs associated with time-consuming log review

Free up staff to perform more challenging and interesting tasks

   A. The best reason for developing alerts in a security information and event management system (SIEM) is the near-instantaneous alerting of personnel of a security matter requiring investigation and potential remediation. Daily log review is time-consuming and infeasible in all but the smallest organizations due to the high volume of log data that is produced in information systems.

   B, C, and D are incorrect. B is incorrect because PCI DSS requirement 10.6 does not specifically require that an organization employ a SIEM with alerts, although it is suggested as a more effective approach for daily log review. C is incorrect because cost reduction is not the best reason to generate security alerts. D is incorrect because providing staff with professional challenges is not the best answer to this question.

While responding to a security incident, the person acting as the incident commander is unable to notify a particular executive in an escalation procedure. What should the incident responder do next?

Notify regulators that the organization is experiencing a cyber incident and requires assistance.

Notify law enforcement that the organization is experiencing a cyber incident and requires assistance.

Order incident responders to suspend their activities until the executive has been contacted.

Notify the next highest executive in the escalation chain.

   D. The best choice among those available here is for the incident commander to notify the next highest executive in the escalation chain. This is not an ideal situation, but security incident response does not always proceed as expected.

   A, B, and C are incorrect. A and B are incorrect because notification of outside authorities is not an appropriate alternative action to the inability to contact an executive. C is incorrect because the suspension of security incident response activities may permit attackers to continue inflicting damage to the organization.

Why would PCI DSS requirements require organizations to put emergency contact information for payment card brands in their incident response plans?

An emergency is a poor time to start looking for emergency contact information for outside organizations.

Card brands must be notified of an incident involving card data as soon as possible.

C.   Requirement 12.10 in PCI DSS requires it.

It reminds organizations to notify the card brands in the event of a breach.

   B. PCI DSS requirement 12.10 implies that card brands’ emergency contact information should be included in organizations’ security incident response plans because the card brands should be notified as soon as possible after knowledge of a breach of credit card data.

   A, C, and D are incorrect. A is incorrect because, although it is true that an emergency is a poor time to start looking around for emergency contact information, this is not the best answer. C is incorrect because this answer is circular; there is a reason for the requirement, and answer B offers the reason. D is incorrect because the presence of contact information does not serve as a reminder; instead, security incident response procedures should explicitly specify when, and under what conditions, an organization is required to notify one or more of the card brands.

The purpose of a post-incident review of a security incident includes all of the following except which one?

Determine the root cause of the incident.

Identify improvements in incident response procedures.

Determine the motivation of the attacker.

Identify improvements in cybersecurity defenses.

   C. Determination of the motivation of an attacker is not one of the objectives of a review of the response to a security incident.

   A, B, and D are incorrect. A is incorrect because the determination of the root cause of a security incident is one of the main reasons for conducting a post-incident review. B is incorrect because the identification of improvements in incident response procedures is one of the reasons for conducting a post-incident review. D is incorrect because the identification of improvements in defenses is one of the objectives of a post-incident review.

Which term in security incident response represents the final activity that takes place during a response to an incident?

Post-incident review

Remediation

Closure

Containment

   A. A post-incident review, sometimes casually called a postmortem, is a review of the entire incident intended to help reviewers understand the incident’s cause, the role of preventive and detective capabilities, and the effectiveness of incident responders. The purpose of the after-action review is to identify improvements in defenses and response procedures to reduce the probability and/or impact of a similar future incident and to ensure a more effective response should one occur.

   B, C, and D are incorrect. These are all steps that take place after containment, mitigation, and recovery. Typically, the steps in security incident response are planning, detection, initiation, analysis, containment, eradication, recovery, remediation, closure, and post-incident review. Evidence is retained after an incident for an unspecific period of time.

Which of the following criteria would likely not be used to classify a security incident?

Data volume

System location

Data sensitivity

Operational criticality

   B. The location of a system is the least likely factor to be used to classify a security incident, unless the incident constitutes a breach of privacy of individuals, in which case there may be applicable laws such as GDPR or CCPA. Further, one influence of the location of a system might be the selection of personnel to respond to an incident, but this is not a part of incident classification.

   A, C, and D are incorrect. A is incorrect because the volume of data involved in an incident is likely to influence the incident’s classification, particularly if the data is sensitive. C is incorrect because the sensitivity of data involved in an incident is highly likely to influence the incident’s classification because of the possibility that regulators, law enforcement, or affected parties may need to be notified. D is incorrect because the operational criticality of a system is likely to influence the incident’s classification.

An incident response team is responding to a situation in which an intruder has successfully logged on to a system using stolen nonprivileged credentials. Which steps are most effective at containing this incident?

Lock the compromised user account.

Reset the password of the compromised user account.

Kill all processes associated with the compromised user account.

Block the intruder’s originating IP address and lock the compromised user account.

   D. Locking the compromised user account and blocking access from the intruder’s originating IP address are the best available steps here. Other steps should also be taken, including killing all processes running under the compromised user account.

   A, B, and C are incorrect. A is incorrect because locking the compromised user account may be ineffective, as the intruder may have compromised other accounts. B is incorrect because resetting the password will not stop the attack in progress unless the intruder needs to log in again. C is incorrect because killing processes alone will not necessarily prevent the intruder from logging in again. None of these choices are completely effective.

In what circumstances should executive management be notified of a security incident?

In no cases, other than monthly and quarterly metrics

In all cases

When its impact is material

When regulators are required to be notified

   D. Executive management should be notified of a cyber incident when it has been determined that regulators must be notified. This is not the only circumstance in which executives should be notified; others include incidents that disrupt business operations as well as large-scale incidents involving the compromise of sensitive information.

   A, B, and C are incorrect. A is incorrect because executives should be notified of serious incidents. B is incorrect because it is not necessary to notify executives of small-scale incidents. C is incorrect because it is not as good an answer as D.

Which of the following individuals should approve the release of notifications regarding cybersecurity incidents to affected parties who are private citizens?

General counsel

Chief marketing officer

Chief information security officer

Security incident response commander

   A. The general counsel—the top-ranking attorney—should be the person who approves the release of notifications to affected parties. An attorney has expertise in the interpretation of applicable laws, and it is these laws that stipulate notifications to outside parties.

   B, C, and D are incorrect. B is incorrect because the marketing executive generally does not have expertise in the law to decide when to perform a required notification. The marketing executive may, however, assist in the process of notifying those parties. C is incorrect because the CISO is generally not the leading expert in the law to determine if and when notification of outside parties is required. Further, because the CISO is generally responsible for security incident response, the CISO, the general counsel, and others function as an executive team responsible for high-level decisions, which is preferable to a single individual who makes all of the strategic decisions. D is incorrect because the incident commander is a lower-level person who is responsible for response logistics, but not for making high-level decisions such as notification of external affected parties.

What is the purpose of a write blocker in the context of security incident response?

Protects forensic evidence against tampering

Creates forensically identical copies of hard drives

Assures that hard drives can be examined without being altered

Assures that affected systems cannot be altered

   C. A write blocker is used to connect a hard drive that is the subject of forensic analysis to a computer. The write blocker permits the computer to read from the subject hard drive but does not permit any updates to the hard drive. This serves as an important control in a forensic investigation by preserving the integrity of subject hard drives.

   A, B, and D are incorrect. A is incorrect because a write blocker does not protect forensic evidence against tampering. B is incorrect because a write blocker is not used to create copies of hard drives; however, a write blocker is a supporting tool that ensures that copies of subject hard drives can be made without affecting the subject hard drives. D is incorrect because write blockers are not used to protect systems from being altered.

An employee in an organization is suspected of storing illegal content on the workstation assigned to him. Human resources asked the security manager to log on to the workstation and examine its logs. The security manager has identified evidence in the workstation’s logs that supports the allegation. Which statement best describes this investigation?

The investigation was performed properly, and the organization can proceed with disciplinary action.

Because forensic tools were not used to preserve the state of the workstation, the veracity of the evidence identified in the investigation can be called into question.

The investigation should enter a second phase in which forensic tools are used to specifically identify the disallowed behavior.

The investigation cannot continue because the initial examination of the workstation was performed without a signed warrant.

   B. Because the security manager logged in to the subject’s workstation without first taking steps to preserve a forensic copy of the workstation, the security manager could be accused of planting evidence on the workstation, and this allegation would be difficult to refute. The security manager should have first taken a forensic image of the workstation’s hard drive before examining its contents.

   A, C, and D are incorrect. A is incorrect because the investigation was not performed properly: the security manager could potentially have tampered with the workstation’s hard drive and even planted evidence. If the disciplined employee brings a legal challenge to the organization, the challenge would cast doubt on the security manager’s actions. C is incorrect because the damage has already been done: the security manager’s initial examination of the hard drive has tainted the integrity of the hard drive; this cannot be undone. D is incorrect because a warrant is not required for an organization to conduct an examination and analyze its own property—in this case, a workstation.

Under the state of California’s data security and privacy law of 2002 (SB 1386), under what circumstances is an organization not required to notify affected parties of a breach of personally identifiable information (PII)?

When the organization cannot identify affected parties

When the PII is encrypted at rest

When the number of compromised records is less than 20,000

When the number of total records is less than 20,000

   B. Under the 2002 state of California’s security and privacy law (SB 1386), organizations are not required to notify affected parties of the breach of security if the information was encrypted at rest.

   A, C, and D are incorrect. A is incorrect because even when an organization is unable to identify all of the specific parties affected by a security breach, the organization is required to publicly announce the breach. C is incorrect because there is no lower limit on the number of compromised records. D is incorrect because there is no limit on the size of a compromised database.

Which of the following is not considered a part of a security incident post-incident review?

Motivations of perpetrators

Effectiveness of response procedures

Accuracy of response procedures

Improvements in preventive controls

   A. The motivation of the perpetrators is generally not a part of a security incident post-incident review. Of the available answers, this is the least likely to be a part of a post-incident review.

   B, C, and D are incorrect. B is incorrect because the effectiveness of response procedures is a key focus area in a post-incident review; it helps ensure that similar incidents in the future can be handled more effectively. C is incorrect because the accuracy of response procedures is considered; it helps ensure that organizations will handle similar future incidents more accurately. D is incorrect because a review of preventive (also detective and administrative) controls is a key focus of a post-incident review; it helps ensure that opportunities for improvements in relevant controls can help reduce the probability and/or impact of future events.

Which of the following is usually not included in a cost analysis of a security incident during the post-incident review?

Penalties and legal fees

Notification to external parties

Assistance by external parties

Loss of market share

   D. Market share is generally not included in a cost analysis of a security event, because changes in market share may be more long-term and potentially unknown for several months, quarters, or more. Changes in market share are also more difficult to attribute, as many other forces contribute to these changes.

   A, B, and C are incorrect. A is incorrect because penalties (from regulators, customers, and others) and legal fees are generally included in the overall cost of a security breach. B is incorrect as the cost of notification to affected parties is generally included among the costs of a security breach. C is incorrect because professional services fees and other costs from outside parties in support of the investigation, forensics, analysis, and other activities are generally included.

Which of the following describes the best practice for capturing login log data?

Capture all unsuccessful login attempts. Capture user ID, password, IP address, and location.

Capture all successful and unsuccessful login attempts. Capture user ID, password, IP address, and location.

Capture all successful and unsuccessful login attempts. Capture user ID, IP address, and location.

Capture all unsuccessful login attempts. Capture user ID, IP address, and location.

   C. The best practice for logging authentication events is the capture all successful and unsuccessful login attempts and to capture the user ID, IP address, and location (if known).

   A, B, and D are incorrect. A is incorrect because successful login attempts should also be captured, and passwords should not be captured. B is incorrect because passwords should not be captured. D is incorrect because successful logins should also be captured.

What is the best method for utilizing forensic investigation assistance in organizations too small to hire individuals with forensic investigation skills?

Utilize interns from a nearby college or university that teaches cyber-forensic investigations.

Request assistance from law enforcement at the city, state/province, or national level.

Obtain an incident response retainer from a cybersecurity firm that specializes in security incident response services.

Use one of several cloud-based, automated forensic examination services.

   C. Most organizations cannot justify hiring a cybersecurity specialist who has computer and network forensic investigations skills and experience. Such organizations should obtain an incident response retainer from a qualified cybersecurity professional services firm that will render assistance if and when a security incident occurs.

   A, B, and D are incorrect. A is incorrect because interns will generally not have sufficient experience to be able to complete a forensic investigation and create a chain of custody. B is incorrect because law enforcement agencies, most of which have insufficient computer forensics resources, are generally not available to perform computer or network forensic analysis unless it is associated with a major crime. D is incorrect because there are no cloud-based forensic examination services (at the time of this writing).

An organization that obtains a SIEM is hoping to improve which security incident response–related metric?

Remediation time

Dwell time

Postmortem quality

Damage assessment

   B. Dwell time, or the time that elapses from the start of an incident to the realization that the incident has occurred (or is still occurring), can be improved through the use of a security information and event management system (SIEM). Collecting log data from systems in the organization, a SIEM correlates log events and produces alerts when actionable incidents are discovered.

   A, C, and D are incorrect. A is incorrect because a SIEM will have a negligible impact on dwell time. C is incorrect because a SIEM will have little or no impact on postmortem quality. D is incorrect because a SIEM will have only minor impact on damage assessment.

An organization has developed DLP solutions on its endpoints and file servers, but an adversary was able to exfiltrate data nonetheless. What solution should the organization next consider to detect unauthorized data exfiltration?

Network anomaly detection

Advanced antimalware

Endpoint firewalls

DDoS mitigation

   A. Network anomaly detection, including NetFlow technology, is designed to baseline normal network behavior and report anomalous network traffic.

   B, C, and D are incorrect. B is incorrect because advanced antimalware is not designed to detect data exfiltration. C is incorrect because endpoint firewalls will not appreciably add to endpoint-based data loss prevention (DLP) in terms of detecting data exfiltration. D is incorrect because distributed denial-of-service (DDoS) mitigation will not help with the detection of data exfiltration.

At what point in the security incident response process should the general counsel be notified?

During quarterly reporting of key risk indicators

During the post-incident review

When the incident is initially declared

When notification of regulators or external parties is likely

   D. The general counsel, sometimes known as the chief legal officer, should be notified when it is determined that there may be a need to report the incident to regulators or other affected parties. The general counsel is responsible for the interpretation of applicable laws and other legal obligations (such as private contracts between organizations) and for making decisions regarding actions required by those laws and contracts.

   A, B, and C are incorrect. A and B are incorrect because the general counsel should be notified during serious incidents, not after they have concluded. C is incorrect because the general counsel does not need to be informed of minor incidents.

What should a security incident response plan utilize to ensure effective notifications of internal and external parties?

Business continuity plan

Crisis response plan

Contact list

Disaster recovery plan

   B. A crisis response plan typically contains contact information for parties to be contacted in various business emergency scenarios, including security incidents and breaches.

   A, C, and D are incorrect. A is incorrect because a business continuity plan does not generally contain detailed information regarding the notification of internal and external parties. C is incorrect because a contact list does not, by itself, define which parties are contacted, at what times, and in what circumstances. D is incorrect because a disaster recovery plan does not generally contain detailed information regarding the notification of other parties.

An organization recently suffered a security attack in which the attacker gained a foothold in the organization through the exploit of a weakness in an Internet-facing system. The root-cause analysis in the post-incident review indicated that the cause of the incident was the lack of a particular security patch on the system that was initially attacked. What can the security leader conclude from the root cause?

System engineers need additional training in patch management.

The firewall failed to block the attack.

C.   The vulnerability management process needs to be improved.

The root-cause analysis was not sufficient to identify the real root cause.

   D. The root-cause analysis of this security incident is insufficient. It is not appropriate to conclude that the breach occurred because of the lack of a patch. Proper root-cause analysis would further ask the following: Why was the patch missing? Why wasn’t this server a part of the patch management process? Why did the server get implemented without being included in the patch management process? Why did the monthly review of patched systems miss this new server? And why did an underqualified person perform the monthly review? In this example string of questions, root-cause analysis keeps asking why until no further information is available.

   A, B, and C are incorrect. A is incorrect because this conclusion cannot be reasonably reached based upon a missing patch. B is incorrect because there is not enough information to conclude that a firewall rule failure was the cause of the incident. C is incorrect because there is not enough information to say which portion of the vulnerability management process requires improvement.

What compensating control is most appropriate for the absence of encryption of backup media?

Store backup media in locked containers in a keycard-access controlled room.

Back up sensitive data to encrypted zip archives, which are backed up to tape.

Obfuscate the names of files backed up to backup media.

Do not permit backup media to be removed from the processing center.

   A. Improving the security of unencrypted backup media is the most feasible compensating control. Many organizations still utilize mainframe and midrange computer systems that do not have the capability of encrypting backup media. But organizations, even when using newer hardware, sometimes do not encrypt backup media for a variety of valid reasons.

   B, C, and D are incorrect. B is incorrect because there may be insufficient resources to zip archive very large data sets. C is incorrect because obfuscating filenames does little to protect the information contained therein. D is incorrect because retaining backup media in the processing center eliminates data assurance in certain disaster scenarios in which systems and media are damaged in the data center—for instance, in case of flood or fire.

The practice of proactively searching for signs of unauthorized intrusions is known as what?

Geolocation

Password cracking

Threat hunting

Log correlation

   C. “Threat hunting” is the term used to describe the activity by which analysts use advanced tools to search for signs of possible intrusions into systems. An example case of threat hunting involves the search for a specific operating system file that has a particular checksum, indicating that it has been altered with a specific emerging form of malware.

   A, B, and D are incorrect. A is incorrect because geolocation is concerned with the identification of the geographic location of a subject. B is incorrect because password cracking is used to derive passwords from a hashed or encrypted password archive. D is incorrect because log correlation is an activity performed by a SIEM to identify potential intrusions or other unauthorized activity.

A SaaS-based e-mail services provider backs up its customer data through the replication of data from one storage system in the main processing center to another storage system in an alternative processing center. This data assurance architecture leaves the organization vulnerable to what type of attack?

LUN spoofing

Supply chain

Smurf

Ransomware

   D. An organization that replicates data from one storage system to another is likely to be vulnerable to ransomware: storage systems will likely replicate the destructive encryption from the main storage system to other storage systems. This would result in no source of undamaged files from which to recover.

   A, B, and C are incorrect. A is incorrect because LUN spoofing is a fictitious term. B is incorrect because a supply chain attack is an attack on a manufacturing company in an attempt to alter or substitute components in a manufactured product (which can include software) for malicious reasons. C is incorrect because a Smurf attack is an attack in which large numbers of ICMP packets with the intended target source IP are broadcast to a network using an IP broadcast address.

An organization’s SIEM has generated alerts suggesting a user’s workstation is being attacked by ransomware. What steps should be taken in an effort to contain the incident?

Disconnect the user’s workstation from the network.

Disconnect the user’s workstation from the network and lock the user’s account.

Lock the user’s account and scan the network for other infected systems.

Pay the ransom and obtain decryption keys to recover lost data.

   B. Disconnecting the user’s workstation and locking the user’s account are the best first steps for containment. If the malware is running on the workstation, disconnecting it should prevent the loss of data on file shares that the user is permitted to access. Locking the user’s account will help to slow down instances of malware that may be present on other systems.

   A, C, and D are incorrect. A is incorrect because there may be other instances of malware running under the user’s account on other systems. C is incorrect because although the user’s account should be locked right away, scanning for other infected systems is a reasonable step later in the containment phase. D is incorrect because paying a ransom does not facilitate data recovery in about half of all ransomware cases.

What is the likely role of the chief marketing officer in an information security incident?

Keep records of security incident proceedings.

Update marketing collateral to state that security is important to the organization.

Notify regulators of the incident.

Develop press releases that describe the incident and the organization’s response to it.

   D. One activity that the chief marketing officer will perform is the development and distribution of press releases that describe the incident and the steps that the organization is taking to contain it and recover from it. Ideally, generic versions of these press releases are written during incident response plan development.

   A, B, and C are incorrect. A is incorrect because a marketing person is an unlikely choice to serve as the incident response team’s scribe. B is incorrect because such collateral updates are not a part of incident response, but activities that take place whenever the organization wishes to update its marketing messaging. C is incorrect because it is more likely that senior executives or the general counsel will be notifying regulators.

An organization has determined that there are no resources who have experience with malware reverse engineering and analysis. What is the organization’s best short-term remedy for this deficiency?

Employ log correlation and analysis on the SIEM.

Obtain tools that perform malware reverse engineering.

Obtain an incident response retainer from a qualified security consulting firm.

Train incident responders in malware analysis.

   C. The best short-term solution is to obtain a retainer from a security incident response firm that has staff and tooling available for this purpose. A viable long-term remedy may include training of in-house staff and acquisition of malware analysis tools.

   A, B, and D are incorrect. A is incorrect because log correlation and analysis on a SIEM will not contribute to the cause of malware analysis. B is incorrect because malware analysis tools are not helpful if personnel are not trained in their use. D is incorrect because training is not a viable short-term remedy.

Why should forensic analysis tools not be placed on incident responders’ daily-use workstations?

Workstations would become too costly and be a theft risk.

Incident responders will not be able to complete daily tasks during incident response.

Daily-use workstations do not have sufficient RAM capacity.

Daily-use activities may influence forensic tools and cast doubt on their integrity.

   D. The rule of forensic analysis tools is that they must be run on dedicated, isolated systems that are used for no other purpose. Only this will instill confidence that other activities cannot influence the outcome of forensic investigations.

   A, B, and C are incorrect. A is incorrect because theft risk is not a significant risk; still, it can be mitigated through secure storage of forensic computers. B is incorrect because this does not address the need for system isolation. C is incorrect because RAM capacity does not address the need for the forensic analysis system to be isolated from other activities.

A post-incident-review process addresses all of the following except which one?

Root-cause analysis

Selection of future incident response personnel

Potential improvements in preventive and detective controls

Potential improvements in security incident response procedures

   B. The selection of future incident response personnel is not likely to be included in a post-incident review. But on the topic of incident response personnel, issues of their training and knowledge may be discussed if there is a need for improvement.

   A, C, and D are incorrect. A is incorrect because a sound incident response post-incident review will include root-cause analysis to identify the root cause of the incident. C is incorrect because a post-incident review will strive to identify improvements in controls to increase awareness of an incident and reduce its impact and probability of occurrence. D is incorrect because a post-incident review attempts to find improvement opportunities in the incident review process itself.

Which of the following techniques best describes the impact of a security incident on management?

Hard costs and soft costs

Hard costs, soft costs, and qualitative impacts

The total of all outsourced professional services

The total of all hardware replacement for affected systems

   B. Because the costs and impact of a security incident can vary, the best approach is to report on specific hard costs, including professional services, tooling, and equipment, as well as soft costs, including the labor hours by in-house staff, together with qualitative impacts such as market share or reputation damage that are difficult to quantify.

   A, C, and D are incorrect. A is incorrect because hard costs and soft costs ignore qualitative impacts such as loss of market share and reputational damage. C is incorrect because the cost of outsourced services probably does not represent the totality of hard costs, and it does not represent qualitative impact such as reputation. D is incorrect because hardware replacement, when it is needed at all, is probably a small portion of the total cost of an incident.

For what reason(s) would an IT service desk incident ticketing system be inappropriate for the storage of information related to security incidents?

Automatic escalations would be timed incorrectly.

A service desk incident ticketing system is designed for a different purpose.

Sensitive information about an incident would be accessible to too few personnel.

Sensitive information about an incident would be accessible to too many personnel.

   D. The primary reason why an IT service desk incident ticketing system would not be used for security incidents is the potential for highly sensitive information in the ticketing system being available to all service desk and other IT personnel. A potential compromise is to record all incidents in the service desk ticketing system but store the most sensitive information (such as suspected personnel in an insider event or details about sensitive affected data or sensitive exploit information) elsewhere and reference it in the ticketing system.

   A, B, and C are incorrect. A is incorrect because escalations can often be customized for incidents of various types and severities. B is incorrect because an IT service desk incident ticketing system is an appropriate system for tracking security incidents. C is incorrect because details about a security incident should not be widely available.

At what point during security incident response should law enforcement be contacted?

When root-cause analysis during post-incident review identifies that a law has been broken

When directed by the incident response plan and approved by the incident response commander

When directed by the incident response plan and approved by the general counsel

When the incident response commander determines a law has been broken

   C. Law enforcement should be contacted when the incident response plan suggests such contact and when the general counsel has specifically approved it.

   A, B, and D are incorrect. A is incorrect because a post-incident review is generally far too late to notify law enforcement. B and D are incorrect because the incident commander is not the appropriate party to approve contact with law enforcement.

SOC operators and the incident response team have confirmed that an intruder has successfully compromised a web server and is logged in to it. The IR team wants to take steps to contain the incident but doesn’t want to disrupt operations unnecessarily. What approach should the IR team take?

Test the proposed changes in a test environment first.

Take containment steps as quickly as possible.

Lock the user account and reboot the server.

Turn on firewall debugging.

   A. When an incident response team is attempting to remove an intruder from a live system, it is often best first to test any changes in a test environment to understand the actual impact of such removal.

   B, C, and D are incorrect. B is incorrect because hastily made containment steps may disrupt the operations of the system. C is incorrect because rebooting the server may have a significant impact on operations (it is not revealed whether the affected server has no counterparts or is part of a server farm). D is incorrect because firewall debugging is not likely to help in incident containment.

All of the following are metrics for security incident response, except which one?

Dwell time

Lag time

Containment time

Time to notify affected parties

   B. “Lag time” is not a common term in information security metrics and is not likely to be reported.

   A, C, and D are incorrect. A is incorrect because dwell time, or the time that elapses between the start of an incident and the organization’s awareness of the incident, is a common and meaningful metric. C is incorrect because containment time is a common and meaningful metric. D is incorrect because the time to notify affected parties is a common and meaningful metric.

An organization recently suffered a significant security incident. The organization was surprised by the incident and believed that this kind of event would not occur. To avoid a similar event in the future, what should the organization do next?

Commission an enterprise-wide risk assessment.

Commission a controls maturity assessment.

Commission an internal and external penetration test.

Commission a controls gap assessment.

   A. An enterprise-wide risk assessment is the best option here so that risks of all kinds can be identified and remedies suggested for mitigating them.

   B, C, and D are incorrect. B is incorrect because it’s possible that there are missing controls; a controls maturity assessment takes too narrow a view here and focuses only on existing controls, when the problem might be controls that are nonexistent. C is incorrect because the nature of the incident is unknown and may not be related to technical vulnerabilities that a penetration test would reveal (for example, it may have been phishing or fraud). D is incorrect because a controls gap assessment takes too narrow a view here and focuses only on existing controls, when the problem might be controls that are nonexistent.

Security analysts in the SOC have noticed that the organization’s firewall is being scanned by a port scanner in a hostile country. Security analysts have notified the security manager. How should the security manager respond to this matter?

Declare a high-severity security event.

Declare a low-severity security event.

Take no action.

Direct the SOC to block the scan’s originating IP address.

   D. The best course of action is to block the IP address that is the origination of the port scan. However, even this may not be necessary because a port scan is not, by itself, a serious matter. However, it may represent reconnaissance by an intruder that is targeting the organization.

   A, B, and C are incorrect. A is incorrect because a port scan is not a high-severity security matter. B is incorrect because this is not the best answer; however, some organizations might consider a port scan a low-level security incident and respond in some way, such as blocking the IP address. C is incorrect because taking no action at all is not the best course of action.

Security analysts in the SOC have noticed a large volume of phishing e-mails that originate from a single “from” address. Security analysts have notified the security manager. How should the security manager respond to the matter?

Declare a high-level security incident.

Block all incoming e-mail from that address at the e-mail server or spam filter.

Issue an advisory to all employees to be on the lookout for suspicious messages and to disregard them.

Block the originating IP address.

   B. Of the choices available, the best one is to block any new incoming e-mail messages from the offending e-mail address. A better solution would be the use of a system that would do this automatically, as well as retrieve any offending messages already delivered to some users before the message was recognized as harmful.

   A, C, and D are incorrect. A is incorrect because this is not the best choice. However, depending on the nature of the threat (which is not revealed in this question), if the phishing is known to carry a malicious payload known to infect user machines successfully in the organization, then perhaps a high-severity incident is the right course of action. C is incorrect because this is not the best choice. However, in the absence of antiphishing controls, this may be the organization’s best choice. D is incorrect because this is not the best choice; the adversary may be able to continue sending e-mails from different servers.

Why is hardware asset inventory critical for the success of security incident response?

Critical processes such as software asset and software licensing depend upon accurate asset inventory.

Incident responders can better understand what assets may be involved in an incident.

Vulnerability scans need to cover all hardware assets so that all assets are scanned.

Penetration tests need to cover all hardware assets so that all assets are scanned.

   B. During a security incident, an accurate, complete, and up-to-date asset inventory can help incident responders respond more effectively during a security incident.

   A, C, and D are incorrect. A is incorrect because software inventory, while important for security operations, is not as important as vulnerability management, event management, and malware control. C and D are incorrect because vulnerability management and penetration tests, while important, are only a portion of critical activities that depend upon effective asset management.

Of what possible value is system classification in the context of security incident response?

System classification informs incident responders on what information is stored in systems.

System classification helps incident responders better understand the relative importance of systems.

System classification helps incident responders understand dependencies between systems.

System classification informs incident responders of the location of systems.

   B. System classification helps incident responders better understand the relative importance of various systems. This may play a role in incident escalation or communication.

   A, C, and D are incorrect. A is incorrect because system classification may not indicate anything about information stored on, or processed by, a system. C is incorrect because system classification does not generally indicate dependencies. D is incorrect because system classification does not generally reveal location information.

The corporate controller in an organization notified the CISO that an employee recently received an e-mail from the CEO with instructions to wire a large amount of money to an offshore bank account that is part of secret merger negotiations. The corporate controller has determined that this was a fraudulent transaction. How should the CISO respond?

Declare a security incident.

Call the bank.

Notify law enforcement.

Conduct a reverse wire transfer.

   A. The best course of action is to declare a security incident, so that appropriate incident responders can begin an investigation and notify other parties, such as the legal department.

   B, C, and D are incorrect. B is incorrect because a security incident should first be declared. It is likely that the bank will soon be notified as a part of incident response proceedings. C is incorrect because a security incident should first be declared. Instructions in the incident response plan will determine who is authorized to approve notifications to outside parties, including law enforcement. D is incorrect because there is no such transaction as a reverse wire transfer.

A SOC analyst is using a system to perform queries to determine whether any specific types of attacks or intrusions have occurred in the organization. What is the SOC analyst doing?

Performing a penetration test

Conducting threat hunting

Performing a vulnerability scan

Conducting threat modeling

   B. The process of looking for signs of intrusions is known as threat hunting.

   A, C, and D are incorrect. A is incorrect because a penetration test is an activity used to identify and confirm exploitable vulnerabilities in one or more systems. C is incorrect because a vulnerability scan is an activity used to identify vulnerabilities in one or more systems (and often is the first stage of a penetration test). D is incorrect because threat modeling is an activity where various types of threat scenarios are identified to determine whether any are likely to occur.

A SOC analyst is using a tool to identify potential weaknesses in one or more information systems. What is the SOC analyst doing?

Performing a penetration test

Conducting threat hunting

Performing a vulnerability scan

Conducting threat modeling

   C. The process of identifying potential weaknesses is known as a vulnerability scan.

   A, B, and D are incorrect. A is incorrect because a penetration test is an activity used to identify and confirm exploitable vulnerabilities in one or more systems. B is incorrect because threat hunting is the process of looking for signs of intrusions. D is incorrect because threat modeling is an activity where various types of threat scenarios are identified to determine whether any are likely to occur.

Why is it important to take long-term steps to reduce dwell time?

Forensic imaging will take less time to acquire.

Vulnerability scans will take less time to complete.

Organizations will be aware of security vulnerabilities earlier.

Organizations will be aware of security incidents earlier.

   D. Dwell time is the time between the onset of a security incident and the organization’s realization of the security incident. Reducing dwell time enables the organization to take containment and eradication steps earlier, often resulting in less damage and disruption.

   A, B, and C are incorrect. A is incorrect because dwell time is not related to forensic imaging. B is incorrect because dwell time is not related to vulnerability scans. C is incorrect because dwell time is not related to an organization’s realization of vulnerabilities, but of security incidents.

A chain of custody should be established for all of the following situations, except:

Computer intrusion by an external adversary

Employee terminated for lack of computer skills

Data theft perpetrated by an insider

Employee terminated for security policy violation

   B. A situation where an organization is terminating an employee for lack of computer skills is not likely to require a chain of custody, because a skill or performance gap is not usually associated with a security incident requiring a chain of custody.

   A, C, and D are incorrect. A is incorrect because a computer intrusion by an external adversary may require a chain of custody should law enforcement want to prosecute the intruder. C is incorrect because data theft perpetrated by an insider is a scenario likely to require a chain of custody. D is incorrect because an employee terminated for security policy violations is a scenario likely to require a chain of custody, should the former employee later sue the employer for wrongful termination.

How are the crisis management and security incident response functions related?

Security incident response leverages crisis management’s escalation model.

Crisis management and security incident response are not related.

Crisis management directs security incident response proceedings.

Crisis management leverages security incident response’s escalation model.

   A. In an organization with crisis management, a security incident response plan will borrow from, or utilize, incident escalation and other features from the crisis management plan, as opposed to developing a similar, yet separate, escalation plan.

   B, C, and D are incorrect. B is incorrect because security incident response and crisis management are related, as both are concerned with the principles and procedures to be followed in a business emergency. C is incorrect because crisis management, which is a general business emergency plan, will not include the detail present in a security incident response plan. D is incorrect because a crisis management plan will not typically borrow techniques from a security incident response plan.

   A, B, and C are incorrect. A is incorrect because existing incident recordkeeping should be leveraged instead of building a separate record. B is incorrect because detailed IR playbooks should also be developed so that SMEs understand what steps to take for various incident scenarios. C is incorrect because an overall IR plan is needed, even when there are detailed IR playbooks and a crisis management plan.
