import { useState, useCallback, useMemo } from "react";

const LECTURES = [
  {
    id: 1,
    title: "Introduction to the Profession of Architecture",
    icon: "🏛️",
    sections: [
      {
        title: "What is Architecture?",
        simple: "Architecture is the art and science of designing buildings and spaces. It covers everything from small homes to entire communities. An architect combines creativity with technical knowledge to turn ideas into physical structures.",
        academic: "Architecture is defined as both the process and product of planning, designing, and constructing buildings and other physical structures. It encompasses the profession of designing buildings, open spaces, communities, and other physical environments. The term is used broadly to describe: (1) buildings and physical structures, (2) the style of design and construction, (3) knowledge of art, science, and humanities, and (4) the full spectrum of an architect's design activities from micro to macro scale.",
        keyTerms: [
          { term: "Architecture", def: "Both the process and product of planning, designing, and constructing buildings and other physical structures." },
          { term: "Architect", def: "A person who plans, designs, and oversees the construction of buildings; registered, licensed, or otherwise authorised to use the title and practice architecture." }
        ],
        examPoints: [
          "Architecture is BOTH process AND product — exams often test this dual nature.",
          "An architect's role extends from technical knowledge to business management.",
          "The architect must possess: skill in designing, knowledge of aesthetics AND practical considerations, and adequate skill to originate, design, plan, and supervise construction."
        ],
        confusion: "Do not confuse 'architecture' (the discipline/product) with 'architectural practice' (the business of providing architectural services). Practice is one component of architecture."
      },
      {
        title: "What is a Profession?",
        simple: "A profession is a special type of career that requires expert knowledge, formal training, examinations, a code of ethics, and service to the public. It's more than just a job — it comes with responsibilities to society.",
        academic: "Every profession involves six key elements: (1) the use of skills based on theoretical knowledge, (2) education and training in these skills, (3) competence of professionals ensured by examinations, (4) a code of conduct to ensure professional integrity, (5) performance of a service for the public good, and (6) a professional association that organizes members. All professionals must provide disinterested services to clients, promote welfare of the community, and have social responsibility.",
        keyTerms: [
          { term: "Profession", def: "An occupation requiring specialised knowledge, formal training, examinations, a code of conduct, service for the public good, and an organising professional association." },
          { term: "Disinterested service", def: "Providing the best service to a client without personal bias or conflicting interests." },
          { term: "Code of Conduct", def: "A set of rules governing professional behaviour and integrity." }
        ],
        examPoints: [
          "SIX elements define a profession — memorise all six.",
          "THREE obligations of all professionals: disinterested service to clients, promote community welfare, social responsibility.",
          "The profession of architecture specifically calls for: artistic ability, business capacity, and men/women of integrity."
        ],
        confusion: "Do not confuse 'profession' with 'occupation.' An occupation is any form of employment, while a profession specifically requires formal qualifications, a code of ethics, and public service orientation."
      },
      {
        title: "Historic Role of the Architect",
        simple: "The word 'architect' comes from Greek meaning 'chief builder.' Although building design goes back to ancient times, architecture only became a separate, recognised profession during the Italian Renaissance. Before that, architects were called 'master builders.'",
        academic: "The word architect derives from the Greek 'architekton' (arkhi- = chief + tekton = builder). Vitruvius Pollio (c. 80–70 BC to after c. 15 BC) is often considered the first recognisable 'architect,' though he did not conform to the modern perception. During the Middle Ages, the term 'architect' was rarely used — practitioners were called 'master' (English), 'magister' (Latin), or 'maestro' (Italian). The actual term 'Architect' dates to the mid-16th century, from French 'architecte' and Italian 'architetto.' Architecture as a distinct discipline first emerged in Italy during the Renaissance. Architecture was closely associated with engineering historically; engineering was taught separately from the 18th century. Civil engineering emerged as distinct from architecture in the second half of the 18th century.",
        keyTerms: [
          { term: "Vitruvius Pollio", def: "Roman writer, engineer, and builder (c. 80–70 BC to after c. 15 BC), often considered the first recognisable 'architect.'" },
          { term: "Master Builder", def: "The title used for architects during the Middle Ages, combining design and construction oversight." },
          { term: "Civil Engineering", def: "Discipline that separated from architecture in the late 18th century, focusing on non-military structures like roads and bridges." }
        ],
        examPoints: [
          "Greek origin: architekton = arkhi (chief) + tekton (builder)",
          "Vitruvius — first recognisable architect, but NOT strictly an architect by modern standards",
          "Renaissance Italy — architecture first emerged as a distinct discipline",
          "Mid-16th century — the actual term 'Architect' appeared",
          "18th century — engineering taught as a separate course; civil engineering distinguished from architecture",
          "Modern shift: from architect responsible for everything → shared responsibility"
        ],
        confusion: "Do not assume architecture was always a separate profession. Until the Renaissance, there was no standard training and no clearly defined profession of architecture."
      },
      {
        title: "Architectural Education & Practice in the UK",
        simple: "In the UK, becoming an architect requires a long combination of university study and practical work experience — a total of about 7 years. Two main bodies control this: the ARB (the legal regulator) and the RIBA (the professional body).",
        academic: "UK architectural education combines academic education and professional training, controlled by state authorities and professional bodies. The Architects Registration Board (ARB) is the statutory regulatory body and keeper of the formal Architect's Register. The Royal Institute of British Architects (RIBA) is the principal professional body. The ARB 'prescribes' qualifications; the RIBA 'validates' programmes. Only persons on the Register may legally use the title 'Architect' in business or practice in the UK.",
        keyTerms: [
          { term: "ARB (Architects Registration Board)", def: "The statutory regulatory body in the UK; keeper of the formal Architect's Register; prescribes qualifications." },
          { term: "RIBA (Royal Institute of British Architects)", def: "The principal professional body in the UK; validates educational programmes and provides accreditation." },
          { term: "RIBA Part 1", def: "3-year degree in architecture at a school of architecture." },
          { term: "RIBA Part 2", def: "2-year degree or diploma in architecture (post-Part 1)." },
          { term: "RIBA Part 3", def: "Final examination in professional practice after minimum 1 year practical experience post-Part 2." },
          { term: "Prescribe vs. Validate", def: "ARB prescribes (formally recognises) qualifications; RIBA validates (accredits) educational programmes." }
        ],
        examPoints: [
          "UK Education Path: A-levels → Part 1 (3 yrs) → Practical Experience (1 yr min) → Part 2 (2 yrs) → Practical Experience (1 yr min) → Part 3 → Registration",
          "ARB = statutory regulator; RIBA = professional body — know the difference",
          "ARB PRESCRIBES; RIBA VALIDATES — key distinction",
          "Only registered persons may use the title 'Architect' in the UK"
        ],
        confusion: "Do not confuse ARB and RIBA. ARB is the LEGAL regulator (statutory body). RIBA is the PROFESSIONAL body. Both have codes of conduct but they are different documents."
      },
      {
        title: "RIBA Membership & UK Practice Routes",
        simple: "RIBA has different membership levels for students, graduates, and fully qualified architects. There are also three routes to register as an architect in the UK, depending on where you got your qualifications.",
        academic: "RIBA membership has two broad categories: Individual Membership (Chartered, Associate, Student, Affiliate, and Retired Chartered) and Practice Membership (for UK architectural practices). Three routes to registration exist: Route 1 — UK qualifications (Parts 1, 2, 3 plus practical experience); Route 2 — EU Automatic Recognition System (qualifications recognised across EU member states); Route 3 — qualifications from outside the UK/EU (must pass equivalent examinations to Parts 1 and 2, then obtain practical training and pass Part 3).",
        keyTerms: [
          { term: "Chartered Membership", def: "RIBA membership for fully qualified architects." },
          { term: "Associate Membership", def: "For individuals awarded RIBA Part 1 and Part 2 or equivalent." },
          { term: "Student Membership", def: "For persons studying RIBA Part 1 or Part 2." },
          { term: "Affiliate Membership", def: "For persons with interest in architecture but not eligible for other categories." },
          { term: "Practice Membership", def: "RIBA Chartered Practice Membership for UK architectural practices." }
        ],
        examPoints: [
          "5 types of individual RIBA membership: Chartered, Associate, Student, Affiliate, Retired Chartered",
          "Route 1 = UK qualifications; Route 2 = EU recognition; Route 3 = non-UK/non-EU qualifications",
          "Route 3 applicants must pass 'equivalent' examinations"
        ],
        confusion: null
      },
      {
        title: "Codes of Conduct (ARB & RIBA)",
        simple: "Both the ARB and RIBA have codes that architects must follow. These codes ensure architects behave ethically, maintain competence, and serve clients and the public properly.",
        academic: "The ARB code ('Standards of Professional Conduct and Practice') contains 12 standards applicable to registered architects: (1) Honesty and integrity, (2) Competence, (3) Honest promotion of services, (4) Competent business management, (5) Consider wider impact, (6) Faithful and careful work, (7) Trustworthiness with client's money, (8) Appropriate insurance, (9) Maintain reputation of architects, (10) Deal with disputes appropriately, (11) Co-operate with regulatory investigations, (12) Respect for others. The RIBA Code of Professional Conduct (since 1 January 2005) has 3 principles: (1) Integrity, (2) Competence, (3) Relationships.",
        keyTerms: [
          { term: "ARB Standards", def: "12 standards of professional conduct and practice for registered UK architects." },
          { term: "RIBA Code", def: "3 principles (Integrity, Competence, Relationships) governing RIBA members since January 2005." }
        ],
        examPoints: [
          "ARB = 12 Standards; RIBA = 3 Principles — know the numbers",
          "ARB Standard 1: Honesty and integrity; Standard 2: Competence",
          "ARB Standard 8: Appropriate insurance — architects MUST have adequate insurance",
          "ARB Standard 12: Respect for others — no discrimination",
          "RIBA Principle 1: Integrity; Principle 2: Competence; Principle 3: Relationships",
          "RIBA Principle 3 includes social diversity, fair dealing, and regard for community and environment"
        ],
        confusion: "Do not mix up the ARB 12 standards with the RIBA 3 principles. They are separate documents from separate bodies. An architect registered with both must comply with BOTH."
      }
    ],
    quiz: [
      { q: "What Greek word does 'architect' derive from, and what does it mean?", a: "From 'architekton' — arkhi (chief) + tekton (builder), meaning 'chief builder.'" },
      { q: "Name the six elements that define a profession.", a: "(1) Skills based on theoretical knowledge, (2) Education and training, (3) Competence ensured by examinations, (4) Code of conduct, (5) Service for public good, (6) Professional association." },
      { q: "What is the difference between ARB and RIBA?", a: "ARB is the statutory regulatory body (legal regulator, keeper of the register). RIBA is the principal professional body. ARB prescribes qualifications; RIBA validates programmes." },
      { q: "How many standards does the ARB code have, and how many principles does the RIBA code have?", a: "ARB: 12 standards. RIBA: 3 principles (Integrity, Competence, Relationships)." },
      { q: "Who was Vitruvius and why is he significant?", a: "Vitruvius Pollio (c. 80–70 BC) was a Roman writer, engineer, and builder, often considered the first recognisable 'architect,' though he did not conform to the modern perception." },
      { q: "When did architecture emerge as a distinct discipline?", a: "During the Italian Renaissance. The actual term 'Architect' dates to the mid-16th century." }
    ]
  },
  {
    id: 2,
    title: "The Building Team",
    icon: "👷",
    sections: [
      {
        title: "The Profession of Architecture — Services",
        simple: "Architects translate abstract ideas into real buildings through sketches, plans, models, and specifications. The design process is not straightforward — it's a creative, nonlinear mix of logic and intuition.",
        academic: "Architectural services include: translating client needs and aspirations, applying theories and technologies, conceptualising spaces and structures, producing costs and budgets, preparing working drawings and tender documents, preparing construction schedules, and getting buildings built on time. A proficient architect requires artistic skills, technological skills, and working knowledge of laws, regulations, customs, costs, business, circulation patterns, access, and special needs.",
        keyTerms: [
          { term: "Architectural Services", def: "The full range of professional activities from translating client needs through to completed building delivery." },
          { term: "NAAB", def: "National Architectural Accrediting Board — defines 5 major areas of architectural practice." },
          { term: "Architectural Technologist", def: "A professional trained in architectural technology, building technical design and construction, who works alongside architects." }
        ],
        examPoints: [
          "NAAB's 5 areas of practice: Laws & Regulations, Business & Practice Management, Project Finance & Building Economics, Architectural Project Delivery Process, Contracts",
          "Three skill areas of a proficient architect: Artistic, Technological, and Working knowledge of laws/costs/business",
          "Architectural technologists are NOT architects but work alongside them, often doing drawing and design work"
        ],
        confusion: "Do not confuse an architect with an architectural technologist. The technologist concentrates on the technology of building and construction, while the architect leads the overall design."
      },
      {
        title: "The Four Groups of the Building Team",
        simple: "Building a building requires four main groups working together: the Client (who pays), the Design Team (who designs), the Contracting Team (who builds), and the Statutory Authorities (who regulate).",
        academic: "The four main groups in a building project are: (1) The Client — commissions the design, contracts for works, pays fees and costs; (2) The Design Team — led by the architect, includes all design professionals; (3) The Contracting Team — led by the contractor, carries out construction; (4) The Statutory Authorities — ensure compliance with regulations, codes, and safety.",
        keyTerms: [
          { term: "Client (Employer)", def: "The person/organisation who commissions the design, contracts for works, and pays all fees and construction costs. Called 'Employer' under standard forms of building contract." },
          { term: "Design Team", def: "The group of professionals led by the architect who design the building." },
          { term: "Contracting Team", def: "The group led by the contractor who physically construct the building." },
          { term: "Statutory Authorities", def: "Government bodies (e.g. Municipality) that ensure compliance with regulations, zoning laws, building codes, and safety standards." }
        ],
        examPoints: [
          "The CLIENT is 'the most important team member' — they pay the fees and 'call the tune'",
          "The architect acts as the client's AGENT",
          "Relationships with the client are of 'prime importance'",
          "The architect's decisions result in the client spending money"
        ],
        confusion: null
      },
      {
        title: "The Design Team — Members & Roles",
        simple: "The design team is led by the architect and includes many specialists, each with a specific job. Think of it as an orchestra — the architect is the conductor, and each member plays a different instrument.",
        academic: "The Design Team consists of: (1) Architect — acts as client's agent from inception to completion; (2) Architectural Technologist — works in partnership with architect, especially in architectural technology; (3) Other Architectural Staff — technicians, assistants, draughtspersons; (4) Clerk of Works — employed by client, acts as architect's on-site representative (inspector, without power to issue instructions independently); (5) Quantity Surveyor — advises on costs, prepares bills of quantities, checks tenders, carries out valuations; (6) Structural Engineer — assists in design, construction, and supervision of structural elements; (7) Resident Engineer — structural engineer's on-site representative; (8) Building Services Engineer(s) — handles lighting, heating, drainage, etc.; (9) Landscape Architect — designs landscaping; (10) Interior Designer — handles internal decor; (11) Other Consultants — specialists like acoustic engineers.",
        keyTerms: [
          { term: "Clerk of Works", def: "Employed by the client to act as the architect's on-site representative/inspector; cannot issue instructions on own authority." },
          { term: "Quantity Surveyor (QS)", def: "Advises architect and client on all cost matters: prepares bills of quantities, checks tenders, carries out cost valuations during the project." },
          { term: "Structural Engineer", def: "Designs, constructs, and supervises the structural elements of a building." },
          { term: "Resident Engineer", def: "The structural engineer's on-site representative (inspector)." },
          { term: "Building Services Engineer", def: "Handles mechanical and electrical services: lighting, heating, drainage, etc." }
        ],
        examPoints: [
          "Architect = client's AGENT; role spans from inception to final completion and occupation",
          "Clerk of Works = client's employee but architect's representative on site — INSPECTOR without independent authority",
          "Quantity Surveyor = cost adviser — bills of quantities, tender checking, valuations",
          "Know the numbered hierarchy: Architect (01), Technologist (02), Other Staff (03), Clerk of Works (04), QS (05), Structural Engineer (06), Resident Engineer (07), Building Services Engineer (08), Landscape Architect (09), Interior Designer (10), Other Consultants (12)"
        ],
        confusion: "Do not confuse the Clerk of Works with the Site Manager. The Clerk of Works works for the CLIENT (inspects on the architect's behalf), while the Site Manager works for the CONTRACTOR."
      },
      {
        title: "The Contracting Team — Members & Roles",
        simple: "The contracting team does the actual building work. Led by the contractor, it includes managers, engineers, foremen, workers, and specialist subcontractors. Think of them as the army that turns the architect's plans into reality.",
        academic: "The Contracting Team hierarchy: Contractor/Builder (employed by client on architect's advice to construct the building); Contracts/Project Manager (employed by contractor, supervises site managers across multiple contracts); Site/Construction Manager (controls work on site); Site Engineer (responsible for setting out and accuracy); General Foreman (day-to-day site running, link between management and operatives); Trade Foremen (in charge of gangs/crews of specific trades); Site Operatives (workforce: tradespeople, apprentices, labourers); Other Staff (buyers, plant managers, storekeepers, timekeepers, wages clerks); Surveyor/QS (prepares interim valuations and final accounts); Estimator (prices tenders, involved in pre-contract cost aspects); Scheduler/Planner (scheduling and programme planning); Subcontractors (responsible for specific parts of construction); Suppliers (supply materials/components).",
        keyTerms: [
          { term: "Contractor/Builder", def: "Employed by the client (on architect's advice) to construct the building in accordance with the design team's documents." },
          { term: "Contracts Manager", def: "Employed by the contractor to run multiple contracts; the site manager's immediate supervisor." },
          { term: "Site (Construction) Manager", def: "Employed by the contractor to control work on site; also called Construction Manager or Site Agent." },
          { term: "General Foreman", def: "Responsible for day-to-day running of the site; link between site manager and operatives." },
          { term: "Trade Foremen", def: "In charge of gangs/crews of specific trades (bricklayers, carpenters, plumbers, etc.)." },
          { term: "Subcontractors", def: "Responsible for specific construction work under the contractor's control (e.g. structural steelwork)." },
          { term: "Suppliers", def: "Responsible for supplying materials or components used by the contractor (e.g. windows)." }
        ],
        examPoints: [
          "Contractor is employed BY THE CLIENT on the architect's advice",
          "Site Engineer → setting out and accuracy; General Foreman → day-to-day running",
          "Estimator = pre-contract pricing; Scheduler/Planner = programming",
          "Contractor's QS ≠ Design Team's QS — different employers, different roles"
        ],
        confusion: "Do not confuse the contractor's Quantity Surveyor with the design team's Quantity Surveyor. Both are QS professionals, but one works for the contractor (interim valuations, final accounts) and the other works for the client (cost advice, bills of quantities)."
      },
      {
        title: "Statutory Authorities",
        simple: "Statutory authorities are government bodies (like municipalities) that make sure buildings follow the law — zoning, safety, building codes, environmental rules, and accessibility standards.",
        academic: "Statutory authorities serve as the foundation for administrative discretion, granting agencies the power to interpret and implement laws. Their roles include: ensuring compliance with local regulations, zoning laws, building codes, and safety standards; providing approvals and permits; guiding on environmental and sustainability requirements; monitoring construction safety; collaborating with the design team; minimising legal risks; overseeing accessibility, health, and fire safety standards; and approving design changes and modifications.",
        keyTerms: [
          { term: "Statutory Authority", def: "A government body with legal power to enforce regulations, issue permits, and ensure compliance with building codes and laws." }
        ],
        examPoints: [
          "Statutory authorities provide approvals at VARIOUS stages of the project, not just at the start",
          "They ensure compliance with: regulations, zoning, building codes, safety, environment, accessibility, health, and fire safety",
          "They collaborate WITH the design team — they are not adversaries"
        ],
        confusion: null
      }
    ],
    quiz: [
      { q: "Name the four main groups in a building project.", a: "Client, Design Team, Contracting Team, and Statutory Authorities." },
      { q: "What is the role of the Clerk of Works and who employs them?", a: "Employed by the client but acts as the architect's on-site representative (inspector). Cannot issue instructions on their own authority." },
      { q: "What is the difference between the design team's QS and the contractor's QS?", a: "Design team QS: advises on costs, prepares bills of quantities, checks tenders (works for the client). Contractor's QS: prepares interim valuations, final accounts, and measures work for subcontractors (works for the contractor)." },
      { q: "Who is the 'most important team member' and why?", a: "The client — they pay the fees and construction costs, commission the design, and ultimately 'call the tune.'" },
      { q: "List the three skill areas a proficient architect needs.", a: "Artistic skills, technological skills, and working knowledge of laws, regulations, customs, costs, business, circulation patterns, access, and special needs." }
    ]
  },
  {
    id: 3,
    title: "Types of Architectural Practices",
    icon: "🏢",
    sections: [
      {
        title: "Introduction — Skills for Success",
        simple: "Running a successful architectural practice requires more than just design talent. You also need organisational skills, management skills, and business expertise. Practices can operate under traditional or non-traditional systems.",
        academic: "A successful architectural practice requires four categories of skills: (1) Design and Technical Skills, (2) Organisation Skills, (3) Managing Skills, and (4) Business Expertise. Practices can operate under two broad systems: the Traditional System (architect is independent of the contracting team) and Non-Traditional Systems (architect is dependent on the rest of the team).",
        keyTerms: [
          { term: "Traditional System", def: "A procurement system where the architect is independent of the contracting team." },
          { term: "Non-Traditional System", def: "A procurement system where the architect is dependent on or integrated with the rest of the team." }
        ],
        examPoints: [
          "4 skills for success: Design/Technical, Organisation, Managing, Business",
          "Traditional = architect INDEPENDENT; Non-traditional = architect DEPENDENT"
        ],
        confusion: null
      },
      {
        title: "Traditional System Practices",
        simple: "Under the traditional system, there are several ways to set up an architectural business, from a single person running everything (sole principal) to large companies with many shareholders.",
        academic: "Traditional system practice types include: Sole Principal, Partnerships (General, Limited, and Limited Liability), Incorporation (Unlimited Liability Companies, Private Limited Liability Companies, and Public Limited Companies), Integrated Practice, Group Practice, and Consortia.",
        keyTerms: [],
        examPoints: [
          "6 types under traditional system: Sole Principal, Partnerships (3 sub-types), Incorporation (3 sub-types), Integrated Practice, Group Practice, Consortia"
        ],
        confusion: null
      },
      {
        title: "Sole Principal",
        simple: "A sole principal is one person who owns and runs the practice alone. They keep all the profits but also carry all the risk. They can still employ staff — 'sole principal' means sole OWNER, not sole worker.",
        academic: "In a sole principal practice, the company and individual owner are one and the same — no legal distinction between individual and business. The owner's assets are the business's assets. A sole principal may trade under their own name or a business name. They are not required by law to produce or file annual accounts. The firm ceases to exist if the owner stops operating unless the business is sold.",
        keyTerms: [
          { term: "Sole Principal", def: "A practice where one individual is solely responsible for the business, with no legal distinction between the person and the business entity." }
        ],
        examPoints: [
          "Advantages: Simplest to start, great freedom, all profits to principal, minimal fees/formalities",
          "Disadvantages: Personal liability for ALL debts and lawsuits, illness/death = business failure, difficult to obtain loans, requires multiple management skills, may be hard to sell",
          "'Sole principal' ≠ 'working alone' — they can employ staff"
        ],
        confusion: "Do not confuse 'sole principal' with 'working alone.' A sole principal is solely RESPONSIBLE for the business but may employ many staff."
      },
      {
        title: "Partnerships",
        simple: "A partnership is when two or more people share a business. There are three types: General (all partners share everything equally), Limited (some partners only invest money), and Limited Liability (everyone's personal assets are protected).",
        academic: "General Partnership: relationship between 2+ persons carrying on business in common with a view to profit. Partners are co-owners and can bind the company. Advisable to use a formal agreement drawn by a lawyer. Limited Partnership: formed according to statutory requirements; has general partner(s) with management responsibility and limited partner(s) who only invest. In architecture, at least one general partner must be an architect. Limited partner's liability is restricted to their investment. Limited Liability Partnership (LLP): combines features of company and partnership. Name must end with 'LLP'. Has separate legal personality. Members' liability limited to their stakes. Must file returns with the registrar.",
        keyTerms: [
          { term: "General Partnership", def: "A relationship between 2+ persons carrying on business in common with a view to profit; all partners share unlimited liability." },
          { term: "Limited Partnership", def: "A partnership with general partner(s) who manage and assume personal liability, and limited partner(s) who only invest and whose liability is limited to their investment." },
          { term: "Limited Liability Partnership (LLP)", def: "A partnership with separate legal personality where members' liability is limited to their stakes; must end name with 'LLP' and file returns." }
        ],
        examPoints: [
          "General: Unlimited liability, partners bind each other, dissolved by any change in relationship",
          "Limited: At least one general partner (must be architect in architecture); limited partners cannot make management decisions",
          "LLP: Separate legal personality, must file returns, name ends 'LLP', members can choose internal organisation"
        ],
        confusion: "Do not confuse Limited Partnership with Limited Liability Partnership (LLP). In a Limited Partnership, the general partners still have unlimited personal liability. In an LLP, ALL members' liability is limited."
      },
      {
        title: "Incorporation (Companies)",
        simple: "Instead of a partnership, architects can form a company. This creates a separate legal entity that can protect personal assets. Companies range from unlimited (less protection) to private limited (good protection) to public (PLC, can sell shares publicly).",
        academic: "Unlimited Liability Company: not common for architecture; shareholders/directors liable for debts if company assets insufficient; max 50 members; director free from liability 12 months after leaving. Private Limited Liability Company: separate legal personality; shareholders' personal assets protected from company debts; important for negligence claims; directors are employees paid salary; shares may be held by non-employees. Public Limited Company (PLC): must put 'PLC' after name; usually formed after period as private company; can raise capital through stock exchange; CRITICAL: control must remain in architects' hands (e.g. keeping 51% of shares).",
        keyTerms: [
          { term: "Unlimited Liability Company", def: "A company where members may be personally liable for company debts; max 50 members; not common for architectural practice." },
          { term: "Private Limited Liability Company", def: "A company with separate legal personality; shareholders' personal assets protected; most relevant for architecture to protect against negligence claims." },
          { term: "Public Limited Company (PLC)", def: "A company that can sell shares to the public via stock exchange; must display 'PLC' after name; control of architect-directors is a key concern." }
        ],
        examPoints: [
          "Private Ltd: Separate legal personality — key for protection against negligence claims",
          "PLC: Can raise capital on stock exchange, BUT architects must maintain control (51%+ shares)",
          "Unlimited company: Max 50 members; director liability ends 12 months after departure",
          "In a limited company, shareholders who are directors are EMPLOYEES of the company"
        ],
        confusion: "Do not confuse a private limited company with a limited partnership. A limited company has a separate legal personality (it is its own entity); a limited partnership does not."
      },
      {
        title: "Integrated Practice, Group Practice & Consortia",
        simple: "These are ways multiple firms or professionals cooperate. Integrated practice puts different disciplines under one roof. Group practice has separate firms sharing resources. Consortia group different disciplines together for specific projects.",
        academic: "Integrated Practice: partners from different professional disciplines (architects, engineers, QS, planners) within a single firm; operates as partnership or company; useful for large, complex projects — client deals with one firm. Group Practice: separate architectural firms combine to offer improved service while retaining independence; do NOT share profits or responsibilities to clients. Consortia: firms from different professional disciplines group together, each retaining separate identity; e.g. architects + structural engineers + building services engineers cooperating on a hospital.",
        keyTerms: [
          { term: "Integrated Practice", def: "A single firm with partners from multiple professional disciplines (architecture, engineering, QS, etc.)." },
          { term: "Group Practice", def: "Separate architectural firms that combine to offer improved service while retaining independence; do not share profits." },
          { term: "Consortia", def: "Firms from different professional disciplines grouping together while each retains its separate identity." }
        ],
        examPoints: [
          "Integrated = one firm, multiple disciplines, shared profits",
          "Group = multiple architecture firms, independence retained, NO shared profits",
          "Consortia = multiple disciplines, separate identities, cooperate on specific projects",
          "Group vs Consortia: Group = SAME discipline firms; Consortia = DIFFERENT discipline firms"
        ],
        confusion: "Do not confuse Group Practice with Consortia. Group Practice = multiple firms of the SAME type (architectural). Consortia = firms from DIFFERENT disciplines."
      },
      {
        title: "Non-Traditional Systems",
        simple: "Non-traditional systems change how the architect relates to the rest of the team. Instead of being independent, the architect might work for the contractor, or a manager might oversee everything.",
        academic: "Non-traditional systems include: (1) Design-and-Build — contractor receives brief directly from client and undertakes both design and construction; (2) Design-and-Develop — client employs independent architect for sketch design, then contractor develops detailed scheme; (3) Management Contracting — client employs contractor at initial stage to manage construction for a fee, with subcontractors competitively tendered; (4) Construction Management — client appoints contractor to manage but enters into contracts with subcontractors directly; (5) Project Management — project manager directs the project, selecting and coordinating both design and contracting teams.",
        keyTerms: [
          { term: "Design-and-Build", def: "Contractor undertakes both design and construction; receives brief directly from client." },
          { term: "Design-and-Develop", def: "Client's independent architect prepares sketch design; contractor then develops detailed scheme and price." },
          { term: "Management Contracting", def: "Client employs a management contractor to manage construction for a fee; subcontractors obtained through competitive tendering." },
          { term: "Construction Management", def: "Similar to management contracting, but the CLIENT enters into contracts directly with each subcontractor." },
          { term: "Project Management", def: "A project manager directs the entire project for the client, selecting and coordinating both design and contracting teams." }
        ],
        examPoints: [
          "Design-and-Build Advantages: single point of responsibility, improved communication, faster programme",
          "Design-and-Build Disadvantages: design quality may suffer, no independent adviser for client, hard to compare competitive schemes",
          "Design-and-Develop: ensures client gets what they want (appearance) + contractor ensures economic solution",
          "Management Contracting: management contractor manages site but does NOT do permanent construction work",
          "KEY DIFFERENCE: In Construction Management, CLIENT contracts directly with subcontractors; in Management Contracting, the MANAGEMENT CONTRACTOR does"
        ],
        confusion: "Do not confuse Management Contracting with Construction Management. The critical difference is WHO contracts with subcontractors: Management Contracting = management contractor; Construction Management = the CLIENT directly."
      }
    ],
    quiz: [
      { q: "Name the 6 traditional system practice types.", a: "Sole Principal, General Partnership, Limited Partnership, LLP, Incorporation (3 types: Unlimited, Private Ltd, PLC), Integrated Practice, Group Practice, Consortia." },
      { q: "What is the key difference between a General Partnership and an LLP?", a: "In a General Partnership, all partners have unlimited personal liability. In an LLP, members' liability is limited to their stakes, and the LLP has separate legal personality." },
      { q: "What distinguishes Management Contracting from Construction Management?", a: "In Management Contracting, the management contractor enters contracts with subcontractors. In Construction Management, the CLIENT enters contracts directly with each subcontractor." },
      { q: "Why might architects prefer to practice as a Private Limited Company?", a: "To protect personal assets from negligence claims — the company has separate legal personality, so if the company is sued, the architects' personal assets cannot be claimed." },
      { q: "What is the key concern with a PLC for architects?", a: "Control must remain in architects' hands — a PLC can be controlled by non-architects, so agreements to restrict shares (e.g. keeping 51%) are important." }
    ]
  },
  {
    id: 4,
    title: "Organisational Frameworks & Project Organisation",
    icon: "📊",
    sections: [
      {
        title: "Organisational Frameworks — Introduction",
        simple: "Every architectural firm needs a clear structure so everyone knows their role, who they report to, and what they're responsible for. This structure is called the organisational framework.",
        academic: "The practice of architecture is an art but also a business. For success, it needs efficient organisation. Organisation occurs at two levels: (1) overall organisation of the firm, and (2) how individual projects are handled. The organisational framework is an arrangement where the firm's total workload is divided among staff. If properly devised, everyone knows precisely what they have to do, whom they control, and to whom they are answerable.",
        keyTerms: [
          { term: "Organisational Framework", def: "An arrangement dividing the firm's total workload among staff, defining responsibilities, authority, and reporting lines." }
        ],
        examPoints: [
          "Two levels of organisation: (1) overall firm organisation, (2) individual project organisation",
          "A proper framework = everyone knows: what to do, who they control, who they answer to"
        ],
        confusion: null
      },
      {
        title: "Three Patterns of Organisational Framework",
        simple: "There are three basic shapes for organising a firm: Shallow (everyone reports to one boss), Deep (layers of management), and Mixed (a combination). As a firm grows, it moves from shallow to deep or mixed.",
        academic: "Three major patterns: (1) Shallow Framework — the simplest; everyone answerable to a single person (the principal). Suitable for very small firms. (2) Deep Framework — as staff increase, project leaders are introduced who receive instructions from the principal and direct groups of assistants. Additional tiers can be added. (3) Mixed Framework — a combination of shallow and deep; the principal controls some individuals directly while also overseeing project leaders who in turn control further groups.",
        keyTerms: [
          { term: "Shallow Framework", def: "Simplest organisational structure; everyone reports directly to one person (the principal)." },
          { term: "Deep Framework", def: "Multi-layered structure with project leaders between the principal and assistants." },
          { term: "Mixed Framework", def: "Combination of shallow and deep — principal controls some staff directly and also oversees project leaders." }
        ],
        examPoints: [
          "Shallow = 1 tier (principal → all staff directly). Suitable for small firms.",
          "Deep = multiple tiers (principal → project leaders → assistants). For larger firms.",
          "Mixed = combination (principal controls some directly + some through project leaders). Most common in growing firms.",
          "Know the progression: Small firm = shallow → Medium = mixed → Large = deep/mixed with more tiers"
        ],
        confusion: "Do not assume one framework type is 'best.' The right choice depends on firm size. A shallow framework becomes impracticable as staff numbers increase."
      },
      {
        title: "Examples of Framework by Firm Size",
        simple: "A one-person practice uses the simplest structure. As firms grow, they add layers — project leaders, associates, and more tiers of management.",
        academic: "Examples include: (1) Sole principal working alone — simplest. (2) One principal + one assistant. (3) Small firm with sole principal — shallow framework (principal directly controls all staff). (4) Medium firm with sole principal — mixed framework (principal employs project leaders PL1–PL3). (5) Large firm with sole principal — mixed framework with additional tiers (senior associates, project leaders, assistants). (6) Partnership — mixed framework with multiple partners and associates (e.g. 3 partners with 5 associates, Assoc.1–Assoc.5).",
        keyTerms: [
          { term: "Project Leader", def: "A senior assistant who receives instructions from the principal and directs a group of assistants on specific projects." },
          { term: "Associate", def: "A senior staff member in a partnership who works under the partners, often managing projects." }
        ],
        examPoints: [
          "Be able to identify framework type from a diagram: count tiers and reporting lines",
          "Partnership example: 3 partners → 5 associates → groups of staff = mixed framework"
        ],
        confusion: null
      },
      {
        title: "Organisation of Individual Projects (RIBA Plan of Work)",
        simple: "Besides organising the whole firm, each individual project must be well-managed. The RIBA Plan of Work describes the major stages of a building project from start to finish.",
        academic: "The principal must organise each project to: (1) enable the contractor to provide the client with what they want, and (2) ensure the architectural firm makes a profit. The RIBA Plan of Work describes project phases from appraising client requirements through to post-construction. The six stages of project organisation are: (1) Deciding what has to be done, (2) Programming the work, (3) Organising the work, (4) Coordinating and controlling the work, (5) Organising record procedures, (6) Day-to-day organisation and work philosophy.",
        keyTerms: [
          { term: "RIBA Plan of Work", def: "A framework by the Royal Institute of British Architects describing the project phases from client appraisal through to post-construction." },
          { term: "Programming", def: "Setting a time against each task and deciding resource allocation." },
          { term: "Coordinating and Controlling", def: "Ensuring everyone works towards a common aim with no task left undone or duplicated, maintaining chain of command and checking progress." }
        ],
        examPoints: [
          "6 stages of project organisation — memorise all six in order",
          "Stage 1 (Deciding): Includes receiving brief, organising design team, sketch plans, costing, full drawings, specifications, statutory approvals, bills of quantities, selecting contractor, contract documents, contract administration",
          "Stage 4 (Coordinating/Controlling): Common aim, no duplication, chain of command, progress checking, budget monitoring",
          "TWO goals of individual project organisation: (1) client satisfaction, (2) firm profitability"
        ],
        confusion: null
      },
      {
        title: "Day-to-Day Organisation Principles",
        simple: "Running a practice day-to-day means balancing quality, time, and cost while keeping staff motivated and maintaining a positive working environment.",
        academic: "All activities measured against three criteria: quality, time, and cost. Key principles: profitability and survival must be remembered; client requirements must be satisfied; organisation should meet people's needs with secure employment; resources utilised efficiently; leaders must define objectives, set standards, and not be over-dominant; office atmosphere should be friendly, enthusiastic, cooperative; jobs should provide challenge; individuals should receive encouragement and motivation; extra effort and above-average performance should be recognised; delegation of authority should always be provided.",
        keyTerms: [
          { term: "Three Criteria", def: "Quality, Time, and Cost — the three measures against which all project activities should be evaluated." }
        ],
        examPoints: [
          "THREE criteria: Quality, Time, Cost — fundamental to all project activities",
          "Professional objective = produce good architecture that is functional and represents value for money",
          "Leaders must NOT be over-dominant",
          "Delegation of authority should ALWAYS be provided"
        ],
        confusion: null
      },
      {
        title: "Communications",
        simple: "Good communication is essential in architecture. Whether by phone, fax, computer, letter, or report, information must be clear, complete, and properly recorded.",
        academic: "Communications involve successful imparting or exchange of information via speaking, writing, computers, photography, and models. Key communication types: (1) Telephone — answer promptly and pleasantly, keep calls brief, record all conversations especially decisions; (2) Fax — useful for transmitting sketches urgently, but not always accepted as legal documents (originals must be posted); (3) Computer — enables simultaneous viewing and discussion of drawings across offices; (4) Written (letters/memos) — be brief, clear, orderly; write as you would speak; avoid jargon with non-technical recipients; (5) Reports — present information clearly and concisely, tailored to the recipient; structure: headings, introduction, body with sections, conclusions/recommendations.",
        keyTerms: [
          { term: "Disbursements", def: "Sums paid by the architect on behalf of the client, such as fees to local authorities for planning/building regulation approvals." },
          { term: "Report Structure", def: "Headings (to, from, title, date) → Introduction (purpose) → Body (sections with subheadings, facts then opinions) → Conclusions/Recommendations." }
        ],
        examPoints: [
          "Fax transmissions are NOT always accepted as legal documents — send originals by post",
          "Telephone: keep notes of ALL conversations, especially when decisions are made",
          "Written communication: 'Write as you would speak, if you had time to think before you spoke'",
          "Report structure: Headings → Introduction → Body → Conclusions — know this sequence",
          "Avoid technical terms when writing to non-technical people (e.g. clients)"
        ],
        confusion: null
      }
    ],
    quiz: [
      { q: "Name the three patterns of organisational framework.", a: "Shallow Framework, Deep Framework, and Mixed Framework." },
      { q: "What are the six stages of project organisation?", a: "(1) Deciding what has to be done, (2) Programming the work, (3) Organising the work, (4) Coordinating and controlling the work, (5) Organising record procedures, (6) Day-to-day organisation and work philosophy." },
      { q: "What three criteria should all project activities be measured against?", a: "Quality, Time, and Cost." },
      { q: "What is the correct structure for a professional report?", a: "Headings (to, from, title, date) → Introduction (purpose) → Body (sections with facts then opinions) → Conclusions and recommendations." },
      { q: "Why are fax transmissions problematic for legal purposes?", a: "They are not always accepted as legal documents, so original documents must be sent by post." }
    ]
  },
  {
    id: 5,
    title: "Financial Aspects of Architectural Practice",
    icon: "💰",
    sections: [
      {
        title: "Architectural Fees — Overview",
        simple: "Architects charge for their services in several ways: as a percentage of the building cost, a fixed lump sum, an hourly rate, or other arrangements. Each method has its own advantages and risks.",
        academic: "Four main methods of determining architectural fees: (1) Percentage of Construction Cost, (2) Lump-Sum (Fixed Fee) Charges, (3) Hourly Rate, and (4) Other Fees. Additionally, the client may be charged for Disbursements (sums paid on their behalf) and Expenses (travel, printing, etc. — only if agreed beforehand).",
        keyTerms: [
          { term: "Architectural Fees", def: "The charges an architect levies for professional services, calculated by percentage, fixed fee, hourly rate, or other methods." },
          { term: "Disbursements", def: "Sums paid by the architect ON BEHALF of the client (e.g. statutory fees for planning approvals)." },
          { term: "Expenses", def: "Day-to-day costs (hotel, travel, printing, postage, telephone) charged to the client only if previously agreed." }
        ],
        examPoints: [
          "4 fee methods: Percentage, Lump-Sum, Hourly Rate, Other",
          "Disbursements vs Expenses: Disbursements = paid on behalf of client; Expenses = day-to-day costs, only chargeable IF agreed beforehand",
          "QS and consultant fees are charged ADDITIONALLY to the architect's fees"
        ],
        confusion: "Do not confuse Disbursements with Expenses. Disbursements are specific sums the architect pays for the client (e.g. statutory fees). Expenses are general costs (travel, etc.) and are ONLY chargeable if agreed in advance."
      },
      {
        title: "Percentage of Construction Costs",
        simple: "The traditional method — the architect charges a percentage of the total building cost. For example, if a villa costs 150,000 BD to build and the fee is 2.5%, the architect earns 3,750 BD.",
        academic: "Traditionally, fees are charged as a percentage of total construction cost. The fee system accounts for building complexity (classified on a scale, e.g. 1 = simplest) and building typology (agricultural, commercial, community, industrial, medical, recreational, educational, residential). UK examples: new works range from 5% to 11.25%; works to existing buildings range from 7.75% to 16.5%. Fees are paid at intervals based on RIBA Plan of Work stages: Inception/Feasibility (time-charged), Outline Proposals (10–15%), Scheme Design (15–20%), Detail Design (20%), Production Information (20%), Tendering/Planning/Site (25–35%).",
        keyTerms: [
          { term: "Percentage Fee", def: "Fee calculated as a fixed percentage of total construction cost; varies by building complexity and type." },
          { term: "Building Classification", def: "Scale rating building complexity (1 = simplest) used to determine percentage fee level." }
        ],
        examPoints: [
          "Fee varies by COMPLEXITY and TYPOLOGY of building",
          "Works to EXISTING buildings cost MORE (7.75–16.5%) than NEW works (5–11.25%)",
          "Payment stages and approximate percentages — know these: Inception (time-charged), Outline Proposals (10–15%), Scheme Design (15–20%), Detail Design (20%), Production Information (20%), Tendering/Site (25–35%)",
          "Example: 2.5% × 150,000 BD = 3,750 BD"
        ],
        confusion: "Do not assume the same percentage applies to all building types. More complex buildings command higher percentage fees."
      },
      {
        title: "Lump-Sum (Fixed Fee) Charges",
        simple: "The client asks for a single fixed price upfront for all the architect's services. The architect must estimate carefully because the fee is usually fixed whether the estimate was right or wrong.",
        academic: "Used when the client wants to know the total fee at the outset. The estimated fee is usually charged regardless of whether it turns out to be correct. Generally more difficult to calculate than the percentage method. To estimate properly, the architect must: (1) know salary and overhead costs of the company, (2) have thorough understanding of services to be performed, (3) have a feeling for the decision-making ability of the client, (4) have job-time histories for similar projects to aid estimating.",
        keyTerms: [
          { term: "Lump-Sum Fee", def: "A fixed total fee agreed at the outset for all professional services; usually charged regardless of whether the estimate was accurate." }
        ],
        examPoints: [
          "4 requirements for accurate lump-sum estimation: know costs, understand services, gauge client's decision-making, have job-time histories",
          "Fee is usually charged WHETHER the estimate is correct or not — risk is on the architect",
          "More difficult to calculate than percentage method"
        ],
        confusion: null
      },
      {
        title: "Hourly Rate",
        simple: "The architect charges for each hour worked. The rate includes three components: salary + overheads + profit, typically resulting in a rate that is three times the employee's actual hourly salary.",
        academic: "Charges the client based on an hourly rate for all technical staff. The hourly rate comprises: (1) Staff Member's Salary (with allowance for salary increases on long projects), (2) Overheads (workspace, facilities, equipment, services — roughly equal to salary costs), and (3) Profit margin (often set at the same level as salary). Thus the hourly rate = approximately 3× the hourly salary. Clients may object to 'the meter always running,' so a 'not-to-exceed' limit is often set. A clause should be included for additional charges if delays or extra work are due to the client.",
        keyTerms: [
          { term: "Hourly Rate", def: "Fee calculated per hour for each technical staff member, comprising salary + overheads + profit ≈ 3× hourly salary." },
          { term: "Overheads", def: "The cost of providing each employee with workspace and facilities (lighting, heating, equipment, services); roughly equal to salary costs." },
          { term: "Not-to-Exceed Limit", def: "A maximum fee cap set in the contract to reassure clients using the hourly rate method." }
        ],
        examPoints: [
          "FORMULA: Hourly rate = Salary + Overheads + Profit ≈ 3× hourly salary",
          "Example: Staff salary 4 BD/hr → charge 12 BD/hr; 10 staff = total 120 BD/hr × hours worked",
          "Overheads ≈ salary; Profit ≈ salary → hence 3× multiplier",
          "'Not-to-exceed' limit addresses client concerns about open-ended billing",
          "Include a clause for additional charges if delays are caused by the CLIENT"
        ],
        confusion: "Do not forget: the 3× multiplier includes overheads AND profit, not just profit. Overheads ≈ salary, Profit ≈ salary, so Salary + Salary + Salary = 3× salary."
      },
      {
        title: "Termination of Services",
        simple: "The client can end the architect's appointment at any time, for any reason (financial difficulties, loss of confidence, etc.), but must give reasonable notice and pay for all work done up to that point.",
        academic: "The client has the right to abort the appointment at any stage, providing reasonable notice. Reasons may include financial difficulties or loss of confidence in the professional advisor. The architect has the right to be paid for all work completed up to the time of termination.",
        keyTerms: [
          { term: "Termination", def: "The ending of the architect's appointment by the client, requiring reasonable notice and payment for all work completed." }
        ],
        examPoints: [
          "Client CAN terminate at any time for any reason",
          "Two conditions: (1) reasonable notice, (2) architect paid for all work done to date",
          "Common reasons: financial difficulties, loss of confidence"
        ],
        confusion: null
      },
      {
        title: "Accounting: Accrual vs Cash & Financial Statements",
        simple: "Firms track money in two ways: Accrual accounting records income/expenses when earned/incurred (even if not yet paid), while Cash accounting only records when money actually changes hands. Accrual is recommended because it gives a clearer picture.",
        academic: "Accrual Accounting: recognises revenue and expenses when earned/incurred, regardless of cash collection/payment. Cash Accounting: recognises revenue and expenses only when cash is actually received/paid. Accrual is recommended because it provides a more comprehensive picture and prevents debt accumulation going unnoticed. Key financial statements: Balance Sheet (Assets = Liabilities + Owner's Equity), Income Statement (Net Revenue → Cost of Sales → Gross Margin → Operating Expenses → Profit/Loss Before Taxes). Cash Management involves forecasting — ensuring inflow equals or exceeds outflow for a given period.",
        keyTerms: [
          { term: "Accrual Accounting", def: "Revenue and expenses recognised when earned/incurred, regardless of whether cash has been received or paid." },
          { term: "Cash Accounting", def: "Revenue and expenses recognised only when cash is actually received or paid." },
          { term: "Balance Sheet", def: "Statement of financial position showing assets, liabilities, and owner's equity at a specific moment. Formula: Total Assets = Liabilities + Owner's Equity." },
          { term: "Income Statement (P&L)", def: "Reports all revenues and expenses for a stated period. Components: Net Revenue, Cost of Sales, Gross Margin, Operating Expenses, Profit/Loss Before Taxes." },
          { term: "Assets", def: "Any tangible or intangible resource the firm owns or controls, measurable in monetary terms." },
          { term: "Liabilities", def: "Moneys the firm owes to creditors." },
          { term: "Owner's Equity", def: "Moneys invested in the firm by owners or stockholders." },
          { term: "Revenue", def: "Inflows from the sale of goods or rendering of services during an accounting period." },
          { term: "Expenses", def: "Outflows of resources as a consequence of efforts to earn revenues." },
          { term: "Cash Management", def: "Cash forecasting — estimating monthly/quarterly revenue and expenses to ensure adequate cash flow." },
          { term: "Transactions", def: "Events that affect the financial aspects of a firm, either revenue-generating or expense-generating." }
        ],
        examPoints: [
          "Accrual = recommended; gives comprehensive picture; prevents hidden debt",
          "Cash Accounting risk: unpaid invoices can accumulate without being obvious",
          "Balance Sheet formula: Assets = Liabilities + Owner's Equity (or: Assets – Liabilities = Owner's Equity)",
          "Income Statement components IN ORDER: Net Revenue → Cost of Sales → Gross Margin → Operating Expenses → Profit/Loss Before Taxes",
          "Net Income = Revenues – Expenses; Loss occurs when Expenses > Revenues",
          "Cash Management = cash forecasting; inflow must ≥ outflow"
        ],
        confusion: "Do not confuse the Balance Sheet with the Income Statement. The Balance Sheet shows position at a SINGLE MOMENT. The Income Statement shows performance over a PERIOD OF TIME."
      }
    ],
    quiz: [
      { q: "Name the four main methods of charging architectural fees.", a: "Percentage of Construction Cost, Lump-Sum (Fixed Fee), Hourly Rate, and Other Fees." },
      { q: "How is the hourly rate calculated?", a: "Hourly rate = Salary + Overheads + Profit ≈ 3× the staff member's hourly salary (overheads ≈ salary, profit ≈ salary)." },
      { q: "What is the difference between disbursements and expenses?", a: "Disbursements: sums paid by the architect on behalf of the client (e.g. statutory fees). Expenses: day-to-day costs (travel, printing) only chargeable if agreed beforehand." },
      { q: "What is the Balance Sheet equation?", a: "Total Assets = Liabilities + Owner's Equity." },
      { q: "Why is Accrual Accounting recommended over Cash Accounting?", a: "Accrual provides a more comprehensive picture of profit and loss. Cash accounting risks unpaid invoices accumulating without being obvious, which could put the firm in a serious situation." },
      { q: "What rights does a client have regarding termination?", a: "The client can terminate at any time for any reason, providing reasonable notice. The architect has the right to be paid for all work completed up to termination." }
    ]
  }
];

