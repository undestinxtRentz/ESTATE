# MAIN GDD (GAME DESIGN DOCUMENT): ESTATE — Complete Game Design & Development Blueprint

ESTATE

A Real Estate Company Roleplay & Business Management Experience

Roblox

Roleplay

Business Simulation

Multiplayer

Economy

This document establishes the core vision, gameplay mechanics, organizational structure, departments, economy, progression, and additional systems for ESTATE.

It is intended to serve as the main game design document (GDD) and development reference for the project. It should also be usable as a comprehensive context document for AI-assisted development.

The game takes heavy inspiration from the Roblox experience The Company, particularly its workplace roleplay, organizational hierarchy, and company-based multiplayer environment. However, ESTATE should establish its own identity through a significantly deeper real estate business simulation, a more meaningful employment system, a player-driven economy, and a much larger organizational structure.

The setting and business operations are heavily inspired by real estate development and brokerage companies in the Philippines.

## 1. Core concept

ESTATE is a multiplayer real estate company roleplay game where players become employees of fictional property development companies known as Developers.

Each Developer operates its own real estate business, owns an office headquarters, markets different properties, manages employees, handles clients, and competes against other Developers.

**Developers specialize in selling and managing different types of real estate, including:**

- Residential houses and subdivisions.

- Studio, one-bedroom, two-bedroom, and premium condominiums.

- Luxury residential developments.

- Commercial buildings and office spaces.

- Shopping centers and retail spaces.

- Luxury hotels and resorts.

- Mixed-use developments.

- Investment properties and land developments.

The central objective is not simply to become the highest-ranking employee. It is to participate in the operation of an entire real estate company.

A Property Specialist should be just as important to the company's success as a Director or Vice President. A company cannot survive through management alone; it needs employees who actively generate clients, secure reservations, and close property sales.

The game should reward teamwork, professional development, company loyalty, and business performance rather than making high-ranking positions the only desirable roles.

## 2. Main menu and first-time experience

When a player launches ESTATE, they should initially encounter a cinematic main menu.

The camera slowly orbits around a tall modern skyscraper that serves as the headquarters of the currently featured Developer. The environment should include a recognizable city skyline, roads, surrounding buildings, and subtle environmental animations.

The interface should be modern, clean, and professional without becoming excessively futuristic.

**Main menu buttons:**
| Button | Function |
| --- | --- |
| PLAY | Begins the game and opens Developer selection or resumes employment. |
| SETTINGS | Opens graphics, audio, interface, and optimization settings. |
| MIGRATE | Allows eligible players to transfer their employment to another Developer. |
| CREDITS | Displays the development team and acknowledgments. |

**The PLAY button should behave differently depending on the player's account data:**

- First-time players are directed to Developer selection.

- Returning employees are automatically directed to their previously assigned Developer.

- Players with an active employment restriction cannot freely join another Developer.

- Players who have been terminated, resigned, or migrated should follow the appropriate employment rules.

The main menu should have smooth transitions, button animations, and a loading sequence that does not unnecessarily delay gameplay.

## 3. Developers — The foundation of multiplayer

aedas.com

One of the most important features of ESTATE is the Developer system.

A Developer represents an independent real estate company operating within the game.

**Examples:**

- Highview Development

- Crestline Properties

- Northstar Realty

- Grandstone Developments

- Aurelia Estates

**Each Developer should have its own:**

## 1. Office headquarters and interior layout.

## 2. Company identity, logo, and branding.

## 3. Property catalog.

## 4. Residential and commercial developments.

## 5. Employee population.

## 6. Organizational hierarchy.

## 7. Management team.

## 8. Financial accounts and company funds.

## 9. Sales performance and monthly targets.

## 10. Contracts, policies, and operational schedules.

### 3.1 Developer selection

Upon pressing PLAY for the first time, players are presented with a Developer selection interface.

**Each Developer should have a profile displaying:**

- Company name and logo.

- Headquarters preview.

- Available positions.

- Employee count.

- Company financial status.

- Available properties.

- Monthly sales performance.

- Company reputation.

- Current management.

- Recruitment status.

Players can inspect Developers before joining.

Once a player applies and becomes an employee of a Developer, that Developer becomes their permanent employment affiliation until they resign, are terminated, or complete an approved migration.

### 3.2 Large server population

Unlike conventional workplace roleplay games, ESTATE should aim to support more than 100 players per Developer server, subject to Roblox's actual server and performance limitations.

This is important because the game depends on having enough employees to populate departments, operate sales locations, manage clients, and create an active corporate environment.

**The server architecture should prioritize:**

- Efficient character rendering.

- Optimized NPC behavior.

- Distance-based rendering and activity.

- Controlled replication of unnecessary information.

- Efficient UI and tablet communication.

- Server-authoritative employment and financial data.

The goal is to make each Developer feel like a functioning company rather than a small roleplay server.

## 4. Character creation and employment

joasphotographer.com

After selecting a Developer, the player is transported to the company's designated character preparation building.

This is where the player establishes their employee identity.

### 4.1 Character customization

**Players can customize:**

- Character appearance.

- Clothing and professional attire.

- Hairstyle and accessories.

- Display name.

- First name.

- Last name.

- Optional employee nickname.

The character's registered first and last name become part of their official employee profile.

The game should offer professional clothing options depending on the player's department. For example, sales employees may wear business attire, while maintenance employees have uniforms.

### 4.2 Human Resources recruitment

After character creation, players enter the main headquarters lobby.

The Human Resources department operates the recruitment area.

An HR employee or designated HR NPC handles applications.

**The recruitment process is:**

## 1. Player approaches the HR recruitment desk.

## 2. Player opens the available department and position list.

## 3. Player selects an eligible position.

## 4. The game checks their level, qualifications, and employment eligibility.

## 5. If the position requires an interview, an authorized manager or superior conducts it.

## 6. If accepted, the player receives an employment license and a position contract.

### 4.3 Employee license and employment contract

These two documents serve different purposes.

Employee License

- Permanent employment qualification for the Developer.

- Identifies the employee and their registered identity.

- Records their employee number.

- Records their employment history.

- Allows them to apply for eligible positions.

- Remains valid even if their position changes.

- Can be revoked following serious disciplinary action.

Position Contract

- Specifies the employee's current job.

- Defines salary and compensation.

- Specifies working hours and assigned schedules.

- Defines performance requirements.

- Includes the contract expiration date.

- Must be renewed periodically.

An employee can retain their permanent license while having an expired position contract.

However, an expired contract prevents them from receiving the salary and employment benefits attached to that position until it is renewed.

### 4.4 Employment persistence

The game must save an employee's information even after leaving the experience.

**Saved information includes:**

- Registered identity.

- Employee license.

- Current Developer.

- Current department.

- Position and employment level.

- Employment contract.

- Salary information.

- Experience and level.

- Sales records.

- Commission history.

- Disciplinary records.

- Promotions and previous positions.

When returning, the player is automatically sent back to their assigned Developer.

They cannot simply select another Developer from the menu.

### 4.5 Position availability

If the employee's previous position is currently occupied or unavailable, the player can temporarily work in another eligible position.

Their original position remains recorded.

**For example:**

A player is a Property Specialist. They leave the game and return while their original assignment is unavailable.

They can temporarily work as a Junior Property Specialist or another available eligible position until their original position becomes available.

Their employment history and accumulated experience should not be reset.

## 5. Moonlighting — The undercover employment system

rhinopat.com

Moonlighting is one of ESTATE's signature mechanics.

Ordinarily, employees are restricted to their registered Developer. However, players may choose to work for another Developer without formally resigning from their original company.

This is considered an illegal employment activity within the game's fictional corporate world.

### 5.1 How it works

A hidden NPC offers an underground service that modifies the player's in-game identity.

After accepting, the player receives a temporary alternate identity.

This allows them to enter another Developer and apply for positions without immediately revealing their original employment affiliation.

The system is intended as a fictional roleplay mechanic, not a real-world identity or document system.

### 5.2 Risks and consequences

Moonlighting carries substantial risks.

**Certain authorized positions can investigate suspicious employees:**

- Human Resources officers.

- Compliance officers.

- Internal auditors.

- Security personnel.

- Authorized executive officers.

**If an employee is caught:**

## 1. Their undercover employment is immediately suspended.

## 2. Their original Developer is notified.

## 3. Their employment license may be revoked.

## 4. Their position contract may be terminated.

## 5. They receive a temporary game restriction depending on the severity of the violation.

Moonlighting should provide interesting roleplay opportunities, but it should never become an unrestricted way to bypass the Developer selection system.

## 6. Organizational structure and career progression

The organizational hierarchy is one of the most important parts of ESTATE.

However, the game should not simply recreate a corporate organizational chart and make every position a decorative title.

Every position must have an actual purpose, responsibilities, tools, and contribution to the company's operations.

The following structure is the proposed organizational model.

### 6.1 Executive leadership

space-mint.com

These positions oversee the entire Developer.
| Position | Responsibilities |
| --- | --- |
| Board of Directors | Establishes company direction, approves major decisions, oversees executive performance. |
| Chairman | Leads the Board of Directors and supervises major corporate governance decisions. |
| Chief Executive Officer (CEO) | Highest operational authority; manages the overall company and its executives. |
| Chief Operating Officer (COO) | Supervises daily operations and ensures departments function properly. |
| Chief Financial Officer (CFO) | Oversees company finances, budgets, salaries, and financial stability. |
| Chief Marketing Officer (CMO) | Controls branding, marketing campaigns, and property promotion. |
| Chief Strategy Officer (CSO) | Plans expansion, development opportunities, and long-term business strategies. |

The CEO should be the highest-ranking operational employee.

The Board of Directors remains above the CEO in corporate governance.

### 6.2 Operations and sales division

This is the most important revenue-generating department.

Its main responsibility is to generate clients, secure property reservations, and complete property transactions.

