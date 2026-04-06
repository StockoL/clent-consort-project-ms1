# The Clent Consort | Project README

This project is a bespoke web application developed for **The Clent Consort**, an amateur choral ensemble based in the Clent Hills, Worcestershire. Moving beyong a simple static brochure, the application is designed to function as a dual-purpose digital ecosystem: providing a high-visibility "Electronic Press Kit" (EPK) to secure prestigious ecclesiastical residencies, while simultaneously serving as a centralised logistics hub for the active members of the choir. By applying the **5 Planes of User Experience**, the development focuses on high-performance accessibility, ensuring that the "digital performance" of the site matches the musical excellence of the ensemble itself.

## 1. Strategy Plane

**Project Goals**
The objective is to architect a high-performance, responsive web application for The Clent Consort. The site must serve as both a public-facing promotional tool and a functionpal resource hub for ensemble members.

**Primary Business Goal:** To secure at least two high-profile cathedral residencies per year by providing a 'digital portfolio' that proves musical excellence and reliability.

**Target Audience**

- **Music Enthusiasts and Patrons:** Seeking high-quality liturgical and secular choral performances.
- **Ecclesiastical Stakeholders:** (e.g. Cathedral Deans) Requiring evidence of professional standards and musical reliability for residencies.
- **Prospective Members:** Auditioning singers looking for repertoire depth.
- **Active Choristers:** Requiring a "Single Source of Truth" for logistics and rehearsal materials.

**User Stories**

1. Local Resident | Access to a performance calendar | To attend upcoming local events.
2. Prospective Member | Review of current repertoire and engagements | To assess the musical alignment and commitment level of the choir.
3. Cathedral Dean | Professional digital presence | To verify the choir is a "safe pair of hands" for cathedral services.
4. Current Member | Centralised resource access | To retrieve sheet music and rehearsal schedules efficiently.

**Research and Rationale**
To ensure the site meets real-world needs, a product audit of local ensemble websites was conducted. Findings show that most provided concert dates and an engaging Electronic Press Kit (EPK) style experience for stakeholders such as Cathedral Deans. However, relatively few boasted an effective "members'" area for resource sharing and scheduling, presumably opting for alternative means of internal organisation.

**Prioritisation (Importance vs. Feasibility)**

- **High Priority/High Feasibility:** Responsive calendar and contact form (Core UX).
- **High Priority/Low Feasibility:** Integrated member-only resources portal with login (deferred to Phase 2 to maintain project timeline/Scope).

---

## 2. Scope Plane

**Objective Requirements**

- **Public Presence:** Establish a professional "digital portfolio" to secure cathedral residencies.
- **Information Access:** Provide a friction-free way for the public to find event dates and locations.
- **Member Support:** Provide a central "notice board" for chorister logistics.

**Functional Requirements**

- **Mobile-First Navigation:** A fully responsive, accessible menu system.
- **Form Validation:** A robust Contact/Booking form with client-side validation to ensure data integrity.
- **Performance Gallery:** A curated visual record of past and upcoming engagements using optimised imagery for fast loading.
- **Accessibility (WCAG 2.1):** Ensuring semantic HTML and ARIA labels are utilised throughout.

**Feature Prioritisation and MVP Thinking**

- **Responsive Concert List** | High Importance/High Feasibility | Build Now (MVP)
- **Validated Contact Form** | High Importance/High Feasibility | Build Now (MVP)
- **Member Resource Area** | Medium Importance/High Feasibility | Build Now (MVP)
- **Secure Member Login** | High Importance/Low Feasibility | Build Later (Phase 2)

**Constraints and Exclusions**
In the interest of meeting the project deadline and maintaining high code quality, a secure login system is currently out of scope. The "Member Resource Area" need will be met via a public but unlinked page in Phase 1. This satisfies the user's need for information without the technical "scope creep" of backend database management at this stage.

---

## 3. Structure Plane

**Information Architecture**
The content of the site is organised into a shallow, logical hierarchy to minimise cognitive load and ensure an intuitive user experience.

