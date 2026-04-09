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

## Technologies Used

- HTML5: Semantic structure and Constraint Validation API.
- CSS3: Custom properties, Flexbox, Grid, and Scroll-Snap.
- Lighthouse: Performance and Accessibility auditing.
- Google Fonts: Integration of _Cinzel_ and _Inter_.

## Global Features & Design System

The Clent Consort web application is built upon a unified design system that ensures visual harmony and technical efficiency across all “movements” (pages) of the site.

### The Design System (CSS Architecture)

To ensure the code is DRY (Do not Repeat Yourself) and scalable, I implemented a utility-first approach to layout based on “Primitives.”

#### The Modular Scale

I used CSS Custom Properties (--s-1 to \--s5) to create a mathematical spacing scale. This is to make sure the “rhythm” of margins and paddings is consistent across the site.

#### Layout Primitives

- **.l-stack**: Manages vertical spacing between elements automatically, preventing the need for manual margin-top declarations on individual components.
- **.l-switcher**: An intrinsic layout tool that allows elements to sit side-by-side on large screens but automatically stack vertically when a threshold is met, reducing the reliance on complex media queries.
- **.l-center**: A utility that keeps content within a readable maximum width while centering it on the screen.
- **.l-reel**: Provides a smooth, horizontal scrolling experience for galleries or lists on mobile devices.

#### Header & Navigation

The header serves as the primary "Command Centre" for the user.

- **Persistent Navigation**: Using position: sticky, the header remains available at all times, ensuring the user never feels "lost in the score."
- **Semantic Accessibility**: I used the aria-current="page" attribute to provide a visual and structural cue to users (and screen readers) regarding their current location.
- **Dual-Context Navigation**:
  - **Public Nav**: Focused on the "EPK" experience (About, Events, Contact).
  - **Member Nav**: A tailored "Dashboard" navigation for the _members.html_ page.
- **Landscape Optimisation:** Implemented a specific "Short-Height" media query (max-height: 450px) to compress the header and brand assets. This prevents the UI from obscuring content on landscape mobile devices, maintaining a functional "aspect ratio" for the user.

#### Footer

The footer provides a "Coda" to every page, offering secondary navigation and social proof.

- **Three-Column Grid:** Managed via a responsive flex layout that elegantly stacks into a single column on mobile devices.
- **Interactive Elements:** Includes a "Member Login" gateway and a "Top ↑" anchor to improve long-page navigation.
- **SVG Integration:** Social media icons are implemented using inline SVGs, ensuring high-performance loading and perfect scaling on all display types.

##

## Individual Pages

### index.html

**Strategic Goal:** To immediately establish the brand's "Cathedral Aesthetic" and provide a clear path to upcoming performances.

**Feature:** High-Performance Hero Section

- **Technical Implementation:** Utilises fetchpriority="high" and preload to ensure the Largest Contentful Paint (LCP) is as fast as possible.
- **Fluid Typography**: Employs the CSS clamp() function for the main heading, ensuring a seamless responsive transition without the need for multiple media queries.
- **Visual Hierarchy:** Uses a dark linear-gradient overlay on the hero image to guarantee text legibility and meet accessibility contrast standards.
- **Min-height: 80vh**: set as 100vh behaved strangely on some mobile browser address bars, and the navigation was to be kept visible at the bottom of the fold.

**User Flow:** The primary Call to Action (CTA) "Our Next Project" directs users straight to the Events page, facilitating the "Patron’s Path."

### about.html

**Strategic Goal:** To communicate the ensemble's unique "Project-Based" identity and the spiritual/architectural philosophy behind their work.

**Feature: "Project Rhythm" Interactive Slider**

- Technical Implementation: A "Pure CSS" slider built using scroll-snap-type. This provides a native-feeling mobile swipe experience without the overhead of JavaScript libraries.
- Scroll-Driven Animations: Utilises the view-timeline API to animate content opacity and scale as the user scrolls through the stages, creating a dynamic "reveal" effect.

**Feature: Conductor's Sidebar**

- Layout Pattern: Employs an intrinsic .sidebar primitive. By using a high flex-grow value on the text, the layout self-optimises for various screen sizes, stacking vertically only when necessary to maintain readability.

**Visual Polish:** Uses a subtle sepia filter and contrast adjustment on the conductor's headshot to align with the "Cathedral Aesthetic" and provide a consistent tonal warmth.

Lighthouse Report: The About page achieved a Performance score of 85\. This 'performance cost' was a conscious design choice to prioritise high-impact visual storytelling via background videos. To mitigate the impact, I implemented poster images and used the playsinline attribute to ensure efficient loading on mobile devices.