**Hierarchy:**

Chief Operating Officer

```text
|

+-- Operations Director

    |

    +-- Head of Sales

        |

        +-- Broker Sales Head / Sales Manager

            |

            +-- Senior Property Specialist

                |

                +-- Property Specialist

                    |

                    +-- Junior Property Specialist
```

Position responsibilities
| Position | Main responsibilities |
| --- | --- |
| Operations Director | Oversees company operations, staffing, and division performance. |
| Head of Sales | Controls the entire sales division, establishes sales targets, and manages Sales Managers. |
| Broker Sales Head / Sales Manager | Manages sales teams, assigns manning locations, monitors quotas, and handles escalated clients. |
| Senior Property Specialist | Handles complex transactions, mentors specialists, and assists with difficult clients. |
| Property Specialist | Finds clients, conducts presentations, follows up leads, and secures reservations and sales. |
| Junior Property Specialist | Assists senior employees, learns the sales process, and handles basic client interactions. |

### 6.3 Sales divisions and teams

A major addition to the original organizational structure is the introduction of Sales Teams.

Each Sales Manager supervises one or more teams.

**Each team contains:**

- One Sales Manager.

- Several Senior Property Specialists.

- Multiple Property Specialists.

- Multiple Junior Property Specialists.

The exact team size should be adjustable by the management.

A Sales Manager should be responsible for their assigned employees rather than controlling the entire sales division.

This creates a clear chain of command.

Example sales team

Broker Sales Head

Sales Manager — Team A

Senior Specialist 1

Mentorship

Senior Specialist 2

Mentorship

Property Specialists

Client acquisition

Junior Specialists

Sales assistance

Important design decision: Sales Managers should not be able to take credit for all transactions made by their employees. Commission sharing must be transparent and tied to actual involvement.

### 6.4 Property management division

This division handles the company's properties after development, including leasing, building operations, and maintenance.
| Position | Responsibilities |
| --- | --- |
| Property Management Director | Oversees the company's managed properties. |
| Property Management Manager | Supervises leasing and maintenance operations. |
| Leasing Manager | Manages rental properties and leasing targets. |
| Leasing Officer | Handles tenant applications, rental agreements, and property viewings. |
| Leasing Assistant | Processes tenant records and assists with documentation. |
| Maintenance Manager | Oversees building maintenance and repair budgets. |
| Maintenance Supervisor | Assigns maintenance tasks and inspects completed work. |
| Maintenance Staff | Performs cleaning, repairs, and general building maintenance. |

**Additional gameplay:**

- Tenants submit maintenance requests.

- Leasing officers arrange property viewings.

- Maintenance employees receive work orders.

- Managers approve repair budgets.

- Buildings receive condition ratings.

- Poor maintenance affects reputation and rental income.

### 6.5 Finance and accounting department

This department controls the Developer's financial activities.
| Position | Responsibilities |
| --- | --- |
| CFO | Controls the company's overall financial strategy. |
| Finance Manager | Supervises budgets, payroll, and financial transactions. |
| Accountant | Records sales, expenses, and company revenue. |
| Finance Analyst | Evaluates profitability, financial trends, and forecasts. |
| Accounts Assistant | Processes payments and organizes financial documents. |

**Additional gameplay:**

- Salary processing.

- Commission verification.

- Reservation payment verification.

- Bank check processing.

- Expense reports.

- Department budgets.

- Monthly financial statements.

- Company bankruptcy monitoring.

The Finance Manager should not have unrestricted authority to withdraw company funds.

Major transactions should require approval from authorized executives.

### 6.6 Human Resources department

Human Resources handles employment, recruitment, employee welfare, and disciplinary actions.
| Position | Responsibilities |
| --- | --- |
| HR Manager | Oversees the entire HR department. |
| HR Specialist | Conducts recruitment, interviews, and contract management. |
| HR Assistant | Processes applications and employee documents. |

**Additional gameplay:**

- Recruitment applications.

- Interviews.

- Employment licenses.

- Position contracts.

- Contract renewal.

- Employee transfers.

- Resignation processing.

- Termination processing.

- Employee records.

- Attendance monitoring.

- Disciplinary hearings.

### 6.7 Legal and compliance department

| Position | Responsibilities |
| --- | --- |
| Legal & Compliance Manager | Oversees legal matters and corporate compliance. |
| Legal Officer | Reviews contracts, reservations, and legal documentation. |
| Compliance Officer | Investigates policy violations and suspicious transactions. |

This department is especially important for the Moonlighting system, contract disputes, and fraudulent company activities.

### 6.8 Marketing and public relations department

| Position | Responsibilities |
| --- | --- |
| Marketing Director | Oversees marketing operations and brand strategy. |
| Digital Marketing Manager | Manages online property campaigns. |
| Social Media Specialist | Publishes promotional content and announcements. |
| Content Creator | Produces property advertisements and promotional videos. |
| Brand & PR Manager | Maintains company reputation and branding. |
| Graphic Designer | Creates advertisements, brochures, and promotional materials. |
| Events Coordinator | Organizes launches, exhibitions, and property events. |
| Public Relations Officer | Handles company announcements and public relations. |

### 6.9 Corporate support departments

These departments support the entire organization.
| Department | Positions |
| --- | --- |
| Information Technology | IT Director, IT Manager, Systems Analyst, IT Support Specialist |
| Sales Support | Sales Operations Manager, Sales Coordinator, CRM Specialist |
| Customer Experience | Customer Service Manager, Customer Service Representative, Client Relations Officer |
| Facilities & Operations | Facilities Manager, Building Operations Supervisor, Facilities Staff |
| Risk & Compliance | Risk Manager, Compliance Specialist, Risk Analyst |
| Internal Audit | Internal Audit Director, Internal Auditor, Audit Assistant |
| Business Development | Business Development Manager, Market Research Analyst, Strategic Planning Specialist |

These departments should have useful gameplay functions rather than existing purely for decoration.

## 7. Position unlocking, levels, and promotions

The game needs a structured career progression system.

Players should not be able to apply for executive positions immediately after joining.

Each position has specific requirements.

### 7.1 Employee levels

**The proposed level progression is:**
| Level | Employee classification |
| --- | --- |
| 1–5 | Trainee |
| 6–10 | Junior Employee |
| 11–20 | Regular Employee |
| 21–30 | Experienced Employee |
| 31–40 | Senior Employee |
| 41–50 | Management Candidate |
| 51+ | Executive Candidate |

These levels should measure overall employee experience, not automatically grant promotions.

### 7.2 Position requirements

| Position | Suggested minimum level |
| --- | --- |
| Junior Property Specialist | 1 |
| Property Specialist | 5 |
| Senior Property Specialist | 15 |
| Sales Manager | 25 |
| Broker Sales Head | 35 |
| Head of Sales | 45 |
| Operations Director | 50 |
| Department Director | 50 |
| HR Specialist | 10 |
| HR Manager | 30 |
| Accountant | 15 |
| Finance Manager | 35 |
| Legal Officer | 15 |
| Legal Manager | 35 |
| C-level executives | 60+ |

These are preliminary requirements and should be adjusted during balancing.

### 7.3 Promotion requirements

Promotion should depend on more than level.

**The system should evaluate:**

- Employee experience.

- Work performance.

- Completed assignments.

- Sales records.

- Client satisfaction.

- Attendance.

- Disciplinary records.

- Department requirements.

- Available vacancies.

- Interview results.

For example, a Property Specialist cannot become a Sales Manager simply because they reached Level 25.

They must demonstrate leadership, have sufficient experience, and pass the required interview.

### 7.4 Interviews

Some positions require interviews before hiring or promotion.

Interviews can be conducted through an interactive interface or in-person roleplay.

**The interviewer can evaluate:**

- Professionalism.

- Knowledge of the department.

- Work experience.

- Leadership ability.

- Previous performance.

Higher positions should require interviews with higher-ranking officers.

### 7.5 Firing and resignation

Managers should have authority over their assigned employees.

A Sales Manager can issue warnings, recommend termination, and request the removal of an employee.

However, permanent termination should follow a controlled approval system.

**Proposed termination workflow:**

## 1. Manager submits a termination recommendation.

## 2. HR reviews the employee's records.

## 3. Evidence and reasons are documented.

## 4. An authorized HR officer or executive approves the decision.

## 5. The employee receives a notification.

## 6. Their position contract is terminated.

## 7. Their employment status is updated.

Executives should also be accountable.

A Board of Directors may initiate an executive review if a CEO or department head consistently fails their responsibilities.

Important: Avoid unrestricted firing votes. Voting can be abused by large groups of players. Use documented reasons, approval authority, and an appeal process.

## 8. Property Specialist — The heart of ESTATE

design.museaward.com

This is arguably the most important gameplay role in the entire experience.

The Property Specialist is responsible for finding potential buyers and turning their interest into actual property transactions.

Unlike traditional workplace roleplay games, ESTATE must make this lower-level position one of the most rewarding and economically important positions.

### 8.1 Manning — On-site selling

Manning refers to the assigned physical location where Property Specialists wait for potential clients.

**Possible manning locations:**

- Shopping malls.

- Retail establishments.

- Property showrooms.

- Condominium viewing areas.

- Sales galleries.

- Exhibition booths.

- Hotel development displays.

- Real estate events.

Managers assign specialists to different locations based on their schedules.

Each location should have different client traffic and customer demographics.

**For example:**
| Location | Possible clients |
| --- | --- |
| Shopping mall | Families, couples, young professionals |
| Luxury showroom | Wealthier buyers and investors |
| Condominium lobby | Interested residents and property buyers |
| Commercial exhibition | Business owners and investors |
| Hotel showcase | Hospitality investors and luxury buyers |

### 8.2 NPC client system

NPC clients should be dynamic rather than generic characters that simply walk up to employees.

Each NPC has individual characteristics.

**These can include:**

- Name.

- Appearance.

