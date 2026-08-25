# FIT5032 A1.1: Design Report

Project: UrbanGreens Hub

Topic: Urban greening, tree planting and biodiversity

## Section 1: Executive Summary

UrbanGreens Hub is a proposed web application for a Melbourne-based environmental not-for-profit organisation focused on urban greening, community tree planting, and biodiversity education. The client wants to make local climate action easier to discover, easier to join, and easier to measure. Its main organisational objectives are to increase volunteer participation, improve public awareness of native plants and urban wildlife, and give staff a clearer way to manage planting events and community impact data.

The target audience includes students seeking meaningful volunteer opportunities, residents who want greener and cooler neighbourhoods, and NFP staff who need practical tools for event administration. Research into similar organisations suggests that successful environmental websites combine clear calls to action with educational content, visible impact measures, and simple pathways into volunteering. Greening Australia highlights the importance of restoring nature in cities through urban canopy, green corridors, water quality, and community access to nature. TreeProject and Port Phillip EcoCentre show that hands-on volunteering needs clear event details, training expectations, and visible ecological outcomes. Conservation Volunteers Australia also demonstrates the value of making local projects searchable and action-oriented.

The primary goal of UrbanGreens Hub is therefore to connect people with nearby greening activities while supporting the NFP's internal workflow. Public users will be able to browse events, filter opportunities by suburb and accessibility needs, register for activities, explore a green map of planting sites, and learn about biodiversity. Registered users can manage bookings and provide feedback after events. Admin users can manage events, monitor registrations, review ratings, export data, and track simple impact metrics such as volunteer numbers and trees pledged.

The design prioritises clarity, trust, and accessibility. The sitemap separates public learning, event participation, map-based discovery, account functions, and admin operations. The low-fidelity prototype focuses on three business requirements: validated event registration, geo-location based site discovery, and role-based administration. Together, these features provide a realistic foundation for later Vue 3 development while keeping the A1.1 design scope focused and achievable.

Word count: 322

## Section 2: Sitemap

The sitemap is embedded in the PDF as Figure 1.

Figma source: https://www.figma.com/design/bl27b2nuZ3rCHQ5b9jmGcT/FIT5032-A1.1-UrbanGreens-Hub-Generated-Figures?node-id=1-2

## Section 3: User Personas

### Persona 1: Maya Chen - Student Volunteer

Maya Chen is a 20-year-old Monash University student living in Clayton and commuting across Melbourne several days a week. She studies information technology, cares about climate action, and wants volunteering experience that feels practical rather than performative. She is comfortable using web applications, but she quickly loses interest when opportunities are hidden behind long pages or unclear instructions. Her goals are to find weekend events near public transport, understand what skills or equipment are required, and receive evidence of participation for her student portfolio. Maya's main pain points are fragmented event information, unclear time commitments, and anxiety about arriving at an event without knowing what to expect. She also wants to avoid signing up for events that are too advanced for a first-time volunteer, especially during busy assessment weeks. UrbanGreens Hub supports Maya through searchable event cards, beginner-friendly labels, clear transport and accessibility information, and a validated registration form that confirms her booking. A personal account lets her view upcoming bookings, save favourite events, and rate the experience afterwards. In a typical scenario, Maya searches for "beginner planting events near train stations", selects a Royal Park habitat day, checks the safety notes, registers with her emergency contact, and receives a confirmation summary.

### Persona 2: Helen Brooks - Community Resident

Helen Brooks is a 46-year-old parent and community member living in Brunswick. She is not a highly technical user, but she is motivated to improve local shade, reduce heat around playgrounds, and help her children learn about native plants. She usually browses on a mobile phone between work and family commitments, so she needs information to be scannable and trustworthy. Her needs are family-safe activities, clear event expectations, and a simple way to understand which local sites need community support. Helen's pain points include websites that use environmental jargon, maps that are hard to interpret, and forms that do not clearly explain privacy or safety expectations. She is also cautious about sharing contact details unless the organisation appears credible. UrbanGreens Hub helps Helen by using plain language, visual site cards, a map with list-view alternatives, and resource pages explaining local biodiversity. She can filter for family-friendly events, accessible paths, and short sessions. Clear icons and short summaries help her decide without reading every page in detail. In a typical scenario, Helen opens the Green Map, finds a pollinator garden project near Merri Creek, reads the site purpose, checks whether children can attend, and registers herself and one family member. After the event, she leaves a rating and reads follow-up guidance about caring for native plants at home.

### Persona 3: Omar Haddad - NFP Program Coordinator

Omar Haddad is a 34-year-old program coordinator working for the NFP. He manages volunteer events, communicates with local partners, and prepares impact summaries for internal reporting. Omar is confident with spreadsheets and email tools, but his current workflow is repetitive and vulnerable to mistakes when registrations change quickly. His goals are to reduce manual spreadsheet work, avoid overbooking events, identify which activities need promotion, and export reliable data for reporting. He also needs different access levels so that volunteers cannot see staff-only information. His pain points are duplicated registrations, incomplete participant information, last-minute cancellations, and limited visibility over attendance trends. UrbanGreens Hub supports Omar through an admin dashboard protected by role-based access. He can create and edit events, view searchable volunteer tables, monitor average ratings, export CSV files, and send bulk updates to selected participants. In a typical scenario, Omar logs in as an admin, checks that a Yarra Riverbank planting event is almost full, exports the volunteer list, sends preparation instructions, and reviews dashboard metrics showing total registrations and trees pledged. This gives him a faster operational workflow while keeping public users separate from admin-only data.

Total persona word count: 606

## Section 4: Wireframes / Low-fidelity Prototype

The PDF includes three wireframes focused on:

1. BR (B.1): Validations - Event Discovery and Registration. Figma source: https://www.figma.com/design/bl27b2nuZ3rCHQ5b9jmGcT/FIT5032-A1.1-UrbanGreens-Hub-Generated-Figures?node-id=1-94
2. BR (E.2): Geo Location - Green Map and Site Discovery. Figma source: https://www.figma.com/design/bl27b2nuZ3rCHQ5b9jmGcT/FIT5032-A1.1-UrbanGreens-Hub-Generated-Figures?node-id=1-155
3. BR (C.2): Role-based Authentication - Admin Dashboard. Figma source: https://www.figma.com/design/bl27b2nuZ3rCHQ5b9jmGcT/FIT5032-A1.1-UrbanGreens-Hub-Generated-Figures?node-id=1-209

## References

- Greening Australia. Nature in Cities. https://www.greeningaustralia.org.au/programs/nature-in-cities/
- TreeProject. Corporate Environmental Volunteering in Melbourne, Victoria. https://treeproject.org.au/corporate-environmental-volunteering-melbourne-victoria/
- Port Phillip EcoCentre. Urban Wildlife Conservation Day. https://www.ecocentre.com/programs/community-programs/corporate-volunteering/urban-wildlife/
- Conservation Volunteers Australia. Urban Shade Forests. https://cva.org.au/greener-cities/urban-shade-forests/
- City of Melbourne. Urban Forest Strategy and Urban Forest Fund. https://www.melbourne.vic.gov.au/urban-forest-strategy