### events.html

**Strategic Goal:** To provide a comprehensive record of the ensemble's track record while highlighting the most important upcoming "Next Project."

**Feature: Featured Event Card**

- **Technical Implementation:** Leverages the .l-sidebar primitive inside a .box.invert container. This creates a high-contrast "Call to Action" area that is fully responsive.
- **Visual Polish:** Uses aspect-ratio: 16 / 9 for the event imagery on mobile to maintain consistency, which adapts to a full-height cover on larger viewports.

**Feature: Recent Performance Reel**

- **Layout Pattern:** Utilises the .l-reel primitive. This allows for horizontal "overflow" scrolling on mobile, providing a tactile way to browse recent history without creating a "long scroll" for the user.

**Feature: Past Events Archive**

- **Clean Code Approach:** Implemented as a list of .archive-item components. By using flexbox with a high flex-grow value on descriptions, the archive functions as a self-aligning table that automatically stacks on smaller screens.
- **Semantics:** Extensive use of the \<time\> element ensures the chronological data is accessible and SEO-friendly.

### contact.html

**Strategic Goal:** To provide clear, distinct pathways for two different user groups: those looking to book the ensemble and those looking to join it.

**Feature: Dual-Form Switcher Layout**

- **Technical Implementation:** Utilises the .l-switcher layout primitive. This ensures that the General Enquiry and Audition forms sit side-by-side on larger displays but intelligently stack on mobile devices once the 60rem threshold is reached.
- **Intrinsic Responsiveness:** By allowing the layout to dictate its own "snap point," the design remains robust across a vast array of viewport sizes without redundant media queries.

**Feature: High-Contrast Form Design**

- **Visual Hierarchy:** Uses "White Well" inputs against the .invert (dark) background. This creates an immediate focal point for the user, guiding them toward the input fields.
- **Interaction Design**: Implemented custom :focus states with a gold glow and a translateY(-2px) hover effect on buttons, providing tactile feedback that mimics a responsive physical interface.

**Accessibility**: Every form field is explicitly linked to a unique \<label\> and includes required attributes for robust client-side validation.

**Future Features:** Currently, the contact forms are functional on the front-end but do not submit data to a live server. In Phase 2, these would be connected to an API or a back-end service like EmailJS or a Python/Django database.

### members.html

**Strategic Goal:** To provide a centralised, mobile-optimised "Single Source of Truth" for active ensemble members to access logistics and rehearsal materials.

**Feature: Interactive Dashboard Navigation**

- **Technical Implementation:** Utilises a specialised "Dashboard Nav" that features a horizontal scroll on mobile devices. This ensures all four key sections (Schedule, Logistics, Library, Learning) are instantly accessible without taking up significant vertical space.

**Feature: Semantic Rehearsal Ledger**

- **Data Structure:** Employs HTML Description Lists (\<dl\>) to ensure schedules and logistics are accessible to screen readers and structurally sound.

**Feature: Voice Part Learning Hub**

- **Layout Pattern**: Uses the .l-switcher primitive to display voice-part specific resources. The layout adapts intrinsically from a multi-column grid to a single-column stack based on the user's viewport.

**Feature: Logistics Integration**

- **UX Choice:** Includes a prominent "Logistics Pack" download button with custom :hover states and SVG-style indicators, facilitating easy access to essential project documents on the go.

**Feature: Intelligent Sidebar Orchestration**

- **Technical Implementation**: Uses an intrinsic layout pattern with high flex-grow values. This allows the primary rehearsal schedule and the supporting "Meta" information to share a row on desktop but stack logically on mobile.

**Feature: Semantic Data Display**

- **Logic**: Employs HTML Description Lists (\<dl\>) for rehearsal dates and times. This maintains a strict relationship between the "Date" (label) and the "Repertoire" (data), which is significantly more accessible than a standard bulleted list.

**Feature: Interactive Music Library**

- **UX Choice:** Implemented "Clickable Rows" using a music-row-link component. This increases the hit area for mobile users, making it easy to tap and download scores while on a music stand.

**Lighthouse Report: Accessibility Remediation**

- **Issue Identified:** Lighthouse Audit indicated non-sequential heading orders.
- **Action Taken:** Refactored sub-headings from `<h4>` to `<h3>` to ensure a sequentially-descending order, improving semantic navigation for screen reader users.
- **Outcome:** Score increased from 93 to 95, consistent with the rest of the site.

### login.html