- **Top-Level Navigation (Public):**
  - **Home:** A high-impact "Overture" providing immediate identity and the primary Call to Action (Next Performance).
  - **About:** Detailed biographies and the Digital EPK for stakeholders.
  - **Events:** A chronological ledger of upcoming and recent events.
  - **Contact:** A functional hub for bookings and enquiries.
- **Second Level (Internal):**
  - **Member Resource Area:** A dedicated area for rehearsal schedules and repertoire (accessible via the footer to keep the main navigation "clean").

**User Flow (The Journey)**
To ensure "easy-to-follow journeys," the site is designed around key user paths:

- **The Patron's Path:** Home>Events>Venue Map/Details>Contact (for enquiries).
- **The Stakeholder's Path:** Home>About (Credentials)>Events (Track Record)>Contact (Booking).

**Interaction Design**

- **Predictable Navigation:** Consistent placement of the navigation bar across all pages ensures the user never feels "lost in the score."
- **Resilient UX (404 Strategy):** A custom 404 page is implemented. To avoid "dead ends," it features a prominent **"Return to Home"** button. This is a strategic choice over a browser "Back" button to ensure the user stays within the application's intended flow.

---

## 4. Skeleton Plane

**Navigation Design**

- **Persistent Header:** A fixed-position navigation bar provides constant orientation. On mobile, this collapses into a "Hamburger Menu" to conserve screen "real estate," while on desktop, it expands to a full horizontal menu for immediate access.
- **Footer Navigation:** Provides secondary links to the Member Resource Area and Social Media, ensuring the primary header remains "uncluttered."

**Interface Design (The "Controls")**

- **Primary CTA:** The "Next Performance" button and "Contact" link will be styled with high visual weight to ensure the user knows exactly what to do instantly.
- **Form Inputs:** The contact form is designed with clear labels and placeholder text, providing immediate feedback during user interaction.

**Information Design (Layout)**

- **The "Inverted Pyramid" Approach:**
  1. **Hero Section:** Identity (Logo) and Primary CTA.
  2. **Featured Content:** Performance dates and Digital EPK highlights.
  3. **Supporting Content:** Gallery and Testimonials (Social Proof).
  4. **Logistical Footer:** Copyright, Credits, and Secondary Navigation.

**Wireframes**

- [See assets/documentation/]
- _Note: In line with "Mobile-First" design principles, wireframes were first conceived for small-screen devices before being "orchestrated" for Tablet and Desktop resolutions._

## 5. Surface Plane

**Visual Hierarchy and Guidance**
The visual design is engineered to guide the user's eye from the high-impact "Identity" (Header) to the "Action" (CTA button), using contrast and scale to establish a clear hierarchy.

**Colour Palette: "The Cathedral Aesthetic"**

- **Primary (Burgundy/Navy):** Deep, authoritative tones that evoke the excellence of the Anglican Choral Tradition.
- **Accent (Gold):** Used sparingly for Call-to-Action (CTA) elements to draw immediate attention to the most important "cues."
- **Neutral (Stone/Off-White):** Provides a high-contrast background for text to ensure maximum readability.

**Typography**

- Cinzel (Display/Headings): Chosen for its classical Roman proportions which evoke the timeless nature of choral music. Uppercase styling and increased letter-spacing (tracking) evokes luxury and historical weight.

- Inter (Body/UI): A high-performance sans-serif selected for its exceptional x-height and clarity on digital screens. This ensures that logistical information (dates/times) is accessible and easy to digest.

**Accessibility (WCAG 2.1 Compliance)**

- **Contrast:** All colour pairings are checked against WCAG AA standards to ensure text is readable for users with visual impairments.
- **Legibility:** Font sizes are chosen to maintain a minimum of 16px for body text, ensuring a comfortable reading experience on mobile devices.

**Design Principle: The "Musical Rest"**

- Strategic use of whitespace is employed as a visual "musical rest," preventing clutter and allowing any photography to take centre stage.