- Clothing.

- Occupation.

- Budget.

- Preferred property type.

- Preferred location.

- Family situation.

- Financial capacity.

- Purchase intention.

- Personality.

- Patience.

- Preferred communication style.

Some NPCs are casual visitors who are not interested in buying anything.

Others may be serious potential buyers.

There should also be wealthy clients who can afford expensive units, but these should be relatively uncommon.

### 8.3 Client interaction

When a Property Specialist approaches an NPC, they can initiate a conversation.

**The NPC may:**

- Ignore the employee.

- Decline the interaction.

- Ask about a specific property.

- Request information.

- Agree to receive a presentation.

- Provide contact information.

- Request a property viewing.

- Make a reservation.

- Purchase a property immediately.

The outcome should depend on the NPC's preferences, the employee's approach, and the property being offered.

### 8.4 Client information acquisition

When an NPC agrees to become a potential client, the specialist can register their information.

**The details include:**

- Full name.

- Contact number.

- Email address.

- Preferred property.

- Budget.

- Purchase timeline.

- Additional requests.

The client is then added to the Property Specialist's personal client database.

Each acquired client should have a unique record.

### 8.5 Client follow-ups

Not every client buys immediately.

Some need additional time, information, or convincing.

After completing their manning shift, specialists can return to the office and access the calling room.

The calling room is where they contact potential buyers through their registered client database.

**Possible outcomes:**

- Client answers and remains interested.

- Client requests additional information.

- Client schedules a viewing.

- Client requests a reservation.

- Client postpones their decision.

- Client declines the offer.

- Client becomes unreachable.

Follow-ups should be a core part of the sales gameplay.

### 8.6 Sales performance and commission

Property Specialists should receive significant commissions for successfully completing property transactions.

**Proposed commission structure:**
| Recipient | Suggested share of property sale value |
| --- | --- |
| Property Specialist | 10–25% |
| Supporting sales employees | 1–5% each |
| Sales Manager | 1–3% |
| Other eligible participants | Based on involvement |
| Developer | Remaining revenue |

These percentages are provisional and must be balanced against property prices and the company's financial system.

The important rule is that the Property Specialist who actually acquires and closes the client should receive the largest individual commission.

The Developer's share must be calculated after commissions and transaction expenses.

It should not be possible for the company to lose money on every transaction simply because commission percentages were calculated without considering its costs.

### 8.7 Why this position matters

Property Specialists are not merely entry-level employees.

**They are the people who:**

- Generate new clients.

- Create sales opportunities.

- Maintain client relationships.

- Conduct property presentations.

- Secure reservations.

- Complete transactions.

- Generate revenue for the Developer.

A company with excellent executives but no productive Property Specialists should struggle financially.

This is one of the defining principles of ESTATE.

## 9. The employee tablet

dribbble.com

Every player receives a company-issued tablet.

It serves as the central employee interface and should be inspired by the clean, functional tablet interface of The Company while having its own design language.

The tablet should be accessible through a keyboard shortcut or an on-screen button.

Its applications should change according to the employee's position and permissions.

### 9.1 Universal applications

**Every employee receives access to:**
| Application | Function |
| --- | --- |
| Profile | Displays employee identity and information. |
| Banking | Shows personal account balance and transaction history. |
| Mail | Sends and receives official company emails. |
| Chat | Communicates with other employees. |
| Schedule | Displays shifts and assigned activities. |
| Directory | Lists employees and their departments. |
| Documents | Stores employment documents and licenses. |
| Notifications | Displays company announcements and alerts. |
| Settings | Controls tablet preferences and interface options. |

### 9.2 Position-specific applications

| Position | Additional tablet tools |
| --- | --- |
| Property Specialist | CRM, Client Database, Leads, Sales Records, Reservations |
| Sales Manager | Team Management, Manning Assignments, Sales Reports, Quotas |
| Head of Sales | Division Performance, Sales Analytics, Manager Reports |
| HR | Recruitment, Employee Records, Contracts, Applications |
| Finance | Payroll, Transactions, Budgets, Accounting |
| Legal | Contract Review, Compliance Cases, Legal Documents |
| Marketing | Campaign Manager, Advertisements, Brand Assets |
| Maintenance | Work Orders, Inspection Reports, Repair Requests |
| Executives | Corporate Dashboard, Company Funds, Department Reports |

The tablet must enforce server-side permissions.

For example, a Property Specialist should not be able to open the executive banking interface simply by manipulating the client UI.

## 10. Client purchasing and reservation system

aureliaresidences.com

The property purchasing system should simulate a simplified version of real estate transactions in the Philippines.

There should be two primary transaction methods.

### 10.1 Direct purchase

A client can directly purchase an available property.

**The process:**

## 1. Client selects a property.

## 2. Specialist presents the unit details.

## 3. Client confirms their interest.

## 4. The system checks the client's available budget.

## 5. The client completes the transaction.

## 6. Finance verifies the payment.

## 7. The transaction is officially recorded.

## 8. The employee receives the applicable commission.

### 10.2 Reservation

A reservation is used when the client wants to secure a property before completing the full purchasing process.

**The process:**

## 1. Specialist presents the available property.

## 2. Client requests a reservation.

## 3. Specialist submits a reservation request through the tablet.

## 4. Sales Manager reviews the request.

## 5. Finance verifies the reservation payment.

## 6. The unit becomes reserved for the client.

## 7. The reservation documents are generated.

## 8. The client proceeds to the remaining purchasing requirements.

## 9. The transaction eventually becomes a completed sale.

A reservation should not automatically count as a completed property sale.

**The game should distinguish between:**

- Available.

- Reserved.

- Pending payment.

- Processing.

- Sold.

- Cancelled.

### 10.3 RFO and documentation

RFO stands for Ready For Occupancy.

The game should include simplified property documentation inspired by actual Philippine real estate processes.

**Possible documents:**

- Reservation Agreement.

- Buyer Information Sheet.

- Reservation Confirmation.

- Contract to Sell.

- Payment Schedule.

- Official Receipt.

- Bank Check Record.

- Turnover Documents.

The documents should be interactive game objects with appropriate department approval.

The specialist handles the client, while other employees help process the transaction.

**For example:**

- Sales Manager verifies the transaction.

- Finance verifies the payment.

- Legal reviews required documents.

- Customer Experience assists the buyer.

- Authorized executives approve exceptional cases.

This creates interdepartmental cooperation instead of making one employee perform every task.

### 10.4 Property catalog

Each Developer should have its own property catalog.

**Example fictional property:**

zielgroup.com.do

Highview Residences

₱34,000,000

Illustrative fictional game price
| Specification | Details |
| --- | --- |
| Property | Studio Condominium |
| Floor area | 60 sqm |
| Bedrooms | Studio |
| Availability | Available |
| Classification | Residential |
| Status | Ready for Occupancy |

Other property types should have their own prices, sizes, floor plans, locations, and features.

## 11. Manning schedules and daily operations

Every company should operate using a structured daily and weekly schedule.

The scheduling system should be controlled primarily by managers.

### 11.1 Daily schedules

**Possible employee activities:**

- Morning briefing.

- Office attendance.

- Manning assignments.

- Client acquisition.

- Property presentations.

- Calling sessions.

- Sales meetings.

- Documentation.

- Department meetings.

- End-of-shift reporting.

### 11.2 Weekly schedules

**Managers should be able to establish weekly activities such as:**

- Monday sales meetings.

- Tuesday property presentations.

- Wednesday client follow-ups.

- Thursday marketing campaigns.

- Friday performance reviews.

- Saturday property exhibitions.

- Sunday optional company events.

These should be configurable rather than forced on every Developer.

### 11.3 Attendance system

Employees clock in and clock out through their tablet or designated office terminals.

**The system records:**

- Attendance.

- Late arrivals.

- Completed shifts.

- Assigned manning locations.

- Absences.

- Overtime.

- Leave requests.

Attendance can affect performance evaluations and eligibility for certain benefits.

It should not punish players excessively for simply having real-life commitments.

## 12. Office headquarters and floor organization

brookfieldproperties.com

Each Developer should own a unique headquarters.

The building is not just a spawn location. It is the central operational environment for the entire company.

I propose the following floor arrangement.
| Floor | Department / Facility |
| --- | --- |
| Ground Floor | Main Lobby, Reception, Security |
| 2F | Human Resources and Recruitment |
| 3F | Employee Lounge, Clothing and Facilities |
| 4F | Sales Department |
| 5F | Calling Rooms and Client Relations |
| 6F | Sales Management and Head of Sales |
| 7F | Property Management and Leasing |
| 8F | Finance and Accounting |
| 9F | Legal and Compliance |
| 10F | Marketing and Public Relations |
| 11F | IT and Corporate Support |
| 12F | Operations and Business Development |
| 13F | Executive Offices |
| 14F | Boardroom and Chairman's Office |
| Rooftop | Executive Lounge and Events |

The floor layout can differ between Developers.

Some may have larger headquarters, additional floors, or specialized facilities.

### 12.1 Office facilities

**The building should include:**

- Reception desks.

- Employee elevators.

- Department offices.

- Conference rooms.

- Calling rooms.

- Interview rooms.

- Training rooms.

- Employee lounges.

- Executive offices.

- Financial counters.

- Document processing counters.

- Boardrooms.

- Emergency exits.

- Security checkpoints.

The elevators should allow employees to travel between departments quickly.

Access to restricted floors should depend on employee authorization.

## 13. The open-world map

ataslivingmalaysia.com

The map should represent a modern Philippine urban environment.

It should contain several interconnected areas.

### 13.1 Main city

**The main city contains:**

- Office headquarters.

- Shopping malls.

- Retail shops.

- Restaurants.

- Roads and intersections.

- Public transportation stops.

- Parks.

- Commercial buildings.

- Residential areas.

### 13.2 Shopping malls

Malls are important manning locations.