const MCQs = [
  { q: "Which body is the statutory regulatory authority for architects in the UK?", opts: ["RIBA", "ARB", "NAAB", "RIAI"], ans: 1, explain: "The ARB (Architects Registration Board) is the statutory regulatory body. RIBA is the professional body." },
  { q: "How many standards does the ARB Code of Professional Conduct contain?", opts: ["3", "7", "10", "12"], ans: 3, explain: "The ARB code contains 12 standards. The RIBA code has 3 principles." },
  { q: "Who employs the Clerk of Works?", opts: ["The contractor", "The architect", "The client", "The local authority"], ans: 2, explain: "The Clerk of Works is employed by the client but acts as the architect's representative on site." },
  { q: "In a Limited Partnership, who has management responsibility?", opts: ["Limited partners only", "All partners equally", "General partner(s) only", "An external manager"], ans: 2, explain: "General partners have management responsibility and personal liability. Limited partners can only invest and cannot make management decisions." },
  { q: "What distinguishes Construction Management from Management Contracting?", opts: ["The design team is different", "The client contracts directly with subcontractors", "There is no main contractor", "The architect manages the site"], ans: 1, explain: "In Construction Management, the CLIENT enters into contracts directly with subcontractors. In Management Contracting, the management contractor does." },
  { q: "The hourly rate charged for an architect's staff member is approximately:", opts: ["1.5× their salary", "2× their salary", "3× their salary", "4× their salary"], ans: 2, explain: "Hourly rate = Salary + Overheads (≈ salary) + Profit (≈ salary) = 3× salary." },
  { q: "Which accounting method is recommended for architectural firms?", opts: ["Cash Accounting", "Accrual Accounting", "Both equally", "Neither — firms use bookkeeping"], ans: 1, explain: "Accrual accounting provides a more comprehensive picture and prevents hidden debt accumulation." },
  { q: "The Balance Sheet shows the firm's financial position:", opts: ["Over a year", "Over a quarter", "At a particular moment in time", "Over the project duration"], ans: 2, explain: "The Balance Sheet shows position at a specific moment. The Income Statement covers a stated period." },
  { q: "What does the word 'architect' mean in Greek?", opts: ["Master designer", "Chief builder", "City planner", "Creative thinker"], ans: 1, explain: "From 'architekton': arkhi (chief) + tekton (builder) = chief builder." },
  { q: "A Group Practice is best described as:", opts: ["One firm with multiple disciplines", "Separate firms from different disciplines", "Separate architectural firms retaining independence", "A temporary project alliance"], ans: 2, explain: "Group Practice = separate architectural firms combining while retaining independence and not sharing profits." },
  { q: "In the percentage fee method, works to existing buildings typically cost:", opts: ["Less than new works", "The same as new works", "More than new works", "It depends on the contractor"], ans: 2, explain: "Existing building works range from 7.75–16.5% vs new works at 5–11.25%." },
  { q: "An LLP must:", opts: ["Have unlimited liability for all members", "End its name with 'LLP' and file returns", "Have at least 5 members", "Be approved by RIBA"], ans: 1, explain: "An LLP must end its name with 'LLP' and file returns with the registrar. Members' liability is limited." },
  { q: "Which is NOT one of the three RIBA Code principles?", opts: ["Integrity", "Competence", "Insurance", "Relationships"], ans: 2, explain: "RIBA's 3 principles: Integrity, Competence, Relationships. Insurance is ARB Standard 8." },
  { q: "In Design-and-Build, who receives the brief directly from the client?", opts: ["The architect", "The QS", "The contractor", "The project manager"], ans: 2, explain: "In Design-and-Build, the contractor receives the brief directly from the client and undertakes both design and construction." },
  { q: "Which organisational framework uses project leaders between the principal and assistants?", opts: ["Shallow", "Deep", "Flat", "Circular"], ans: 1, explain: "Deep framework introduces project leaders who receive instructions from the principal and direct groups of assistants." },
];

