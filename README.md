# PROJECTNAME

## Objective
[Brief Objective - Remove this afterwards]

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
1st Day: Logical Diagram
    This is the start of the 30 day SOC Challenge and the activity is to create a high level topology of the design that I will use. The following are the details of present in the topology
	 1. Servers:
	     a. Elk & Kibana
		 b. Windows Server with RDP enabled
		 c. Ubuntu Server with SSH enabled
		 d. Fleet Server
		 e. Ticket Server
		 f. C2 Server Mythic
	
	 2. Laptops:
	     a. For SOC Analyst
		 b. For Attacker
		 
	 3. Cloud Gateway
	
	 4. Internet Gateway
	
	In the topology, interconnections are also present and in details
	
  
  2nd Day: ELK Stack Introduction
    In this part, I go deep dive with the ELK Tool and this is what I learned about:
	 
     ELK is an acronym for Elasticsearch, Logstash, and Kibana, which are three open-source tools commonly used together for log management and data analysis.
 
      Elasticsearch: A distributed search and analytics engine that stores and indexes data, making it easily searchable. It’s known for its speed and scalability.      

      Logstash: A server-side data processing pipeline that ingests data from various sources, transforms it, and sends it to a "stash" like Elasticsearch. It is used to collect, parse, and enrich logs and other data.

      Kibana: A data visualization tool that works on top of Elasticsearch. It allows users to explore and visualize data stored in Elasticsearch using interactive dashboards and charts.

     Together, ELK is often used in security operations, IT monitoring, and other use cases where analyzing large volumes of log data is important. It's popular in building centralized logging solutions for searching, monitoring, and analyzing log data in real-time.