They should contain NPC visitors, potential clients, retail stores, restaurants, and property promotion booths.

### 13.3 Property showrooms

Each Developer should have designated property galleries.

Players can visit these showrooms to present their company's properties.

**Features:**

- Interactive scale models.

- Property brochures.

- Unit floor plans.

- Interior previews.

- Virtual tours.

- Reservation counters.

### 13.4 Development sites

These are areas where properties are constructed.

**Examples:**

- Condominium construction sites.

- Subdivision developments.

- Hotel construction projects.

- Commercial buildings.

- Resort developments.

These locations can support future construction and development mechanics.

### 13.5 Developer-exclusive locations

**Each Developer should have certain exclusive locations, such as:**

- Exclusive property galleries.

- Private headquarters.

- Company residential projects.

- Exclusive luxury developments.

This helps differentiate each Developer.

## 14. Developer economy and bankruptcy

kpmg.com

The Developer economy is the system that connects all employees and departments.

Every Developer has its own financial account.

**Company funds are used for:**

- Employee salaries.

- Employee commissions.

- Building maintenance.

- Marketing campaigns.

- Property development.

- Operational expenses.

- Equipment.

- Expansion.

- Special projects.

### 14.1 Revenue sources

**Developers generate income through:**

## 1. Completed property sales.

## 2. Property reservations that progress to sales.

## 3. Leasing and rental operations.

## 4. Property management contracts.

## 5. Commercial property income.

## 6. Other approved company business activities.

### 14.2 Expenses

**Developers lose money through:**

- Employee salaries.

- Sales commissions.

- Building maintenance.

- Marketing.

- Construction.

- Administrative expenses.

- Property operations.

- Refunds and cancelled reservations.

### 14.3 Financial management

Executives should receive a company financial dashboard through their tablets.

**The dashboard displays:**

- Total company balance.

- Revenue.

- Expenses.

- Outstanding salaries.

- Monthly sales.

- Reservation value.

- Completed transactions.

- Department budgets.

- Financial projections.

- Bankruptcy risk.

The CFO is responsible for financial management, but major expenditures should require executive approval.

### 14.4 Bankruptcy

A Developer becomes bankrupt when it can no longer meet its financial obligations.

Bankruptcy should not happen simply because a company had a bad day.

The system should monitor financial stability over time.

**Possible warning stages:**
| Status | Description |
| --- | --- |
| Stable | Company has sufficient funds. |
| Financial Warning | Expenses are approaching available revenue. |
| Critical | Company is struggling to meet obligations. |
| Insolvent | Company cannot meet its financial commitments. |
| Bankrupt | Formal company failure and restructuring process. |

### 14.5 Consequences

**When a Developer becomes bankrupt:**

- Salaries may be delayed or suspended.

- New recruitment may be restricted.

- Marketing budgets may be reduced.

- Contracts may not be renewed.

- Employees may resign.

- Management may face performance reviews.

- Company assets may be sold.

- A restructuring process begins.

The game should allow employees to resign and migrate to other Developers.

### 14.6 Developer recovery and Stocking

I propose calling the company rescue system Stocking.

This is where financially successful Developers can invest in struggling Developers.

**A successful Developer may:**

- Purchase company shares.

- Acquire a minority stake.

- Provide emergency funding.

- Finance new developments.

- Acquire company assets.

- Eventually purchase controlling ownership.

**For example:**

Highview is struggling financially.

Another Developer, Crestline, decides to invest in Highview.

Crestline purchases 30% of Highview's company shares.

In exchange, Crestline receives a financial ownership stake and certain shareholder rights.

Highview remains operational, but its ownership structure changes.

If a Developer acquires a controlling stake, the game can introduce corporate takeover mechanics.

This creates competition between companies without making bankruptcy an automatic game-ending event.

## 15. Additional systems and gameplay ideas

These are proposed additions to make ESTATE feel like a complete business simulation rather than a simple workplace roleplay game.

### 15.1 Employee reputation

Every employee should have an individual professional reputation score.

**Reputation can be influenced by:**

- Sales performance.

- Client satisfaction.

- Attendance.

- Completed assignments.

- Teamwork.

- Disciplinary actions.

- Management reviews.

High reputation may improve interview opportunities and promotion eligibility.

### 15.2 Client satisfaction

Every client has a satisfaction rating.

Specialists who provide good service, communicate effectively, and recommend appropriate properties receive better satisfaction scores.

**Poor service can result in:**

- Lost clients.

- Negative company reviews.

- Cancelled reservations.

- Reduced reputation.

### 15.3 Company reputation

Each Developer has an independent reputation score.

**It can be affected by:**

- Property quality.

- Client satisfaction.

- Sales performance.

- Building maintenance.

- Employee conduct.

- Financial stability.

- Successful projects.

A highly reputable Developer may attract more potential clients.

### 15.4 Company announcements

Executives and authorized departments can publish company-wide announcements.

**Examples:**

- New property launches.

- Recruitment openings.

- Monthly sales competitions.

- Company meetings.

- Financial reports.

- Employee awards.

- New branch openings.

Announcements appear on employee tablets and office displays.

### 15.5 Employee awards

**Introduce awards such as:**

- Employee of the Month.

- Top Property Specialist.

- Best Sales Manager.

- Best Performing Department.

- Highest Client Satisfaction.

- Outstanding Leadership.

- Best Developer of the Month.

Awards should be based on measurable performance rather than popularity alone.

### 15.6 Company meetings

Executives and managers can schedule official meetings.

Employees receive meeting notifications and can attend designated conference rooms.

**Meetings can include:**

- Sales reports.

- Financial updates.

- Department planning.

- Company announcements.

- New property presentations.

- Management reviews.

### 15.7 Property launch events

When a Developer introduces a new property, the company can organize a launch event.

Players can attend as employees or guests.

**The event includes:**

- Property presentations.

- Interactive displays.

- Promotional materials.

- NPC visitors.

- Client acquisition opportunities.

- Reservation counters.

### 15.8 Training and certification

Certain positions should require additional training.

**For example:**

Property Specialists complete sales training.

Finance employees complete accounting training.

HR employees complete recruitment training.

Maintenance employees complete safety and maintenance training.

Training can be completed through interactive courses, tests, and practical assignments.

### 15.9 Employee leave

**Employees should be able to request:**

- Vacation leave.

- Emergency leave.

- Medical leave.

- Unpaid leave.

HR processes and approves requests.

Approved leave should prevent the employee from being penalized for missing scheduled shifts.

### 15.10 Inter-Developer competition

**Developers should compete through:**

- Monthly sales rankings.

- Property launch competitions.

- Company reputation.

- Financial performance.

- Employee productivity.

- Development expansion.

- Customer satisfaction.

A global leaderboard can display the top Developers.

Competition should not be limited to individual employee rankings.

## 16. Promotion, management, and authority systems

Management should have meaningful responsibilities.

A player who reaches a managerial position should receive additional tools, not simply a higher salary and a different office.

Sales Managers

**Can:**

- Create employee teams.

- Assign Property Specialists.

- Schedule manning shifts.

- Establish team quotas.

- Review employee performance.

- Recommend promotions.

- Issue warnings.

- Submit termination recommendations.

- Review sales transactions.

Head of Sales

**Can:**

- Manage Sales Managers.

- Establish division-wide quotas.

- Monitor sales performance.

- Organize sales meetings.

- Reassign employees between teams.

- Review monthly reports.

- Recommend department-level promotions.

Department Directors

**Can:**

- Manage their departments.

- Approve departmental schedules.

- Assign budgets within approved limits.

- Review department reports.

- Recommend managerial appointments.

- Report directly to their executive.

Executives

**Can:**

- Approve major operational decisions.

- Establish corporate objectives.

- Review departmental performance.

- Manage company-wide policies.

- Approve major budgets.

- Organize executive meetings.

- Initiate company restructuring.

Board of Directors

**Can:**

- Review CEO performance.

- Approve major acquisitions.

- Approve changes in ownership.

- Establish corporate governance rules.

- Vote on major company decisions.

- Appoint or remove the CEO through authorized procedures.

The game should have a clear permissions system so that employees cannot use tools beyond their authority.

## 17. Settings, optimization, and accessibility

The settings interface should be comprehensive.

The game must prioritize performance because it is designed for large multiplayer servers.

Graphics settings

- Graphics quality.

- Shadow quality.

- Reflections.

- Lighting quality.

- Environmental details.

- NPC rendering distance.

- Character rendering distance.

- Particle effects.

- Visual effects.

- Object detail.

Performance settings

- Reduced NPC animations.

- Reduced distant character rendering.

- Simplified environment rendering.

- Reduced background effects.

- Low-performance mode.

- Automatic optimization.

- Optional reduced UI animations.

Audio settings

- Master volume.

- Music volume.

- Environment volume.

- Interface sound volume.

- Notification sounds.

- Voice chat compatibility settings where supported.

Interface settings

- Tablet position.

- UI scaling.

- Notification preferences.

- Chat preferences.

- Accessibility options.

- Keybind customization.

- Reduced motion.

Gameplay settings

- Automatic tablet opening.

- Interaction preferences.

- Camera sensitivity.

- Character movement preferences.

- Cinematic camera toggle.

The game should use classic, recognizable Roblox-style graphics.

Avoid excessive bloom, heavy motion blur, unnecessary particles, and overly realistic textures.

The objective is to create a clean, presentable, immersive environment that performs well on different devices.

## 18. Visual direction and atmosphere

Corporate interiors

Clean, modern, spacious, professional.

Property showrooms

Elegant, interactive, realistic layouts.

City environment

Lively, populated, recognizable urban setting.

User interface

Readable, organized, responsive, functional.

**The visual direction should follow these principles:**

## 1. Classic Roblox-inspired graphics.

## 2. Modern architectural designs.

## 3. Clean and readable interfaces.

## 4. Smooth but restrained animations.