**Strategic Goal:** To provide a low-friction "Member Only" gateway that demonstrates user flow and security concepts within a front-end scope.

**Feature: Interactive Security Feedback**

- **Technical Implementation**: Utilises advanced CSS pseudo-classes (:placeholder-shown, :valid, :invalid) to provide real-time visual feedback. The input border transitions from neutral to red (error) or green (success) as the user enters the "Skeleton Key."
- **Mobile Optimisation**: Input fields and buttons are designed with "Fat-Finger" targets (min-height: 3.5rem) and optimised font sizes to prevent automatic browser zooming on mobile devices.

**Accessibility**: Includes an aria-describedby link between the password input and its hint, ensuring screen reader users receive the same "Clue" as sighted users.

**Technical Note: Member Authentication Workaround**

To maintain the project's focus on HTML and CSS while still fulfilling the 'Member Resource' user story, I utilised the HTML5 Constraint Validation API. By using the ‘pattern’ attribute on the password input, I created a functional gateway that requires no client-side scripting (JavaScript) or back-end logic. This ensures the application remains lightweight, accessible, and strictly within the technical scope of the Milestone 1 brief.

### 404.html

**Strategic Goal:** To handle navigation errors gracefully and prevent user drop-off by providing a clear, thematic "Return to Home" path.

**Feature: Contextual UX Design**

- Technical Implementation: Utilises the global .l-stack and .l-center primitives to maintain visual consistency with the rest of the application.
- Dynamic Spacing: Employs a local CSS variable override (--stack-space) to increase vertical padding, ensuring the error message is the central focus of the viewport.

**Tone & Identity:** The copy ("The Silence of the Stones") maintains the "Cathedral Aesthetic," ensuring that even a technical error feels like part of the ensemble's unique brand story.

### Performance and Accessibility (Lighthouse Scores)

| Page    | Performance | Accessibility | Best Practices | SEO |
| :------ | :---------- | :------------ | :------------- | :-- |
| Index   | 93          | 95            | 96             | 100 |
| About   | 85          | 95            | 96             | 100 |
| Events  | 99          | 95            | 96             | 100 |
| Contact | 99          | 96            | 96             | 100 |
| Login   | 99          | 96            | 96             | 100 |
| Members | 99          | 95            | 96             | 100 |
| 404     | 100         | 95            | 96             | 100 |

### Testing

### **Automated Testing**

I utilised industry-standard auditing tools to ensure the application meets high performance and accessibility benchmarks.

#### **W3C Validator Results**

All HTML and CSS files were passed through the **W3C HTML Service** and **W3C Jigsaw CSS Validator**.

**W3C HTML Service**

While the W3C Validator returned a successful pass with no errors, after pointing out the need for two closing tags, it provided 'Info' regarding the use of trailing slashes on void elements (e.g., \<meta /\>, \<link /\>). I have refactored my code to remove these slashes in accordance with modern HTML5 best practices, ensuring the code is cleaner and adheres to the current living standard.

During validation of events.html, the W3C flagged the \<time\> elements for improper formatting. I resolved this by implementing the datetime attribute (ISO 8601 standard) on all event dates. This ensures that while the user sees a human-readable format (e.g., 'October 2025'), search engines and assistive technologies can accurately parse the chronological data, significantly boosting the site's SEO and accessibility.

**W3C Jigsaw CSS Validator**

The style.css file was validated using the W3C Jigsaw Service. The report returned 4 errors, mostly related to Scroll-Driven Animations (view-timeline-axis and \--slide-reveal).

**Technical Justification:** These are not syntax errors, but rather 'Future-Proof' CSS properties that are part of the emerging CSS Animation Level 4 specification. While the Jigsaw validator (limited to CSS Level 3\) does not yet recognise these properties, they are fully functional in modern browsers and provide a high-end, progressive enhancement to the user experience. I have chosen to retain these properties as they gracefully degrade in older browsers without breaking the core layout.

The final error was resolved at once. I had two definitions for .rhythm-slide, deleting scroll-snap-align: top; in favour of scroll-snap-align: start; as this is the standard-compliant value, whereas top is a non-standard shorthand.

**Manual Testing**

| Feature         | Action                    | Expected Result                     | Pass/Fail |
| :-------------- | :------------------------ | :---------------------------------- | :-------- |
| Skeleton Key    | Input “Clent2026”         | Redirects to Members Dashboard      | Pass      |
| Form Validation | Submit empty Contact form | Browser prompts for required fields | Pass      |
| Sticky Header   | Scroll down any page      | Header remains visible at top       | Pass      |