const CHECKLIST = [
  "Define architecture and the six elements of a profession",
  "Explain the historic role of the architect from ancient times to present",
  "Distinguish ARB (prescribes) from RIBA (validates) and their codes",
  "Describe the UK education path: Part 1 → Part 2 → Part 3",
  "Name the four groups of the building team and key members",
  "Explain each design team member's role (Architect through Consultants)",
  "Explain each contracting team member's role",
  "Compare all traditional practice types: Sole Principal, 3 partnership types, 3 company types",
  "Distinguish Integrated Practice vs Group Practice vs Consortia",
  "Compare all non-traditional systems: Design-and-Build, Design-and-Develop, Management Contracting, Construction Management, Project Management",
  "Explain three organisational frameworks: Shallow, Deep, Mixed",
  "List the 6 stages of project organisation (RIBA Plan of Work)",
  "State the three criteria: Quality, Time, Cost",
  "Describe the four fee methods with calculations",
  "Calculate hourly rate (3× salary) with examples",
  "Know percentage fee payment stages and approximate percentages",
  "Distinguish disbursements from expenses",
  "Explain termination rights and obligations",
  "Compare accrual vs cash accounting",
  "State the Balance Sheet equation and Income Statement components",
];

// ─────────── App Component ───────────
export default function App() {
  const [activeLecture, setActiveLecture] = useState(0);
  const [expandedSections, setExpandedSections] = useState({});
  const [showQuiz, setShowQuiz] = useState(false);
  const [showMCQ, setShowMCQ] = useState(false);
  const [mcqAnswers, setMcqAnswers] = useState({});
  const [mcqRevealed, setMcqRevealed] = useState({});
  const [revealedQuiz, setRevealedQuiz] = useState({});
  const [showChecklist, setShowChecklist] = useState(false);
  const [checkedItems, setCheckedItems] = useState({});
  const [sidebarOpen, setSidebarOpen] = useState(false);

  const toggleSection = useCallback((key) => {
    setExpandedSections(prev => ({ ...prev, [key]: !prev[key] }));
  }, []);

  const lecture = LECTURES[activeLecture];

  const progress = useMemo(() => {
    let total = 0, done = 0;
    LECTURES.forEach((l, li) => {
      l.sections.forEach((_, si) => {
        total++;
        if (expandedSections[`${li}-${si}`]) done++;
      });
    });
    return total ? Math.round((done / total) * 100) : 0;
  }, [expandedSections]);

  return (
    <div style={{ fontFamily: "'Crimson Pro', 'Georgia', serif", background: "#FFF7F9", minHeight: "100vh", color: "#3D2B2B" }}>
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Crimson+Pro:ital,wght@0,300;0,400;0,500;0,600;0,700;1,400&family=DM+Sans:wght@400;500;600;700&display=swap');
        * { box-sizing: border-box; margin: 0; padding: 0; }
        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-thumb { background: #E8B4C0; border-radius: 3px; }
        ::-webkit-scrollbar-track { background: transparent; }
        .nav-btn { border: none; cursor: pointer; transition: all 0.25s ease; }
        .nav-btn:hover { transform: translateY(-1px); }
        .card { background: white; border-radius: 16px; border: 1px solid #F5DDE3; box-shadow: 0 2px 12px rgba(200,130,160,0.08); transition: all 0.3s ease; }
        .card:hover { box-shadow: 0 4px 20px rgba(200,130,160,0.14); }
        .tag { display: inline-block; padding: 3px 10px; border-radius: 20px; font-size: 11px; font-family: 'DM Sans', sans-serif; font-weight: 600; letter-spacing: 0.5px; text-transform: uppercase; }
        .expand-btn { width: 100%; text-align: left; background: none; border: none; cursor: pointer; padding: 0; font-family: inherit; }
        .fade-in { animation: fadeIn 0.35s ease-out; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: translateY(0); } }
        .mcq-opt { border: 2px solid #F0D0DA; border-radius: 10px; padding: 10px 14px; cursor: pointer; transition: all 0.2s; font-family: 'DM Sans', sans-serif; font-size: 14px; background: white; display: block; width: 100%; text-align: left; margin-bottom: 6px; }
        .mcq-opt:hover { border-color: #D4849B; background: #FFF0F4; }
        .mcq-opt.selected { border-color: #C06080; background: #FDE8EF; }
        .mcq-opt.correct { border-color: #6BAF7B; background: #E8F5EC; }
        .mcq-opt.wrong { border-color: #D46B6B; background: #FDECEC; }
        .sidebar-overlay { position: fixed; inset: 0; background: rgba(60,30,40,0.3); z-index: 998; }
        @media (min-width: 900px) { .sidebar-overlay { display: none !important; } }
      `}</style>

      {/* Header */}
      <header style={{ background: "linear-gradient(135deg, #F9E0E8 0%, #F2C4D3 50%, #E8A8BE 100%)", padding: "28px 24px 22px", borderBottom: "1px solid #E8B4C0", position: "sticky", top: 0, zIndex: 100 }}>
        <div style={{ maxWidth: 1200, margin: "0 auto", display: "flex", alignItems: "center", gap: 12 }}>
          <button onClick={() => setSidebarOpen(!sidebarOpen)} className="nav-btn" style={{ display: "none", background: "rgba(255,255,255,0.6)", borderRadius: 10, padding: "8px 10px", fontSize: 18 }}
            ref={el => { if (el) el.style.cssText += window.innerWidth < 900 ? ";display:block" : ";display:none"; }}>☰</button>
          <div style={{ flex: 1 }}>
            <div style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 11, fontWeight: 700, letterSpacing: 2.5, textTransform: "uppercase", color: "#8C4A60", marginBottom: 4 }}>ARCG 521 — Study Guide</div>
            <h1 style={{ fontSize: "clamp(18px, 3.5vw, 26px)", fontWeight: 700, color: "#4A1A2E", lineHeight: 1.2 }}>Architectural Professional Practice</h1>
            <div style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 12, color: "#8C4A60", marginTop: 4 }}>University of Bahrain · Lectures 1–5 · Complete Exam Preparation</div>
          </div>
          <div style={{ textAlign: "right", fontFamily: "'DM Sans', sans-serif" }}>
            <div style={{ fontSize: 11, color: "#8C4A60", fontWeight: 600, marginBottom: 4 }}>Study Progress</div>
            <div style={{ width: 120, height: 8, background: "#F5D0DB", borderRadius: 4, overflow: "hidden" }}>
              <div style={{ width: `${progress}%`, height: "100%", background: "linear-gradient(90deg, #D4849B, #B05C78)", borderRadius: 4, transition: "width 0.5s ease" }} />
            </div>
            <div style={{ fontSize: 11, color: "#8C4A60", marginTop: 2 }}>{progress}%</div>
          </div>
        </div>
      </header>

      <div style={{ maxWidth: 1200, margin: "0 auto", display: "flex", gap: 0, position: "relative" }}>
        {/* Sidebar */}
        {sidebarOpen && <div className="sidebar-overlay" onClick={() => setSidebarOpen(false)} />}
        <nav style={{
          width: 260, minWidth: 260, padding: "20px 16px", borderRight: "1px solid #F0D0DA", background: "#FFFAFB",
          position: window.innerWidth < 900 ? "fixed" : "sticky", top: window.innerWidth < 900 ? 0 : 100, height: window.innerWidth < 900 ? "100vh" : "calc(100vh - 100px)",
          overflowY: "auto", zIndex: 999,
          transform: window.innerWidth < 900 && !sidebarOpen ? "translateX(-100%)" : "translateX(0)", transition: "transform 0.3s ease"
        }}>
          <div style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 11, fontWeight: 700, letterSpacing: 2, textTransform: "uppercase", color: "#B0758A", marginBottom: 16, paddingLeft: 8 }}>Lectures</div>
          {LECTURES.map((l, i) => (
            <button key={i} onClick={() => { setActiveLecture(i); setShowQuiz(false); setShowMCQ(false); setShowChecklist(false); setSidebarOpen(false); }}
              className="nav-btn"
              style={{
                display: "flex", alignItems: "center", gap: 10, width: "100%", padding: "10px 12px", borderRadius: 10, marginBottom: 4, textAlign: "left",
                background: activeLecture === i ? "linear-gradient(135deg, #F9E0E8, #F0C8D8)" : "transparent",
                color: activeLecture === i ? "#6A2040" : "#6B4A55", fontFamily: "'DM Sans', sans-serif", fontSize: 13, fontWeight: activeLecture === i ? 600 : 400
              }}>
              <span style={{ fontSize: 18 }}>{l.icon}</span>
              <span style={{ lineHeight: 1.3 }}>{l.title}</span>
            </button>
          ))}
          <div style={{ height: 1, background: "#F0D0DA", margin: "16px 0" }} />
          <button onClick={() => { setShowMCQ(true); setShowQuiz(false); setShowChecklist(false); setSidebarOpen(false); }} className="nav-btn"
            style={{ display: "flex", alignItems: "center", gap: 10, width: "100%", padding: "10px 12px", borderRadius: 10, marginBottom: 4, textAlign: "left", background: showMCQ ? "linear-gradient(135deg, #F9E0E8, #F0C8D8)" : "transparent", color: showMCQ ? "#6A2040" : "#6B4A55", fontFamily: "'DM Sans', sans-serif", fontSize: 13, fontWeight: showMCQ ? 600 : 400 }}>
            <span style={{ fontSize: 18 }}>📝</span><span>MCQ Bank ({MCQs.length} Questions)</span>
          </button>
          <button onClick={() => { setShowChecklist(true); setShowMCQ(false); setShowQuiz(false); setSidebarOpen(false); }} className="nav-btn"
            style={{ display: "flex", alignItems: "center", gap: 10, width: "100%", padding: "10px 12px", borderRadius: 10, marginBottom: 4, textAlign: "left", background: showChecklist ? "linear-gradient(135deg, #F9E0E8, #F0C8D8)" : "transparent", color: showChecklist ? "#6A2040" : "#6B4A55", fontFamily: "'DM Sans', sans-serif", fontSize: 13, fontWeight: showChecklist ? 600 : 400 }}>
            <span style={{ fontSize: 18 }}>✅</span><span>Full Marks Checklist</span>
          </button>
        </nav>

        {/* Main content */}
        <main style={{ flex: 1, padding: "24px clamp(16px, 3vw, 32px)", maxWidth: "calc(100% - 260px)", minWidth: 0 }}>

          {/* MCQ Bank */}
          {showMCQ && (
            <div className="fade-in">
              <h2 style={{ fontSize: 24, fontWeight: 700, color: "#4A1A2E", marginBottom: 6 }}>📝 Multiple Choice Question Bank</h2>
              <p style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 14, color: "#8C5A6A", marginBottom: 24 }}>Test your knowledge across all 5 lectures. Select an answer to check.</p>
              {MCQs.map((mcq, i) => (
                <div key={i} className="card" style={{ padding: 20, marginBottom: 16 }}>
                  <div style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 12, fontWeight: 700, color: "#C06080", marginBottom: 8 }}>QUESTION {i + 1}</div>
                  <p style={{ fontSize: 15, fontWeight: 600, marginBottom: 14, lineHeight: 1.5 }}>{mcq.q}</p>
                  {mcq.opts.map((opt, j) => {
                    let cls = "mcq-opt";
                    if (mcqRevealed[i]) {
                      if (j === mcq.ans) cls += " correct";
                      else if (mcqAnswers[i] === j) cls += " wrong";
                    } else if (mcqAnswers[i] === j) cls += " selected";
                    return (
                      <button key={j} className={cls} onClick={() => {
                        if (!mcqRevealed[i]) {
                          setMcqAnswers(prev => ({ ...prev, [i]: j }));
                          setMcqRevealed(prev => ({ ...prev, [i]: true }));
                        }
                      }}>
                        <span style={{ fontWeight: 600, marginRight: 8 }}>{String.fromCharCode(65 + j)}.</span> {opt}
                      </button>
                    );
                  })}
                  {mcqRevealed[i] && (
                    <div style={{ marginTop: 12, padding: "10px 14px", background: mcqAnswers[i] === mcq.ans ? "#E8F5EC" : "#FDECEC", borderRadius: 10, fontFamily: "'DM Sans', sans-serif", fontSize: 13, lineHeight: 1.5 }}>
                      {mcqAnswers[i] === mcq.ans ? "✅ Correct! " : "❌ Incorrect. "}{mcq.explain}
                    </div>
                  )}
                </div>
              ))}
            </div>
          )}

          {/* Checklist */}
          {showChecklist && (
            <div className="fade-in">
              <h2 style={{ fontSize: 24, fontWeight: 700, color: "#4A1A2E", marginBottom: 6 }}>✅ Full Marks Checklist</h2>
              <p style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 14, color: "#8C5A6A", marginBottom: 24 }}>Can you confidently explain each of these? Check off as you master them.</p>
              <div className="card" style={{ padding: 20 }}>
                {CHECKLIST.map((item, i) => (
                  <label key={i} style={{ display: "flex", alignItems: "flex-start", gap: 10, padding: "10px 0", borderBottom: i < CHECKLIST.length - 1 ? "1px solid #F5DDE3" : "none", cursor: "pointer", fontFamily: "'DM Sans', sans-serif", fontSize: 14, lineHeight: 1.5 }}>
                    <input type="checkbox" checked={!!checkedItems[i]} onChange={() => setCheckedItems(prev => ({ ...prev, [i]: !prev[i] }))}
                      style={{ marginTop: 3, accentColor: "#C06080", width: 18, height: 18 }} />
                    <span style={{ textDecoration: checkedItems[i] ? "line-through" : "none", color: checkedItems[i] ? "#B0A0A6" : "#3D2B2B" }}>{item}</span>
                  </label>
                ))}
                <div style={{ marginTop: 16, textAlign: "center", fontFamily: "'DM Sans', sans-serif", fontSize: 14, color: "#8C5A6A" }}>
                  {Object.values(checkedItems).filter(Boolean).length} / {CHECKLIST.length} mastered
                </div>
              </div>
            </div>
          )}

          {/* Lecture content */}
          {!showMCQ && !showChecklist && (
            <div className="fade-in" key={activeLecture}>
              <div style={{ display: "flex", alignItems: "center", gap: 12, marginBottom: 8 }}>
                <span style={{ fontSize: 36 }}>{lecture.icon}</span>
                <div>
                  <div style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 11, fontWeight: 700, letterSpacing: 2, textTransform: "uppercase", color: "#C06080" }}>Lecture {lecture.id}</div>
                  <h2 style={{ fontSize: "clamp(20px, 3.5vw, 28px)", fontWeight: 700, color: "#4A1A2E", lineHeight: 1.2 }}>{lecture.title}</h2>
                </div>
              </div>
              <div style={{ height: 2, background: "linear-gradient(90deg, #E8A8BE, transparent)", marginBottom: 24, borderRadius: 1 }} />

              {lecture.sections.map((sec, si) => {
                const key = `${activeLecture}-${si}`;
                const open = expandedSections[key];
                return (
                  <div key={si} className="card" style={{ marginBottom: 16, overflow: "hidden" }}>
                    <button className="expand-btn" onClick={() => toggleSection(key)}
                      style={{ padding: "16px 20px", display: "flex", alignItems: "center", justifyContent: "space-between" }}>
                      <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
                        <span style={{ width: 28, height: 28, borderRadius: "50%", background: open ? "linear-gradient(135deg, #D4849B, #B05C78)" : "#F5DDE3", color: open ? "white" : "#8C4A60", display: "flex", alignItems: "center", justifyContent: "center", fontFamily: "'DM Sans', sans-serif", fontSize: 12, fontWeight: 700, flexShrink: 0 }}>{si + 1}</span>
                        <span style={{ fontSize: 17, fontWeight: 600, color: "#4A1A2E" }}>{sec.title}</span>
                      </div>
                      <span style={{ fontSize: 18, color: "#C06080", transform: open ? "rotate(180deg)" : "rotate(0)", transition: "transform 0.25s" }}>▾</span>
                    </button>

                    {open && (
                      <div style={{ padding: "0 20px 20px", animation: "fadeIn 0.3s ease-out" }}>
                        {/* Simple explanation */}
                        <div style={{ background: "#FFF5F8", borderRadius: 12, padding: 16, marginBottom: 16, borderLeft: "4px solid #E8A8BE" }}>
                          <div className="tag" style={{ background: "#FDDFE8", color: "#A04A65", marginBottom: 8 }}>Simple Explanation</div>
                          <p style={{ fontSize: 15, lineHeight: 1.7, color: "#5A3545" }}>{sec.simple}</p>
                        </div>

                        {/* Academic explanation */}
                        <div style={{ background: "#FBF0F4", borderRadius: 12, padding: 16, marginBottom: 16, borderLeft: "4px solid #D4849B" }}>
                          <div className="tag" style={{ background: "#F0C8D8", color: "#7A3050", marginBottom: 8 }}>Academic Detail</div>
                          <p style={{ fontSize: 14, lineHeight: 1.75, color: "#4A2535" }}>{sec.academic}</p>
                        </div>

                        {/* Key Terms */}
                        {sec.keyTerms && sec.keyTerms.length > 0 && (
                          <div style={{ marginBottom: 16 }}>
                            <div className="tag" style={{ background: "#E8D4F0", color: "#6A3080", marginBottom: 10 }}>Key Terms</div>
                            <div style={{ display: "grid", gap: 8 }}>
                              {sec.keyTerms.map((kt, ki) => (
                                <div key={ki} style={{ background: "white", border: "1px solid #F0D0DA", borderRadius: 10, padding: "10px 14px" }}>
                                  <span style={{ fontWeight: 700, color: "#7A3050", fontFamily: "'DM Sans', sans-serif", fontSize: 13 }}>{kt.term}:</span>{" "}
                                  <span style={{ fontSize: 13, color: "#5A3545", fontFamily: "'DM Sans', sans-serif", lineHeight: 1.5 }}>{kt.def}</span>
                                </div>
                              ))}
                            </div>
                          </div>
                        )}

                        {/* Exam Points */}
                        {sec.examPoints && sec.examPoints.length > 0 && (
                          <div style={{ background: "#FFF8E8", borderRadius: 12, padding: 16, marginBottom: 16, border: "1px solid #F0E0C0" }}>
                            <div className="tag" style={{ background: "#F8E8C8", color: "#8A6020", marginBottom: 10 }}>🎯 High-Yield Exam Points</div>
                            {sec.examPoints.map((ep, ei) => (
                              <div key={ei} style={{ display: "flex", gap: 8, marginBottom: 6, fontFamily: "'DM Sans', sans-serif", fontSize: 13, lineHeight: 1.55, color: "#5A4020" }}>
                                <span style={{ color: "#C09030", fontWeight: 700, flexShrink: 0 }}>▸</span>
                                <span>{ep}</span>
                              </div>
                            ))}
                          </div>
                        )}

                        {/* Confusion points */}
                        {sec.confusion && (
                          <div style={{ background: "#FFF0F0", borderRadius: 12, padding: 14, marginBottom: 8, border: "1px solid #F0C8C8" }}>
                            <div className="tag" style={{ background: "#F8D0D0", color: "#904040", marginBottom: 8 }}>⚠️ Common Confusion</div>
                            <p style={{ fontFamily: "'DM Sans', sans-serif", fontSize: 13, lineHeight: 1.55, color: "#6A3030" }}>{sec.confusion}</p>
                          </div>
                        )}
                      </div>
                    )}
                  </div>
                );
              })}

              {/* Quick Quiz Section */}
              <div style={{ marginTop: 32 }}>
                <button className="nav-btn" onClick={() => setShowQuiz(!showQuiz)}
                  style={{ display: "flex", alignItems: "center", gap: 10, padding: "14px 24px", borderRadius: 12, background: "linear-gradient(135deg, #D4849B, #B05C78)", color: "white", fontFamily: "'DM Sans', sans-serif", fontSize: 15, fontWeight: 600, boxShadow: "0 4px 16px rgba(180,80,120,0.25)" }}>
                  <span style={{ fontSize: 20 }}>🧠</span>
                  {showQuiz ? "Hide" : "Show"} Active Recall — Lecture {lecture.id}
                </button>

                {showQuiz && (
                  <div className="fade-in" style={{ marginTop: 16 }}>
                    {lecture.quiz.map((qa, qi) => (
                      <div key={qi} className="card" style={{ padding: 16, marginBottom: 12 }}>
                        <p style={{ fontSize: 15, fontWeight: 600, color: "#4A1A2E", marginBottom: 10, lineHeight: 1.5 }}>Q{qi + 1}: {qa.q}</p>
                        <button className="nav-btn" onClick={() => setRevealedQuiz(prev => ({ ...prev, [`${activeLecture}-${qi}`]: !prev[`${activeLecture}-${qi}`] }))}
                          style={{ padding: "8px 16px", borderRadius: 8, background: revealedQuiz[`${activeLecture}-${qi}`] ? "#F0E8EB" : "#FDE8EF", color: "#8C4A60", fontFamily: "'DM Sans', sans-serif", fontSize: 13, fontWeight: 600 }}>
                          {revealedQuiz[`${activeLecture}-${qi}`] ? "Hide Answer" : "Reveal Answer"}
                        </button>
                        {revealedQuiz[`${activeLecture}-${qi}`] && (
                          <div style={{ marginTop: 10, padding: "10px 14px", background: "#F5FFF5", borderRadius: 10, fontFamily: "'DM Sans', sans-serif", fontSize: 13, lineHeight: 1.6, color: "#2A5A2A", border: "1px solid #C8E8C8" }}>
                            {qa.a}
                          </div>
                        )}
                      </div>
                    ))}
                  </div>
                )}
              </div>
            </div>
          )}
        </main>
      </div>

      {/* Footer */}
      <footer style={{ textAlign: "center", padding: "20px 16px", borderTop: "1px solid #F0D0DA", fontFamily: "'DM Sans', sans-serif", fontSize: 12, color: "#B0758A", marginTop: 40 }}>
        ARCG 521 Study Guide · Covers Lectures 1–5 · All slide content included · Good luck on your exam! 🌸
      </footer>
    </div>
  );
}