## 5. Realistic-looking corporate environments without excessive graphical complexity.

## 6. Consistent company branding.

## 7. Distinct visual identities for each Developer.

The game should not look like a futuristic sci-fi simulator.

It should feel like a modern Philippine corporate environment recreated inside Roblox.

## 19. Developer customization and identity

Each Developer should have a customizable corporate identity.

The CEO and authorized executives can manage approved company branding.

**Customizable elements:**

- Company logo.

- Company name.

- Corporate colors.

- Employee uniforms.

- Office decorations.

- Property advertisements.

- Company slogan.

- Company announcements.

- Property showroom design.

Developers should also have different architectural styles.

**For example:**
| Developer | Identity |
| --- | --- |
| Highview | Modern luxury residential developments |
| Crestline | Premium condominiums and commercial properties |
| Northstar | Affordable housing and residential communities |
| Aurelia | Luxury hotels, resorts, and exclusive estates |
| Grandstone | Mixed-use developments and commercial buildings |

These are fictional examples, not real-world company affiliations.

## 20. Property development system

This is a proposed major expansion that can make ESTATE much deeper.

Instead of Developers only selling predetermined properties, they should eventually be able to participate in developing new properties.

**The development process:**

## 1. Business Development identifies a potential project.

## 2. Market Research evaluates the location.

## 3. Strategy prepares a development proposal.

## 4. Finance evaluates the proposed budget.

## 5. Executives review the proposal.

## 6. The Board approves major developments.

## 7. The Developer acquires the project.

## 8. Construction begins.

## 9. Marketing prepares the launch.

## 10. Sales Specialists begin accepting reservations.

Development categories

- Residential subdivisions.

- Condominium towers.

- Luxury hotels.

- Commercial complexes.

- Shopping malls.

- Office buildings.

- Mixed-use developments.

Development management

**Projects should have:**

- Construction budgets.

- Development schedules.

- Required approvals.

- Project managers.

- Construction progress.

- Property specifications.

- Launch dates.

- Expected revenue.

This system should be introduced after the core sales and employment mechanics are stable.

## 21. Property leasing and rental operations

Not every property transaction needs to be a sale.

Developers should also be able to generate recurring income through rentals.

**For example:**

A Developer owns a commercial building with several available units.

Leasing Officers handle tenant applications and negotiate rental agreements.

The company receives rent payments periodically.

This creates another revenue stream that does not depend entirely on property sales.

**Possible rental properties:**

- Condominiums.

- Commercial spaces.

- Retail units.

- Office spaces.

- Luxury residences.

- Hotel rooms.

## 22. Banking and personal finances

Every player should have a personal bank account separate from the Developer's corporate account.

**The tablet's Banking application should display:**

- Current balance.

- Salary deposits.

- Commission deposits.

- Transaction history.

- Pending payments.

- Employment earnings.

- Approved transfers.

Players should be able to visit physical bank branches as an alternative interface.

Salary system

Salaries should be processed according to employment contracts.

**Possible compensation structure:**

- Fixed salary.

- Sales commission.

- Performance bonus.

- Management allowance.

- Overtime compensation.

- Special incentives.

The salary amount should depend on the position, company financial condition, and approved employment contract.

## 23. Quotas and employee performance

Every department should have measurable objectives.

This makes employees accountable and gives managers a genuine reason to manage their teams.

**Examples:**
| Position | Possible performance requirements |
| --- | --- |
| Property Specialist | Acquired clients, follow-ups, reservations, sales |
| Senior Specialist | Sales performance and junior employee mentorship |
| Sales Manager | Team sales, client acquisition, employee attendance |
| Head of Sales | Division revenue and team performance |
| HR Specialist | Recruitment processing and contract renewals |
| Accountant | Financial accuracy and transaction records |
| Marketing Specialist | Campaign completion and client engagement |
| Maintenance Staff | Completed work orders and inspection results |
| Customer Service Representative | Client satisfaction and resolved concerns |

Quotas should be configurable.

A Sales Manager should not be able to impose impossible targets without considering employee availability and company conditions.

The game should also distinguish between individual quotas and team quotas.

## 24. Core gameplay loop

This is how the different systems connect during normal gameplay.

The employee gameplay cycle

## 1. Join a Developer

   The player enters their assigned company and checks their employment status.

## 2. Check the employee tablet

   Review schedules, announcements, assignments, and available tasks.

## 3. Report to the department

   Employees attend their designated offices or manning locations.

## 4. Perform assigned duties

   Specialists find clients, finance processes payments, HR recruits employees, and managers oversee operations.

## 5. Complete business transactions

   Clients reserve or purchase properties. Departments cooperate to process the transactions.

## 6. Receive compensation

   Salaries, commissions, and bonuses are processed according to contracts.

## 7. Evaluate performance

   Managers review results, employees gain experience, and eligible players may receive promotions.

## 8. Expand the company

   Successful Developers invest in new projects, hire more employees, and compete with other companies.

## 25. Anti-abuse and administrative systems

Because ESTATE relies heavily on player-managed companies, its administrative systems must be designed carefully.

**The following protections are important:**

Employment protection

- Only authorized employees can hire or terminate other employees.

- Promotions must meet documented requirements.

- Players cannot bypass position restrictions.

- Contracts must be verified by the server.

Financial protection

- All financial transactions must be server-authoritative.

- Company funds must be separated from personal funds.

- Executive withdrawals must have authorization requirements.

- Commission calculations must be validated.

- Transactions must have permanent records.

Management protection

- Managers cannot arbitrarily remove employees without a documented process.

- Executives can be investigated for misuse of authority.

- Board decisions should require appropriate voting procedures.

- Employees should have access to an appeal process.

Client protection

- Each client should have a unique transaction record.

- One client cannot purchase the same unit multiple times.

- Reservations should have expiration dates.

- Duplicate commissions must be prevented.

- Completed transactions cannot be modified without authorization.

Anti-exploit protection

- Employment and financial validation must happen on the server.

- Remote events must validate permissions.

- Client interfaces must never be trusted as proof of a transaction.

- Important records must be saved reliably.

## 26. Roblox technical architecture

ESTATE is a large-scale multiplayer experience. Its technical architecture should be designed around persistence, scalability, and security from the beginning.

### 26.1 Data persistence

**The following information should be saved:**

Player data

- Character identity.

- Employment history.

- Developer affiliation.

- License information.

- Position and contract.

- Level and experience.

- Personal finances.

- Client database.

- Sales records.

- Certifications.

- Disciplinary records.

Developer data

- Company identity.

- Employee registry.

- Organizational structure.

- Department assignments.

- Corporate finances.

- Properties.

- Reservations.

- Transactions.

- Budgets.

- Contracts.

- Management records.

- Company reputation.

- Ownership and shares.

### 26.2 Data organization

**The development team should separate the following systems into independent modules:**

ESTATE

```text
|

+-- Core

|   +-- PlayerData

|   +-- DeveloperData

|   +-- Employment

|   +-- Permissions

|   +-- Persistence

|

+-- Gameplay

|   +-- CharacterCreation

|   +-- Recruitment

|   +-- Departments

|   +-- Positions

|   +-- Promotions

|   +-- Scheduling

|

+-- Business

|   +-- Properties

|   +-- Clients

|   +-- CRM

|   +-- Reservations

|   +-- Transactions

|   +-- Leasing

|   +-- Development

|

+-- Economy

|   +-- Banking

|   +-- Payroll

|   +-- Commissions

|   +-- CompanyFunds

|   +-- Bankruptcy

|   +-- Stocking

|

+-- Interface

|   +-- MainMenu

|   +-- Tablet

|   +-- Notifications

|   +-- Chat

|   +-- Settings

|

+-- World

|   +-- Headquarters

|   +-- City

|   +-- Malls

|   +-- Showrooms

|   +-- NPCs

|

+-- Security

    +-- Validation

    +-- AuditLogs

    +-- AntiExploit

    +-- Moderation
```

This is a logical architecture, not a requirement to place every system in one script or folder.

Each module should have clear responsibilities and interfaces.

### 26.3 Large-server considerations

The 100+ player target is ambitious.

It should be treated as a performance target rather than an unconditional promise.

**The game should use:**

- Server-authoritative gameplay.

- Efficient NPC spawning.

- Controlled NPC population.

- StreamingEnabled where appropriate.

- Optimized character models.

- Limited unnecessary physics.

- Efficient network communication.

- DataStoreService for persistent information.

- MemoryStoreService for suitable temporary cross-server information.

- MessagingService for cross-server announcements and coordination where appropriate.

A Developer's persistent identity must be separated from an individual Roblox server instance.

Otherwise, a company could accidentally have multiple disconnected financial records or conflicting employee assignments.

### 26.4 Important architecture decision: Developer identity

A Developer should exist as a persistent company entity.

A Roblox server should be considered an operating instance of that Developer, not the Developer itself.

**For example:**

DEVELOPER: HIGHVIEW

```text
|

+-- Persistent Company Data

|   +-- Employees

|   +-- Finances

|   +-- Properties

|   +-- Management

|   +-- Transactions

|

+-- Server Instance A

|   +-- Employees currently online

|

+-- Server Instance B

|   +-- Employees currently online

|

+-- Server Instance C

    +-- Employees currently online
```

This architecture allows a Developer to potentially operate across multiple Roblox server instances while maintaining one company identity.

It also makes it possible to coordinate company-wide schedules, employee records, and financial information.

### 26.5 Security and data consistency

Certain operations must be atomic or otherwise protected against conflicting requests.

**For example:**

If two Property Specialists attempt to reserve the same condominium unit at almost the same time, only one reservation should succeed.

Likewise, salary payments should never be duplicated simply because an employee reconnects or a server restarts.

All important operations should have unique transaction identifiers and appropriate validation.

## 27. Development roadmap

ESTATE is a large project. Attempting to implement everything simultaneously would make development difficult and increase the risk of broken systems.

