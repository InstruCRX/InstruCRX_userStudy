# instruCRX_userStudy

[studyData.csv](https://github.com/InstruCRX/InstruCRX_userStudy/blob/main/studyData.csv): Anonymized raw data in csv format

## Content

1) [Pre/post test questionnaire](https://github.com/InstruCRX/InstruCRX_userStudy/blob/main/README.md#prepost-test-questionnaire-g3-g4)
2) [Self-assessmemnt questionnaire](https://github.com/InstruCRX/InstruCRX_userStudy/blob/main/README.md#self-assessmemnt-questionnaire-g1-g2-g5)
3) [Data set columns description](https://github.com/InstruCRX/InstruCRX_userStudy/blob/main/README.md#data-set-columns)

## Pre/Post test questionnaire (G3, G4)

| Category                            | Item No | Item                                                                     | Correct answer                                                                                                        | False answer 1                                                                                           | False answer 2                                                                                                                                                                  | False answer 3                                                                                                 |
| ----------------------------------- | ------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| ICS network knowledge               | NK1     | What is the ARP protocol?                                                | A communication protocol mapping IP addresses to MAC addresses                                                        | A network-layer protocol, defining how data is exchanged between network components on the network layer | A cryptographic protocol designed to provide communications security over a computer network | A network protocol for operating network services securely over an unsecured network                           |
| ICS network knowledge               | NK2     | What is a PLC (SPS)?                                                     | An industrial computer control system, e.g. for controlling sensors                                                   | The processing unit of a computer                                                                        | A multi-purpose computer operated by an end user                                                                          | The core of a computer's operating system |
| ICS network knowledge               | NK3     | What is an ICS?                                                          | A virtually connected physical system                                                                                 | A user interface for interaction with physical maschines                                                 | An industrial sensor                                                                                                                                                            | The digital representation of a physical asset                                                                 |
| SIEM knowledge                      | SK1     | What is the purpose of a SIEM system?                                    | Correlarting secruity-relevant data from across the entire network to detect incidents                                | Reporting the status of the current tasks of the cybersecurity team                                      | Controlling incoming and outgoing network traffic based on predetermined security rules                                                                                         | Performing integrated management of main business processes                                                    |
| SIEM knowledge                      | SK2     | What is a SIEM event?                                                    | A seucrity-related log, transmitted to a SIEM system                                                                  | An attack identified by the SIEM system                                                                  | A conference for SIEM experts                                                                                                                                                   | A potentially manipulated file, identified by the SIEM system                                                  |
| SIEM knowledge                      | SK3     | What is the difference between a SIEM system and an IDS?                 | A SIEM correlates security-related  log data from various sources an IDS monitors a network for suspicious activities | A SIEM is the technical component of an IDS                                                              | There is no difference                                                                                                                                                          | A SIEM operates on a network, an IDS on an application layer                                                   |
| Incident response process knowledge | PK1     | What is Incident Response mainly concerned with?                         | Reacting to security incidents in a coherent and repeatable manner                                                    | Secure SW development                                                                                    | Implementing security controls such as anti malware software or access control                                                                                                  | Managment of security risks and policies                                                                       |
| Incident response process knowledge | PK2     | What is the first step of incident response?                             | Preparation                                                                                                           | Investigation                                                                                            | Reponse                                                                                                                                                                         | Analysis                                                                                                       |
| Incident response process knowledge | PK3     | What is an incident response playbook?                                   | A list of actions how to react to a specific kind of incident                                                         | A software for incident management                                                                       | A standard for incident categorization                                                                                                                                          | A database for cyber threat intelligence                                                                       |
| ICS attack knowledge                | AK1     | What is a Man In The Middle (MiTM) Attack?                               | Intercepting the network traffic between to parties                                                                   | Exhausting the system resources of a server                                                              | Phising for passwords via malicous email                                                                                                                                        | A malware attack targeting middleware                                                                          |
| ICS attack knowledge                | AK2     | Effect of a MitM Attack on an industrial system?                         | Inability of the ICS to read the sensor values, resulting in an interruption of the physical process                  | Escalation of priviledge on an HMI                                                                       | Replication of malware code on other devices in the network                                                                                                                     | Temporary inaccessibility of the ICS because it is flooded with requests                                       |
| ICS attack knowledge                | AK3     | How does ARP spoofing work?                                              | Linking the attacker’s MAC address with the IP of the victim                                                          | Poisoning the DNS cache of a client                                                                      | Replacing the IP address of a network packet                                                                                                                                    | Changing a factory-assigned IP address of a network interface                                                  |
| Incident response tool knowledg     | TK1     | How can you identify the attacking host during an ARP-based MiTM Attack? | Identifying which MAC address is falsely assigned to another network host                                             | Identifying the network host which sends an unusual high amount of requests                              | Identifying the network host openining a VPN connection                                                                                                                         | Identifying who modified the file  /etc/shadow                                                                 |
| Incident response tool knowledg     | TK2     | How can you make an arp cache static                                     | arp -s <IP> <MAC>                                                                                                     | arp -a  <MAC1> <MAC2>                                                                                    | vi /etc/sysconfig/network                                                                                                                                                       | more /etc/hosts --static                                                                                       |
| Incident response tool knowledg     | TK3     | How can you take down the interface of a network device?                 | ip link set dev <INTERFACE> down                                                                                      | ifconfig <INTERFACE>                                                                                     | service network stop                                                                                                                                                            | ip route list <INTERFACE>                                                                                      |


## Self-assessmemnt questionnaire (G1, G2, G5)

| Category              | Item No | Item                                                                                                                                                                                                |
| --------------------- | ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ARCS                  | A1      | The scenario and context of the training were interesting.                                                                                                                                          |
| ARCS                  | A2      | I wanted to successfully finish the training and complete all the tasks.                                                                                                                            |
| ARCS                  | R1      | To me, the scenario and context seemed to be realistic.                                                                                                                                             |
| ARCS                  | R2      | I my opinion, the tasks I performed represent skills that are required in real incident response work.                                                                                              |
| ARCS                  | C1      | During the training, I felt I was in control over my actions.                                                                                                                                       |
| ARCS                  | C2      | During the training, I had a sense that I made good progress.                                                                                                                                       |
| ARCS                  | S1      | During the training, I experienced excitement.                                                                                                                                                      |
| ARCS                  | S2      | I was satisfied with my performance during the training.                                                                                                                                            |
| Percieved relatedness | PR1     | I really like my teammates.                                                                                                                                                                         |
| Percieved relatedness | PR2     | I get along with my teammates.                                                                                                                                                                      |
| Percieved relatedness | PR3     | I collaborated actively with my teammates and did not keep to myself during the training.                                                                                                           |
| Percieved relatedness | PR4     | My teammates care about me.                                                                                                                                                                         |
| Percieved relatedness | PR5     | My teammates seem to like me much.                                                                                                                                                                  |
| Percieved relatedness | PR6     | My teammates are pretty friendly towards me.                                                                                                                                                        |
| Teamwork satisfaction | TS1     | I enjoyed the experience of collaborative learning with my teammates.                                                                                                                               |
| Teamwork satisfaction | TS2     | I liked solving problems with my teammates in this training.                                                                                                                                        |
| Teamwork satisfaction | TS3     | Interacting with my teammates increased my motivation to learn.                                                                                                                                     |
| Teamwork satisfaction | TS4     | I have benefited from interacting with my teammates.                                                                                                                                                |
| Teamwork satisfaction | TS5     | I have benefited from my teammates' feedback.                                                                                                                                                       |
| Teamwork satisfaction | TS6     | Working with my team had better training quality than working individually.                                                                                                                         |
| Teamwork skills       | TSK1    | Participating in the training together with my teammates has helped me strengthen the ability to participate actively and take a fair share of the group work.                                      |
| Teamwork skills       | TSK2    | Participating in the training together with my teammates has helped me strengthen the ability to give timely, constructive feedback to team members.                                                |
| Teamwork skills       | TSK3    | Participating in the training together with my teammates has helped me strengthen the ability to communicate actively and constructively.                                                           |
| Teamwork skills       | TSK4    | Participating in the training together with my teammates has helped me strengthen the ability to appreciate all perspectives and acknowledge contributions of others.                               |
| Teamwork skills       | TSK5    | Participating in the training together with my teammates has helped me strengthen the ability to constructively build upon contributions of others and integrate my own ideas with those of others. |
| Teamwork skills       | TSK6    | Participating in the training together with my teammates has helped me strengthen the ability to communicate my views without being dominant or passive-aggressive.                                 |
| Teamwork skills       | TSK7    | Participating in the training together with my teammates has helped me strengthen the ability to contribute appropriately to a healthy debate.                                                      |
| Teamwork skills       | TSK8    | Participating in the training together with my teammates has helped me strengthen the ability to respond to and manage conflicts constructively and effectively.                                    |

## Data set columns

| Column        | Type    | Range       | Description                                                                                                                                                                                         |
| ------------- | ------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID            | int64   | {0;9999}    | trainee ID                                                                                                                                                                                          |
| collaboration | int64   | {0;1}       | participation in the competitive-collaborative group                                                                                                                                                |
| gender        | int64   | {0;1}       | gender of the trainee (1=female)                                                                                                                                                                    |
| graduate      | int64   | {0;1}       | education level of the trainee (1=graduated)                                                                                                                                                        |
| points        | int64   | [-8;24]     | Points the participant scored during the training                                                                                                                                                   |
| NK1_pre       | int64   | {0;1}       | What is the ARP protocol?                                                                                                                                                                           |
| NK2_pre       | int64   | {0;1}       | What is a PLC (SPS)?                                                                                                                                                                                |
| NK3_pre       | int64   | {0;1}       | What is an ICS?                                                                                                                                                                                     |
| NK_avg_pre    | float64 | [0;1]       | Average from NK1_pre, NK2_pre and NK3_pre                                                                                                                                                           |
| SK1_pre       | int64   | {0;1}       | What is the purpose of a SIEM system?                                                                                                                                                               |
| SK2_pre       | int64   | {0;1}       | What is a SIEM event?                                                                                                                                                                               |
| SK3_pre       | int64   | {0;1}       | What is the difference between a SIEM system and an IDS?                                                                                                                                            |
| SK_avg_pre    | int64   | {0;1}       | Average from SK1_pre, SK2_pre and SK3_pre                                                                                                                                                           |
| PK1_pre       | int64   | {0;1}       | What is Incident Response mainly concerned with?                                                                                                                                                    |
| PK2_pre       | int64   | {0;1}       | What is the first step of incident response?                                                                                                                                                        |
| PK3_pre       | float64 | [0;1]       | What is an incident response playbook?                                                                                                                                                              |
| PK_avg_pre    | int64   | {0;1}       | Average from PK1_pre, PK2_pre and PK3_pre                                                                                                                                                           |
| AK1_pre       | int64   | {0;1}       | What is a Man In The Middle (MiTM) Attack?                                                                                                                                                          |
| AK2_pre       | int64   | {0;1}       | Effect of a MitM Attack on an industrial system?                                                                                                                                                    |
| AK3_pre       | float64 | [0;1]       | How does ARP spoofing work?                                                                                                                                                                         |
| AK_avg_pre    | int64   | {0;1}       | Average from AK1_pre, AK2_pre and AK3_pre                                                                                                                                                           |
| TK1_pre       | int64   | {0;1}       | How can you identify the attacking host during an ARP-based MiTM Attack?                                                                                                                            |
| TK2_pre       | int64   | {0;1}       | How can you make an arp cache static                                                                                                                                                                |
| TK3_pre       | float64 | [0;1]       | How can you take down the interface of a network device?                                                                                                                                            |
| TK_avg_pre    | int64   | {0;1}       | Average from TK1_pre, TK2_pre and TK3_pre                                                                                                                                                           |
| NK1_post      | int64   | {0;1}       | What is the ARP protocol?                                                                                                                                                                           |
| NK2_post      | int64   | {0;1}       | What is a PLC (SPS)?                                                                                                                                                                                |
| NK3_post      | int64   | {0;1}       | What is an ICS?                                                                                                                                                                                     |
| NK_avg_post   | float64 | [0;1]       | Average from NK1_post, NK2_post and NK3_post                                                                                                                                                        |
| SK1_post      | int64   | {0;1}       | What is the purpose of a SIEM system?                                                                                                                                                               |
| SK2_post      | int64   | {0;1}       | What is a SIEM event?                                                                                                                                                                               |
| SK3_post      | int64   | {0;1}       | What is the difference between a SIEM system and an IDS?                                                                                                                                            |
| SK_avg_post   | int64   | {0;1}       | Average from SK1_post, SK2_post and SK3_post                                                                                                                                                        |
| PK1_post      | int64   | {0;1}       | What is Incident Response mainly concerned with?                                                                                                                                                    |
| PK2_post      | int64   | {0;1}       | What is the first step of incident response?                                                                                                                                                        |
| PK3_post      | float64 | [0;1]       | What is an incident response playbook?                                                                                                                                                              |
| PK_avg_post   | int64   | {0;1}       | Average from PK1_post, PK2_post and PK3_post                                                                                                                                                        |
| AK1_post      | int64   | {0;1}       | What is a Man In The Middle (MiTM) Attack?                                                                                                                                                          |
| AK2_post      | int64   | {0;1}       | Effect of a MitM Attack on an industrial system?                                                                                                                                                    |
| AK3_post      | float64 | [0;1]       | How does ARP spoofing work?                                                                                                                                                                         |
| AK_avg_post   | int64   | {0;1}       | Average from AK1_post, AK2_post and AK3_post                                                                                                                                                        |
| TK1_post      | int64   | {0;1}       | How can you identify the attacking host during an ARP-based MiTM Attack?                                                                                                                            |
| TK2_post      | int64   | {0;1}       | How can you make an arp cache static                                                                                                                                                                |
| TK3_post      | float64 | [0;1]       | How can you take down the interface of a network device?                                                                                                                                            |
| TK_avg_post   | int64   | {1;2;3;4;5} | Average from TK1_post, TK2_post and TK3_post                                                                                                                                                        |
| NK_diff       | float64 | [0;1]       | Difference between NK_avg_pre and NK_avg_post                                                                                                                                                       |
| SK_diff       | float64 | [0;1]       | Difference between SK_avg_pre and SK_avg_post                                                                                                                                                       |
| PK_diff       | float64 | [0;1]       | Difference between PK_avg_pre and PK_avg_post                                                                                                                                                       |
| AK_diff       | float64 | [0;1]       | Difference between AK_avg_pre and AK_avg_post                                                                                                                                                       |
| TK_diff       | float64 | [0;1]       | Difference between TK_avg_pre and TK_avg_post                                                                                                                                                       |
| A1            | int64   | {1;2;3;4;5} | The scenario and context of the training were interesting.                                                                                                                                          |
| A2            | int64   | {1;2;3;4;5} | I wanted to successfully finish the training and complete all the tasks.                                                                                                                            |
| R1            | int64   | {1;2;3;4;5} | To me, the scenario and context seemed to be realistic.                                                                                                                                             |
| R2            | int64   | {1;2;3;4;5} | I my opinion, the tasks I performed represent skills that are required in real incident response work.                                                                                              |
| C1            | int64   | {1;2;3;4;5} | During the training, I felt I was in control over my actions.                                                                                                                                       |
| C2            | int64   | {1;2;3;4;5} | During the training, I had a sense that I made good progress.                                                                                                                                       |
| S1            | int64   | {1;2;3;4;5} | During the training, I experienced excitement.                                                                                                                                                      |
| S2            | int64   | {1;2;3;4;5} | I was satisfied with my performance during the training.                                                                                                                                            |
| ARCS_avg      | float64 | [0;5]       | Average from A1 - S2                                                                                                                                                                                |
| PR1           | int64   | {1;2;3;4;5} | I really like my teammates.                                                                                                                                                                         |
| PR2           | int64   | {1;2;3;4;5} | I get along with my teammates.                                                                                                                                                                      |
| PR3           | int64   | {1;2;3;4;5} | I collaborated actively with my teammates and did not keep to myself during the training.                                                                                                           |
| PR4           | int64   | {1;2;3;4;5} | My teammates care about me.                                                                                                                                                                         |
| PR5           | int64   | {1;2;3;4;5} | My teammates seem to like me much.                                                                                                                                                                  |
| PR6           | int64   | {1;2;3;4;5} | My teammates are pretty friendly towards me.                                                                                                                                                        |
| PR_avg        | float64 | [0;5]       | Average from PR1 - PR6                                                                                                                                                                              |
| TS1           | int64   | {1;2;3;4;5} | I enjoyed the experience of collaborative learning with my teammates.                                                                                                                               |
| TS2           | int64   | {1;2;3;4;5} | I liked solving problems with my teammates in this training.                                                                                                                                        |
| TS3           | int64   | {1;2;3;4;5} | Interacting with my teammates increased my motivation to learn.                                                                                                                                     |
| TS4           | int64   | {1;2;3;4;5} | I have benefited from interacting with my teammates.                                                                                                                                                |
| TS5           | int64   | {1;2;3;4;5} | I have benefited from my teammates' feedback.                                                                                                                                                       |
| TS6           | int64   | {1;2;3;4;5} | Working with my team had better training quality than working individually.                                                                                                                         |
| TS_avg        | float64 | [0;5]       | Average from TS1-TS6                                                                                                                                                                                |
| PR_TS_avg     | float64 | [0;5]       | Avergae from PR_avg and TS_avg (composite variable "teamwork experience")                                                                                                                           |
| TSK1          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to participate actively and take a fair share of the group work.                                      |
| TSK2          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to give timely, constructive feedback to team members.                                                |
| TSK3          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to communicate actively and constructively.                                                           |
| TSK4          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to appreciate all perspectives and acknowledge contributions of others.                               |
| TSK5          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to constructively build upon contributions of others and integrate my own ideas with those of others. |
| TSK6          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to communicate my views without being dominant or passive-aggressive.                                 |
| TSK7          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to contribute appropriately to a healthy debate.                                                      |
| TSK8          | int64   | {1;2;3;4;5} | Participating in the training together with my teammates has helped me strengthen the ability to respond to and manage conflicts constructively and effectively.                                    |
| TSK_avg       | float64 | [0;5]       | Average from TSK1-TSK8                                                                                                                                                                              |
