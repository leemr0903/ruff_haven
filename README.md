<h1>Ruff Haven Crisis Shelter Database Design</h1>

<h2>Overview</h2>
This project was completed as part of the University of Utah’s IS 6420 course in Database Theory and Design. Our group designed a transactional database system for Ruff Haven, a nonprofit animal crisis shelter that provides temporary housing for pets whose owners are experiencing hardship. The database was developed to support the organization’s operations such as intake tracking, boarding logistics, grooming services, rehoming processes, and a new proposed venture involving domestic abuse safe housing. PostgreSQL and DBeaver were used for implementation, and Lucidchart was used to develop the conceptual, logical, and physical models.

<h2>Business Problem</h2>
Ruff Haven currently supports many vital services but does not have a unified, scalable system to manage and track all interactions between pets, owners, and service offerings. With continued organizational growth and increasing demand, the shelter required a reliable database solution to improve operational efficiency, safeguard sensitive information, and lay the foundation for future service expansion, especially for vulnerable populations such as victims of domestic violence.

<h2>Objectives</h2>
<ul>
  <li>Create a comprehensive database that supports Ruff Haven’s core programs such as crisis sheltering, grooming, rehoming, and community outreach.</li>
  <li>Design a new venture within the database to support co-sheltering of domestic abuse survivors and their pets using secure and anonymous data handling.</li>
  <li>Ensure the final database structure is well-documented, ethically responsible, scalable, and technically sound for nonprofit deployment.</li>
</ul>

<h2>Data and Methodology</h2>
<ul>
  <li>The team gathered requirements by reviewing Ruff Haven’s public forms, service information, and relevant legal context such as Utah House Bill 175.</li>
  <li>A conceptual model was created using Lucidchart, outlining key entities such as Pet, Owner, Boarding Stay, Grooming Session, and Rehoming.</li>
  <li>The model was then translated into a logical and physical schema in PostgreSQL using DBeaver for implementation and testing.</li>
  <li>Tables were normalized to reduce redundancy, and bridge tables were added to support complex relationships and ensure relational integrity.</li>
</ul>

<h2>Deliverables</h2>
<ul>
  <li><a href="Ruff Haven Report.pdf"><strong>Project Summary Report</strong></a> which outlines the database’s scope, entity design, service logic, ethical framework, and future features.</li>
  <li><a href="Ruff Haven Presentation.pdf"><strong>Final Presentation Slides</strong></a> used in a live walkthrough of our system and key recommendations for Ruff Haven stakeholders.</li>

<h2>Key Features</h2>
<ul>
  <li>Database structure includes 17 tables covering all critical services, pet-owner relationships, volunteer coordination, and contract tracking.</li>
  <li>The rehoming process is supported by features for scheduling meetings, managing digital adoption contracts, and tracking pet availability.</li>
  <li>A new safe house system is proposed with anonymized pet and owner records, capacity limits, and bed assignments to enhance security.</li>
  <li>Support for future features such as vaccination tracking and partner organization referrals is also considered in the schema design.</li>
</ul>

<h2>Ethical and Technical Considerations</h2>
<ul>
  <li>All personally identifiable information is stored in separate, restricted-access tables to protect user privacy and promote trust.</li>
  <li>Access control and data handling protocols are designed to prevent unauthorized access and ensure compliance with ethical data standards.</li>
  <li>The system supports optional consent for data usage in reporting and outreach, with clearly defined permissions built into the schema.</li>
</ul>

<h2>My Contributions</h2>
<ul>
  <li>Contributed to the development of the conceptual and physical schema in Lucidchart and PostgreSQL, including key design decisions around normalization and relational integrity.</li>
  <li>Led the creation of bridge tables and query logic for managing grooming sessions, foster stays, and owner-pet relationships.</li>
  <li>Drafted the written report sections addressing ethical considerations, technical implementation, and requirements mapping.</li>
  <li>Presented the proposed domestic abuse safe house expansion to peers and faculty, including visual models and relational flow diagrams.</li>
</ul>

<h2>Challenges and Lessons Learned</h2>
<ul>
  <li>Designing for both flexibility and precision required thoughtful planning, especially for dynamic services like rehoming and boarding that span multiple interactions.</li>
  <li>The process of balancing anonymization with trackability showed the importance of ethical database design, particularly for nonprofits serving vulnerable populations.</li>
  <li>Working as a team on interdependent design tasks highlighted the importance of collaborative tools, clear communication, and iterative feedback.</li>
</ul>

<h2>Impact</h2>
This project provides Ruff Haven with a centralized system that improves operational clarity, service tracking, and data security. The database also supports future integrations with mobile apps, dashboards, and reporting tools. With the proposed safe house model and additional feature readiness, Ruff Haven can expand its mission-driven programs and serve more people and pets in need with care and accountability.