I recommend developing the game in phases.

## Phase 1 — Foundation

Highest priority

- Main menu and cinematic camera.

- Developer selection.

- Character creation.

- Employee registration.

- Employment persistence.

- Basic headquarters.

- Basic HR recruitment.

- Employee tablet.

- Position and permission framework.

## Phase 2 — Employment and departments

- Organizational hierarchy.

- Employee contracts.

- Salary system.

- Promotion system.

- Resignation and termination.

- Department offices.

- Managerial tools.

- Attendance and scheduling.

## Phase 3 — Real estate operations

- Property catalog.

- NPC client system.

- Manning locations.

- Client interactions.

- Client database.

- Calling rooms.

- Reservation system.

- Property transaction system.

- Sales commissions.

## Phase 4 — Company economy

- Corporate banking.

- Personal banking.

- Payroll.

- Company expenses.

- Financial reports.

- Developer reputation.

- Bankruptcy.

- Stocking and acquisitions.

## Phase 5 — Advanced roleplay

- Moonlighting.

- Legal investigations.

- Leasing.

- Property management.

- Marketing campaigns.

- Employee training.

- Company events.

- Property development.

## Phase 6 — Expansion and optimization

- Additional Developers.

- Larger city map.

- New property catalogs.

- Additional headquarters.

- Cross-server company coordination.

- Advanced NPC behavior.

- Performance optimization.

- Public release preparation.

The first playable version should focus on the employment system, property sales, and basic company operations.

Those three systems are the foundation of the entire experience.

## 28. Essential design principles

The following principles should guide every future addition to ESTATE.

## 1. Every position must matter.

No employee should exist solely to fill an organizational chart. Each role must have meaningful responsibilities and gameplay.

## 2. Sales generate the company's livelihood.

Property Specialists are essential. The company should not function without actual client acquisition and sales activity.

## 3. Management requires responsibility.

Higher positions should come with greater authority and greater accountability.

## 4. Progression must be earned.

Levels help unlock opportunities, but experience, performance, qualifications, and interviews determine promotions.

## 5. The company belongs to its entire workforce.

A successful Developer is the result of cooperation between employees, managers, and executives.

## 6. The economy must be interconnected.

Sales, commissions, payroll, expenses, reservations, and bankruptcy should affect one another.

## 7. Every Developer should feel different.

Different companies should have different properties, buildings, identities, and corporate strategies.

## 8. Roleplay must emerge naturally from gameplay.

Employees should have reasons to communicate, meet, collaborate, negotiate, and work together.

## 9. Do not overcomplicate basic interactions.

Complex corporate systems should still be accessible through intuitive interfaces.

## 10. Performance comes before visual excess.

A large multiplayer environment needs efficient systems more than unnecessary graphical effects.

## 29. Final vision

emiratesnbdresearch.com

ESTATE should ultimately become a multiplayer corporate simulation where players experience the operation of a real estate development company from the perspective of an actual employee.

A player might begin as a Junior Property Specialist, spend time acquiring clients, become a successful Property Specialist, lead a sales team, eventually manage an entire sales division, and perhaps become an executive.

Another player might begin in Human Resources and eventually become HR Manager.

Another might work in Finance, handling company budgets and payroll.

Meanwhile, other players are responsible for the company's properties, maintenance, marketing, legal operations, and corporate strategy.

Every role contributes to the same objective: keeping the Developer operational, profitable, and competitive.

The most important distinction between ESTATE and conventional company roleplay games is that the company itself is the gameplay.

It is not simply a building full of employees with different titles.

It is an interconnected business simulation where individual actions have consequences for the entire organization.

ESTATE

Build your career. Grow your company. Own the market. SOME CONFIGURED SYSTEMS: PART 2

Design decisions incorporated

 November 1, 2026

These decisions establish a much clearer direction for ESTATE. In particular, I agree with prioritizing the office before the open world.

Instead of immediately building an enormous city, we can make the headquarters a fully functioning workplace first. Players should already have plenty of things to do without needing a large map.

**I've also identified two major gameplay additions from your instructions:**

## 1. Property Inventory System — Specialists must find the most suitable available property for every client.

## 2. Online Sales System — Specialists can generate leads through company marketing content and handle clients remotely, without physically meeting NPCs.

Below is the revised specification.

System

Finalized decision

Developer architecture

One Developer initially

Commission

10–25% of total property price

Employment contracts

Custom duration per position

Moonlighting

Investigation, HR hearing, possible license revocation

Company ownership

Board-controlled

NPC generation

Hybrid system

Initial map

Office headquarters first

Maximum server population

100 players

Property Specialist employee limit

No separate position cap

Currency

Ledger (LDG), pronounced "Ledge"

For the first version, ESTATE will have only one playable Developer.

We will use Highview Development as the initial example company.

The Developer architecture should still be designed so additional companies can be introduced later without rewriting the entire game.

However, we will not spend development time implementing multiple companies yet.

**The initial focus is:**

- One company identity.

- One headquarters.

- One organizational structure.

- One property catalog.

- One company bank account.

- One employee registry.

- One company management structure.

Target: 100 players

The initial target is 100 concurrent players per server.

There will be no separate employee limit for Junior Property Specialists or Property Specialists.

**For example, the company may have:**

- 2 CEOs or executives where appropriate to the organizational structure.

- 5 Sales Managers.

- 15 Senior Property Specialists.

- 60 Property Specialists.

- 18 Junior Property Specialists.

These are illustrative employee counts, not fixed limits.

The only immediate restriction is the server's total player capacity.

Management positions can have vacancy limits, while lower-level sales positions remain open for recruitment.

OFFICIAL GAME CURRENCY

Pronunciation: Ledge

Currency specifications

- Full name: Ledger

- Abbreviation: LDG

- Spoken name: Ledge

- Currency type: Virtual in-game currency

Ledger is the universal currency of ESTATE.

**It will be used for:**

- Employee salaries.

- Property commissions.

- Property purchases.

- Reservation payments.

- Company revenue.

- Company expenses.

- Marketing budgets.

- Construction budgets.

- Investments and acquisitions.

- Personal banking.

All financial transactions should be recorded in a ledger-style transaction history.

**For example:**

```

TRANSACTION RECORD

Employee: John Smith

Transaction: Property Commission

Property: Highview Residences

Unit: Studio - 60 SQM

Property Value: LDG 34,000,000

Commission Rate: 15%

Commission Earned: LDG 5,100,000

Status: PROCESSED

```

The game should use whole-number Ledger amounts for simplicity.

A distinction must also exist between a company's total sales value and its actual available cash. A property worth LDG 34 million does not mean the company immediately receives LDG 34 million in cash.

Major gameplay system

[接待中心香氛設計：縮短成交週期的嗅覺策略 — Scenter Insights]\(https\://images.openai.com/static-rsc-4/UOdEOgIxdYc9c5YSLOT9lDSSSLayXxKuFeDobu2LHwn4kwPJ8Iae3sgWJrvT6C4fmE9_x1Z-hOlJmvkXK4cDn29IeFCKag9FM4aZIX7Yf6BuC_JPMOZT6x6p-3a6ZaTyuol3ToE5HxYQIZYmKIKSC3UqQjhHFh0mxQFmFwwAkcY?purpose=inline)

[scenter.tw]\(https\://www.scenter.tw/insights/real-estate-sales-center-scent-design/?utm_source=chatgpt.com)

This is one of the most important additions to ESTATE.

Every Developer has an official inventory containing all available property units.

The inventory is accessible through the employee tablet, with additional permissions depending on the employee's position.

The system should not simply display a list of properties. It should function as a real inventory management tool.

**The inventory will be separated into:**

Category

Examples

Residential

Houses, subdivisions, townhouses

Condominium

Studio, 1BR, 2BR, 3BR, penthouse

Luxury

Premium residences, exclusive estates

Commercial

Retail spaces, offices, commercial units

Hospitality

Hotel rooms, hotel properties, resorts

Land

Residential lots, commercial lots

Every available unit should have its own unique identification number.

**Example:**

```

HIGHVIEW PROPERTY INVENTORY

|

+-- HIGHVIEW RESIDENCES

|   |

|   +-- STUDIO UNITS

|   |   +-- HVR-S-001

|   |   +-- HVR-S-002

|   |   +-- HVR-S-003

|   |

|   +-- ONE BEDROOM

|   |   +-- HVR-1B-001

|   |   +-- HVR-1B-002

|   |

|   +-- TWO BEDROOM

|       +-- HVR-2B-001

|       +-- HVR-2B-002

|

+-- HIGHVIEW HEIGHTS

|   |

|   +-- STUDIO UNITS

|   +-- ONE BEDROOM

|   +-- TWO BEDROOM

|

+-- HIGHVIEW ESTATES

    |

    +-- RESIDENTIAL LOTS

    +-- HOUSE AND LOT

```

**Each unit should contain:**

- Unit ID.

- Development name.

- Property type.

- Floor area.

- Floor number, where applicable.

- Number of bedrooms.

- Number of bathrooms.

- Selling price.

- Reservation fee.

- Availability.

- Property status.

- Payment options.

- Location.

- Property images.

- Floor plan.

Every unit must have a status.

Status

Meaning

Available

Can be offered to clients.

Reserved

Temporarily secured by a client.

Pending

Transaction is being processed.

Sold

Successfully purchased.

Blocked

Unavailable for administrative reasons.

A reserved unit should not be offered as available to another client.

If a reservation expires or is cancelled, the unit can return to the available inventory after the appropriate verification.

**The Property Specialist's tablet should have a dedicated application called:**

PROPERTY INVENTORY

[Real Estate CRM And Listing Management Template | Tadabase]\(https\://images.openai.com/static-rsc-4/\_ISdgiRXb5FmeprsJwibuFh8Oz-kG_BCZ0VpZkJWrasWtl6sewUcyhzQm7XP7pneCQnhkogjWFsEStwKdOSLcvBhFfsRdZBdhG0Z0J6YJ_xupkUyoOJYQOWhXCoKDW-ApaWmzejJS9yetXRer9wn-CtlCkgy0CPEKzN_ksJwzEs?purpose=inline)

[tadabase.io]\(https\://tadabase.io/template-apps/real-estate-crm-template?utm_source=chatgpt.com)

**Features:**

- Browse all available developments.

- Search by property name.

- Filter by price.

- Filter by unit type.

- Filter by floor area.

- Filter by bedroom count.

- Check availability.

- View property photographs.

- View floor plans.

- Compare different units.

- View reservation fees.

- Check payment arrangements.

However, the most important feature is the client matching function.

Whenever a Property Specialist acquires a client, the specialist should identify a suitable property.

**For example:**

**A client approaches a Property Specialist and provides the following information:**

```

CLIENT PROFILE

Name: Michael Anderson

Budget: LDG 30M - 40M

Preferred Property: Condominium

Floor Area: 50 - 70 SQM

Bedrooms: Studio or 1BR

Preferred Location: Central Business District

Purpose: Personal Residence

```

The specialist opens the inventory and searches for matching units.

**The system identifies:**

```

MATCHING INVENTORY

1. Highview Residences

   Studio - 60 SQM

   LDG 34,000,000

   AVAILABLE

   MATCH: EXCELLENT

2. Highview Heights

   1 Bedroom - 65 SQM

   LDG 38,000,000

   AVAILABLE

   MATCH: EXCELLENT

3. Highview Towers

   Studio - 45 SQM

   LDG 27,000,000

   AVAILABLE

   MATCH: GOOD

```

The specialist then presents the available options.

This is a particularly important mechanic.

A client should be more likely to proceed when the offered property matches their actual requirements.

**The game should consider:**

- Budget compatibility.

- Property type.

- Location preference.

- Floor area.

- Bedroom requirements.

- Payment arrangements.

- Client preferences.

An unsuitable property should have a lower chance of closing.

A well-matched property should have a higher chance of closing.

However, the specialist should not receive a guaranteed sale just by selecting the highest matching score. Client personality, purchase intention, timing, and other factors should also influence the result.

The objective is to reward specialists who understand their clients rather than those who simply spam property offers.

Major gameplay system

[Gérer ses liens sur les réseaux sociaux : le guide complet pour 2026 | LinkDash]\(https\://images.openai.com/static-rsc-4/h2-IiTI2SaA0N3LDsZ-7co4MZeXsRRiOqA59CYAUXfi6jJShMe8JN0inFRA7KjsC72vub_TO-HZz9tYAyxg-zyG1Ph4aeQAua07GVYzY4lTS1sS5TI6IOW-S926el90EaotoJLt13K7wmV6gJeey5BTUMAvJ-AqujnNBAZbYcQQ?purpose=inline)

[linkdash.eu]\(https\://linkdash.eu/fr/blog/social-media-links-beheren?utm_source=chatgpt.com)

This is another major feature that makes ESTATE different.

Property Specialists should not be limited to physically meeting NPCs.

They can also generate clients through the company's online marketing operations.

This represents the modern real estate sales process, where potential buyers discover properties through advertisements, social media, and online inquiries.

The Marketing Department produces official promotional content.

**Content Creators are responsible for preparing:**

- Property photographs.

- Promotional videos.

- Condominium tours.

- Property brochures.

- Development announcements.

- Promotional posters.

- Property advertisements.

- Virtual showroom presentations.

These materials become available to Property Specialists through the tablet.

A Content Creator creates the material once, and authorized specialists can use the published material for online selling.

This creates a connection between Marketing and Sales.

**The Property Specialist receives a tablet application called:**

ONLINE SALES

[10 Best Lead Generation Strategies for Real Estate]\(https\://images.openai.com/static-rsc-4/vWw1IiZd4EqKkV87iAUS_XyiCgDGW1grXNgPR11TYwwI-mfU0_E8FdFyB2a2k9T3R-trmM6ucz2fdAjXySGpHYtR5jJGpHnNP0_JEFyTeiXpgj5-obCBeuuAz2jJ0MEA836peUlPYezwgkPN6H5gQ6bP6f_tB75Y59w6Rn_15po?purpose=inline)

[campaigncreators.com]\(https\://www.campaigncreators.com/blog/10-best-lead-generation-strategies-for-real-estate?utm_source=chatgpt.com)

**The application contains several sections:**

Section

Function

Content Library

Displays official marketing materials.

Advertisements

Allows specialists to select content for promotion.

Active Campaigns

Displays currently active promotions.

Online Leads

Shows incoming potential clients.

Inquiries

Displays client questions and messages.

Analytics

Displays views, inquiries, and lead conversions.

Performance

Tracks the specialist's online sales results.

Property Specialists can select official company content and promote it through the in-game online platform.

**The specialist chooses:**

## 1. Property to advertise.

## 2. Promotional content.

## 3. Target audience.

## 4. Campaign duration.

## 5. Advertising budget.

For the initial version, the advertising budget can be deducted from the employee's assigned marketing allowance or approved company budget.

The employee should not be able to spend unlimited company money.

A Property Specialist selects a promotional video for Highview Residences.

They launch an advertising campaign.

The game simulates the advertisement reaching potential buyers.

**Depending on the campaign's effectiveness, it generates:**

- Advertisement views.

- Property inquiries.

- Interested clients.

- Qualified leads.

- Potential reservations.

Higher-performing content and suitable audiences should produce better results.

The Content Creator's work should also receive performance recognition based on how well their content generates engagement and leads.

When an interested NPC responds to an advertisement, the Property Specialist receives an incoming notification.

**Example:**

NEW ONLINE INQUIRY

Incoming

[Are Ai Headshots Safe]\(https\://images.openai.com/static-rsc-4/f4CtL9aHeBSEyxQf9eVW7baQAoUs5m7tZVYV2Cm2U2z3XVoFeLYtgizkNrPlas5GFmKQgNxO_7sbSWSz9cny_G1VYwxrbCaPf9zhHm9DPTHOtM4QURmKXklZRmGURuFYrh5xhOH3BR-ZGD4bnEZCsLMd1Yq1mg_4QUjEcSoG5iU?purpose=inline)

Michael Anderson

Highview Residences advertisement

Online inquiry · Just now

Hello! I saw your advertisement for Highview Residences. Do you have any available studio units?

Illustrative game interface

The specialist can respond through the tablet's online messaging system.

**They can:**

- Introduce themselves.

- Answer questions.

- Share property photographs.

- Send floor plans.

- Recommend available units.

- Schedule a viewing.

- Request client information.

- Proceed with a reservation.

Once the client provides their information and expresses serious interest, the specialist can add them to their CRM database.

Both systems should use the same underlying client and property transaction systems.

Feature

On-site sales

Online sales

Client discovery

NPCs physically visit locations

NPCs respond to advertisements

Interaction

In-person dialogue

Tablet messaging

Property presentation

Showroom or physical presentation

Images, videos, floor plans

Client information

Acquired during interaction

Acquired through online inquiry

Inventory

Same central inventory

Same central inventory

Follow-ups

Calling room

Online messages and calls

Reservation

Same reservation system

Same reservation system

Commission

Same commission rules

Same commission rules

The online system should not automatically be more profitable than on-site selling.

Each should have advantages.

On-site selling offers immediate interaction and physical presentations.

Online selling offers wider reach and the ability to handle leads while inside the office.

Your hybrid approach is a good direction.

NPCs should not appear randomly everywhere without purpose.

Their spawning should be connected to player activity and suitable locations.

**NPC clients can appear in:**

- Shopping malls.

- Property showrooms.

- Sales galleries.

- Condominium viewing areas.

- Designated sales booths.

- Office reception areas.

However, NPCs should only spawn when there is at least one eligible Property Specialist nearby or assigned to the relevant location.

This prevents unnecessary NPC processing when nobody is available to interact with them.

The office should occasionally receive potential clients.

However, this should be relatively rare.

**Possible locations:**

- Main reception.

- Property showroom.

- Sales department reception.

- Designated client consultation area.

Office NPCs should only spawn if there are available Property Specialists who can attend to them.

The office should not become flooded with NPCs.

Online leads should be generated through active marketing campaigns.

**The system evaluates:**

- Campaign effectiveness.

- Advertised property.

- Audience preferences.

- Advertising duration.

- Marketing budget.

- Available campaign reach.

A campaign can generate inquiries even when the specialist is not physically standing at a manning location.

However, incoming leads should be assigned or claimed by available specialists to prevent duplicate ownership.

**The proposed rules:**

```

CLIENT GENERATION SYSTEM

|

+-- ON-SITE CLIENTS

|   |

|   +-- Check designated location

|   +-- Check specialist presence

|   +-- Check available NPC capacity

|   +-- Generate suitable client

|

+-- OFFICE CLIENTS

|   |

|   +-- Check office client areas

|   +-- Check available specialists

|   +-- Apply rare spawn probability

|

+-- ONLINE CLIENTS

    |

    +-- Check active advertisements

    +-- Check campaign effectiveness

    +-- Generate online inquiries

    +-- Assign or claim lead

```

If no eligible Property Specialist is available, the game should stop generating new on-site and office clients.

Existing online inquiries should remain saved until someone can handle them.

This prevents clients from disappearing just because their assigned employee left the game.

This is where the inventory, online sales, on-site sales, and client systems come together.

## 1. Receive assignment

   The specialist checks their tablet for schedules, manning assignments, and online sales opportunities.

## 2. Generate or acquire clients

   The specialist either meets an NPC in person or receives an online inquiry through a marketing campaign.

## 3. Collect client information

   The specialist learns the client's budget, preferences, property requirements, and contact details.

## 4. Open Property Inventory

   The specialist searches for suitable units from the company's available inventory.

## 5. Match and present units

   The specialist selects appropriate properties and sends photographs, floor plans, pricing, and other information.

## 6. Follow up

   The client may request more information, schedule a viewing, or consider purchasing.

## 7. Reservation or direct purchase

   The specialist submits the transaction through the tablet.

## 8. Coordinate with other departments

   Sales Management, Finance, Legal, and Customer Experience help process the transaction.

## 9. Complete the transaction

   The unit is marked sold after successful payment verification and completion.

## 10. Receive commission

    The specialist receives their percentage of the property's total selling price according to the commission agreement.

This loop should be the first fully playable business system in ESTATE.

The commission is calculated using the property's total selling price.

**For example:**

Property transaction

HIGHVIEW RESIDENCES · STUDIO · 60 SQM

Commission rate

Specialist earns

10%

LDG 3,400,000

15%

LDG 5,100,000

20%

LDG 6,800,000

25%

LDG 8,500,000

The Property Specialist receives the commission according to their transaction agreement.

Other employees may receive additional shares from the separately allocated sales commission pool.

Important accounting distinction: The total specialist commission and the commission shares allocated to supporting employees must be accounted for separately. We should not accidentally deduct the same commission twice.

Also, the company must not treat a reservation request as a completed sale. Commission eligibility should be tied to verified transaction milestones, with final payment following the company's commission policy.

Each position will have its own contract duration.

There will no longer be one universal renewal period.

**Example:**

Position

Example contract duration

Junior Property Specialist

30 days

Property Specialist

60 days

Senior Property Specialist

90 days

Sales Manager

90 days

Department Director

120 days

Executive

180 days

These are suggested starting values, not final requirements.

Contracts should be configurable by authorized HR management.

**The system should automatically:**

- Notify employees before expiration.

- Notify HR about upcoming renewals.

- Generate renewal documents.

- Allow authorized HR officers to renew contracts.

- Record contract changes.

- Suspend position salary eligibility when contracts expire.

An employee's license remains separate from their position contract.

Moonlighting will no longer result in automatic punishment upon detection.

Instead, it will have a proper investigation and HR hearing.

**Proposed process:**

```

MOONLIGHTING DETECTED

|

+-- Compliance Officer investigates

|

+-- Evidence is collected

|

+-- Investigation report submitted

|

+-- HR reviews the case

|

+-- Employee receives hearing notification

|

+-- Employee attends HR hearing

|

+-- Authorized decision is made

    |

    +-- Case dismissed

    |

    +-- Official warning

    |

    +-- Contract termination

    |

    +-- License revocation

          |

          +-- Temporary game restriction

```

The employee should have the opportunity to respond to allegations.

This creates actual gameplay for HR, Legal, and Compliance instead of making the system a simple automatic punishment mechanic.

The Developer will be governed by its Board of Directors.

The CEO manages the company operationally, but the Board retains authority over major corporate decisions.

**The Board should have control over:**

- Appointment and removal of the CEO.

- Major acquisitions.

- Company ownership changes.

- Major corporate restructuring.

- Approval of exceptional financial decisions.

- Company-wide strategic direction.

The Board should not need to approve every ordinary operational decision.

For example, a Sales Manager should not need Board approval to assign a Property Specialist to a mall.

This separation keeps the company manageable.

New development priority

[AB Foods stock steady as Primark separation plans reshape investor focus]\(https\://images.openai.com/static-rsc-4/-tOFgfgDEbXM1yZ6SaCezzoZ6qojJ_6RFd31ANeZ_jPhHa3gak_jAmgARf2Xm_DDlDE1uYIgcDwoQlzK1G4EFA9-\_mAmFv0MpN-IfB3b6BIn3jXh7UmN1aI4lhSlpsvmt-eDUJBgulYHYxMtkCT2N5pXRmJYXFI3DD9vxChyawM?purpose=inline)

[ad-hoc-news.de]\(https\://www.ad-hoc-news.de/boerse/news/corporate-news/ab-foods-stock-steady-as-primark-separation-plans-reshape-investor-focus/70017267?utm_source=chatgpt.com)

I recommend changing the development order.

Instead of constructing the entire city immediately, we should build a complete office environment first.

**The initial playable map should contain:**

ESTATE — Initial playable headquarters

[Business center lobby design concept :: Behance]\(https\://images.openai.com/static-rsc-4/YsgEodcjZEowtgbvwzrYJdOD9PMLa2xC6wi2PEk7S7fCIxmLWXjv9-KTr-6jn4woCjJAOGVVGclHYbdKLlrsrWf7sBnBbmmQx9Mao-MwhzV1PXuRBP3j6XqZdeP2NEuFttBL7X2bm2LMQwqWJ638OdSx_OeYYDI41eTl0IikTYY?purpose=inline)

[behance.net]\(https\://www.behance.net/gallery/146940385/Business-center-lobby-design-concept?utm_source=chatgpt.com)

## 1. Main lobby and reception.

## 2. Human Resources recruitment office.

## 3. Employee clothing and customization area.

## 4. Sales department.

## 5. Sales management offices.

## 6. Calling rooms.

## 7. Property inventory showroom.

## 8. Marketing department.

## 9. Finance and accounting.

## 10. Legal and compliance.

## 11. Customer relations.

## 12. Executive offices.

## 13. Boardroom.

## 14. Employee lounge.

The initial office should be large enough to feel like a genuine corporate headquarters, but not unnecessarily enormous.

Each department should have interactive objects and functional workstations.

**For example:**

- HR has recruitment computers.

- Sales has employee desks and client consultation rooms.

- Finance has payment processing counters.

- Marketing has content creation workstations.

- Executives have corporate dashboards.

- The Boardroom has meeting and voting interactions.

The office itself should provide enough gameplay to keep players occupied before the open-world city is developed.

Based on your decisions, I would now arrange ESTATE's development roadmap differently.

Priority

System

Importance

1

Main menu and character creation

Essential

2

Developer and employee persistence

Essential

3

HR recruitment and employment

Essential

4

Organizational positions and permissions

Essential

5

Office and department environments

Essential

6

Employee tablet

Essential

7

Property inventory

Essential

8

NPC client generation

Essential

9

Client CRM and matching

Essential

10

On-site and online sales

Essential

11

Reservations and transactions

Essential

12

Commission and Ledger banking

Essential

13

Management and promotion

High

14

Finance and company bankruptcy

High

15

Moonlighting and investigations

Medium

16

Open-world city

Later

17

Additional Developers

Later

Every employee has their own personal office, with customization and upgrade options depending on their position and available funds.

A. Office Ownership and Upgrades

- Every employee receives their own office upon obtaining an eligible position.

- Office size can be upgraded using Ledger (LDG).

- Higher office sizes provide more space for furniture, decorations, and additional features.

- Office upgrades and purchases are permanent unless the player changes positions or the office is reassigned under company rules.

B. Furniture & Decoration

- Employees can customize their offices using furniture and decorations purchased through the in-game tablet.

- Purchases use the player's Ledger balance.

- Possible items include:

- Desks, chairs, and meeting tables

- Sofas and lounge furniture

- Cabinets, shelves, and storage

- Computers, monitors, and office equipment

- Plants, paintings, clocks, and decorations

- Lighting, flooring, and wall designs

- Furniture placement should be customizable, allowing employees to arrange their offices according to their preferences.

C. Employee Summoning & Meeting Invitations

- Positions with management responsibilities can summon their direct employees to their offices.

- Employees can still request meetings with other employees, regardless of department or position, through an email invitation system on their tablet.

- Invitations include the meeting subject, participants, date, time, and location.

- Invited employees receive an email or tablet notification and can respond to the invitation.

D. Public Meetings & Assigned Seating

- Every employee must have an assigned seat for public company meetings.

- Invited participants must also have designated seats.

- The seating system should recognize each attendee and display their assigned seat.

- Meeting organizers can arrange seating according to departments, positions, or meeting requirements.

Important distinction: Personal offices are private workspaces, while public meetings take place in shared company meeting rooms, conference halls, or boardrooms.

This adds a new layer of office ownership, personalization, and professional interaction to ESTATE.

There are five systems I strongly recommend adding to the design.

A. Lead ownership

When a Property Specialist acquires a client, that client should be registered under their employee account.

Other specialists cannot simply take over the client.

Managers can reassign clients under specific circumstances, such as inactivity, resignation, or approved transfers.

This prevents players from stealing one another's commissions.

B. Client appointment calendar

Specialists should be able to schedule appointments with clients.

**Appointments appear on their tablet calendar and can include:**

- Property viewing.

- Online consultation.

- Follow-up calls.

- Reservation meetings.

- Document signing.

This gives clients a purpose beyond random conversations.

C. Unit reservation locks

When a client submits a reservation request, the system should temporarily lock the selected unit while Finance verifies the transaction.

This prevents two specialists from selling the same unit simultaneously.

D. Employee productivity dashboard

**Managers should see actual employee contributions, including:**

- Clients acquired.

- Qualified leads.

- Follow-ups completed.

- Reservations submitted.

- Sales completed.

- Total sales value.

- Client satisfaction.

This makes promotions and performance evaluations more objective.

E. Central company database

All company information should be connected to one persistent database architecture.

**For example, a sale should automatically update:**

- Property inventory.

- Client records.

- Employee sales history.

- Commission records.

- Company revenue.

- Finance reports.

- Sales Manager performance.

This is essential to prevent inconsistent information between departments.

One company. One headquarters. An entire corporate ecosystem.

Initial release vision

- 100-player server target.

- One Developer: Highview.

- Persistent employee identities.

- Full organizational hierarchy.

- Functional office headquarters.

- Interactive employee tablets.

- Central property inventory.

- NPC and online clients.

- On-site and online selling.

- Reservations and property transactions.

- Ledger banking and commissions.

- Player-managed departments.

  Development focus

  Build the company before building the city.

