# 2026 February Draft W3C Equity Maturity Model (EMM)
[as of September 24, 2026]

## 1. Introduction
The World Wide Web Consortium (W3C) establishes guidelines for the web that organizations use to guide quality governance of their digital services. Decisions we make for web services have ripple effects on the systems and societies of our world, improving or exacerbating existing power structures — no technology exists in a vacuum. As managing these various standards can be a complex process, this framework aims to introduce equity guidelines and harmonise multiple W3C guidelines including accessibility, internationalization, privacy, security, sustainable web, and web performance into a single, cohesive model that groups and organizations can use to evaluate their work and guide equity efforts. Equitable outcomes depend on integrating technical, social, environmental, and institutional domains rather than evaluating digital or policy systems in isolation.

### 1.1 About the Equity Maturity Model (EMM)
The Equity Maturity Model (EMM) is a framework designed to assist organizations in evaluating their own degree of equity impacts in a product or service, as well as systematically integrating equitable and sustainable practices into their policies, business processes, and culture. Operationalizing equity requires moving beyond transactional metrics (such as post-hoc bug counts or standard compliance checklists) toward continuous institutional governance. Using the W3C Accessibility Maturity Model (AMM) as an example, the EMM serves as a “shift-left” methodology, emphasizing the importance of preventing problems during the design and development phases (i.e., “shifting left” or a stage earlier in the project lifecycle) rather than attempting to address them after a product has launched.
The EMM provides actionable guidance for establishing, evaluating, and/or improving organizational policies and technical capabilities. It is built upon the principle that equity requires recognizing individuals do not all start from the same place, and therefore necessitates deliberate adjustments to address imbalances and ensure equitable digital environments. Because of this, the EMM is split into several “tiers” indicating the depth of an organisation’s approach in the given context. These are introduced in Section 2.1 and outlined in Table 1. An organisation should seek to fulfil all requirements at the current tier before attempting to progress to the next.

#### Table 1. Equity Maturity Model Tiers
More details in 2.1 Maturity Levels

<table>
<thead>
  <tr>
    <th align="left">Tier&nbsp;/&nbsp;Stage</th>
    <th align="left">Focus&nbsp;&amp;&nbsp;Approach</th>
    <th align="left">Characteristics &amp; Execution</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1.&nbsp;Inactive</td>
    <td>Unaware&nbsp;/&nbsp;Overlooked</td>
    <td>
      <ul>
        <li>Little to no awareness of equity needs, or these needs are consciously overlooked.</li>
        <li>No active efforts or formal recognition of equity requirements exist.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>2.&nbsp;Developing</td>
    <td>Ad-hoc&nbsp;&amp;&nbsp;Reactive</td>
    <td>
      <ul>
        <li>Recognizes the need for equity and has initiated initial planning.</li>
        <li>Activities remain ad-hoc, isolated, or reactive.</li>
        <li>Governance systems are not yet well-organized or consistently applied.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>3.&nbsp;Integrating</td>
    <td>Consistent&nbsp;&amp;&nbsp;Planned</td>
    <td>
      <ul>
        <li>An overall approach and defined roadmap are established.</li>
        <li>Equity standards are systematically integrated into policies, processes, features, functionality, and organizational structures.</li>
        <li>Execution is managed in a consistent and repeatable fashion.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>4.&nbsp;Optimizing</td>
    <td>Continuous&nbsp;Improvement</td>
    <td>
      <ul>
        <li>Equity is fully embedded into organizational culture and treated as a standard operational practice.</li>
        <li>Uses data and feedback (e.g., audit reports, equity metrics) to continuously identify disparities.</li>
        <li>Applies a “shift-left” / “by design” approach to proactively remove systemic barriers before problems recur.</li>
      </ul>
    </td>
  </tr>
</tbody>
</table>

This MM introduces criteria for equity maturity and includes guidelines from multiple W3C guidelines into one model that includes accessibility, equity, internationalization, privacy, sustainable web, and web performance guidelines so organizations may assess their practices and establish roadmaps towards greater maturity using a single EMM. While some organizations have individuals or departments that support each of these areas individually, many do not recognize the importance of these topics as a requirement or the need for governance systems on these subjects. This can limit the equity and impact of their products and services including training and documentation which are essential for inclusive digital environments. Individually and collectively, these principles have an impact on the equity of outcomes for people and the planet.
This challenge can be addressed by encouraging organizations to establish and implement governance systems within their organizations. These systems integrate equitable Information Communication Technology (ICT) standards into policies, business processes, organizational culture, and management structures in a consistent, repeatable, and measurable fashion. Only then can organizations address the complexities related to enabling equitable ICT. The EMM is grounded in Guiding Principles of Accessibility, Equity, Internationalization, Privacy, Security, Sustainable Web, and Web Performance, as follows.
Where this document refers to human rights, these should be taken to refer to those rights enshrined in the Universal Declaration of Human Rights (<a href="#UN1948">United Nations [UN], 1948</a>) and any other applicable UN Declarations specific to the group in question (such as the Convention on the Rights of Persons with Disabilities (<a href="#UN2006">UN, 2006</a>) or the Convention on the Rights of the Child (<a href="#UN2006">UN, 2006</a>).

#### Statement of Principles
- **Accessibility:** “…the extent to which products, systems, services, environments and facilities can be used by people from a population with the widest range of user needs, characteristics and capabilities to achieve specified goals in specified contexts of use.”  (<a href="#W3CAMM">World Wide Web Consortium [W3C], 2025</a>)  
- **Equity:** “…equity means recognizing that we do not all start from the same place and must acknowledge and make adjustments to imbalances. The process is ongoing, requiring us to identify and overcome intentional and unintentional barriers arising from bias or systemic structures.” (<a href="#NACE">National Association of Colleges and Employers [NACE], n.d.</a>)
- **Internationalization:** “…the design and development of a product, application or document content that enables easy localization for target audiences that vary in culture, region, or language.” (<a href="#i18n">W3C, 2025</a>)
- **Privacy:** “…a user's ability to control or influence what information related to them may be collected and stored and by whom and to whom that information may be disclosed.” (<a href="#ping">W3C, 2019</a>)
- **Security:** “…the protection of web users, data, and resources against unauthorized access, malicious exploitation, data breaches, and compromise of system integrity.” (<a href="#wsig">W3C, 2025</a>)
- **Sustainability / Sustainable Web:** “…digital sustainability focuses on creating web products and services that put people and the planet first… designed, built, and delivered in a way that respects environmental limits by minimizing energy consumption and carbon emissions.” (<a href="#wsg">W3C, 2026</a>)
- **Web Performance:** “…how fast a site loads and responds to user interaction, ensuring digital experiences are efficient, usable, and functional regardless of device capabilities or network constraints.” (<a href="webperf">W3C, 2026</a>)

This proposed EMM describes an overall framework for establishing a robust ICT program and identifying areas for improvement. The EMM is a tool that:
- **assesses** the current effectiveness and capabilities of an entire organization or subunits within the organization
- **supports** identification of gaps between the current capabilities and the next level of maturity
- **plans** for next steps to improve the organization’s performance over time

Organizations know when they are doing well (or poorly) with this maturity model’s stated principles using audit reports and bug counts. However, these metrics don’t indicate how the organization is doing operationally to continue to produce equitable products without examining some key corporate processes. Quantitative metrics alone are insufficient; qualitative feedback, journey mapping, and community-based evaluation are essential to understand the root causes of systemic inequities. The EMM is a big part of a “shift-left” or “by design” methodology of preventing problems from recurring, not fixing them after they have happened.

### 1.2 Difference from Compliance
Equity maturity modeling is fundamentally different from traditional conformance or compliance testing, though some of the underlying skills are transferrable. While conformance testing such as an audit or a bug count provides a snapshot of a specific product’s adherence to standards at a single point in time, maturity modeling provides a holistic view of an organization’s long-term capability to produce equitable outcomes. Operational models must evaluate both direct user experience (e.g., accessibility, interface design) and indirect systemic burdens (e.g., resource allocation, energy/bandwidth consumption, structural access barriers). The EMM aims to provide a framework for evaluating the equity considerations of a product or service and provide guidance an organization may use to incorporate equitable principles.
Instead of focusing solely on the end product, the EMM evaluates the effectiveness of an organization’s internal operations regarding a specific product or service. It identifies where the organization’s product or service is performing equity functions well and where improvements are needed to remove systemic barriers and harms, or other issues. Institutional maturity is indicated by how actively marginalized communities and individuals with lived experience are integrated into decision-making. Evaluating progress requires disaggregating quantitative data by demographic, socioeconomic, and structural stratifiers to expose hidden disparities. The EMM may offer guidance for maturing the organization’s approach to equity.
### 1.3 Audience
The EMM is intended to guide and evaluate levels of service-related maturity in both public and private sector organizations at any scale. While the framework encompasses the full scope of an organization’s responsibilities regarding the specific product or service, it can also be used to measure the maturity level of specific sub-units, provided the scope is clearly identified in reporting.
The primary audience for this model includes, but is not limited to:
- **Executive Leadership:** Those responsible for the organization’s strategic direction and high-level commitment to equity.
- **Management:** Individuals responsible for implementing equity maturity policies and business processes, specific services, or individual projects.
- **Subject Matter Experts:** Specialists who develop the actions, metrics, and governance systems required to sustain an equitable organizational culture.
The EMM is structured around several organizational dimensions where maturity can improve conformance with equity standards and regulations. This section details the fundamental structure of the model, specifically the maturity levels used for assessment.

## 2. Maturity Model Structure
Most maturity models consist of a series of levels that represent increasing stages of organizational capability. For the EMM, each level is defined by specific controls, processes, and proof points, which are the documented evidence an organization can use to verify its attainment of a particular maturity stage. This section describes the goal structure and Section 5 outlines the <strong>Organizational Equity Maturity Model Spectrum</strong>.

### 2.1 Maturity Levels
The EMM evaluates a service or organization’s progress across four distinct tiers of maturity. These levels shift the focus from reactive “point-in-time” fixes toward a “shift-left” methodology that prevents inequities from recurring by embedding equitable practices into core processes by design.
- **Inactive:** At this stage, there is little to no awareness of equity needs (or these needs are consciously overlooked), and no active efforts or formal recognition of these requirements exist.
- **Developing:** The service / organization has recognized the need for equity and initiated planning. However, activities remain ad-hoc, and governance systems are not yet well-organized or consistently applied.
- **Integrating:** The service / organization has established a defined roadmap and an overall approach. Equity standards are integrated into policies, processes, features, functionality, and structures in a consistent and repeatable fashion.
- **Optimizing:** Equity is fully embedded into the organizational culture and is treated as a standard part of all operations. The organization practices continuous review / improvement by using data and feedback (such as audit reports and equity metrics) to identify disparities and proactively remove systemic barriers.

### 2.2 Components of the Model
To measure maturity effectively, the model utilizes the following structural components:
- **Dimensions:** Essential aspects or functional areas of a service / organization (such as Information Communication Technology (ICT) development, personnel, or procurement) where equity maturity is measured.
- **Maturity Levels:** The granular levels (1 (Inactive) through 4 (Optimizing)) used to signify the specific progress made within each dimension.
- **Proof Points:** The specific criteria and supporting evidence used to validate an organization’s claim to a particular maturity level.
- **Technical & Equity Framework Alignment:** The deliberate pairing of code-level W3C technical standards with qualitative human rights and equity impact assessments. This component establishes the operational connection between technical specifications (how a digital service functions) and human rights frameworks (who is impacted and how power is distributed).

## 3. Dimensions of Equity Maturity
The EMM takes inspiration from the structural framework of the W3C Accessibility Maturity Model (<a href="#W3CAMM">W3C, 2025</a>) and maps these dimensions to the United Nations Sustainable Development Goals (<a href="#UN2015">UN, 2015</a>) to create a holistic view of organizational equity and sustainability. The Proof Points listed here are not to be taken as exhaustive.

### 3.1 Communications
**Description:** Information must be accessible to the widest audience possible, removing barriers to access and providing equivalent alternatives for all users (<a href="#W3CAMM">W3C, 2025</a>). This includes addressing discrimination on the basis of protected characteristics in information sharing and ensuring equitable access to technology (<a href="#UN2015">UN, 2015</a>).

#### Proof Points
- Adoption of inclusive language that prevents discrimination on the basis of protected characteristics (<a href="#UN2015">UN, 2015</a>).
- Ensuring communications are renderable in multiple formats to provide equivalent access, and accessible under low-bandwidth conditions (<a href="#W3CAMM">W3C, 2025</a>).

#### Technical & Equity Framework Alignment
- **W3C Technical Rules:** W3C Web Content Accessibility Guidelines (<a href="#wcag22">WCAG 2.2, World Wide Web Consortium, 2023</a>) and Internationalization (I18n) Guidelines (<a href="#i18n_mission">W3C, n.d.</a>).
- **Paired Equity Framework:** UN Convention on the Rights of Persons with Disabilities (CRPD) (<a href="#UN2006">UN, 2006</a>) & UN SDG 10 (Reduced Inequalities) (<a href="#UN2015">UN, 2015</a>).
- WCAG and I18n standards specify mechanics like screen reader accessibility, bidirectional text, and character encoding. Human Rights Impact Assessments (HRIAs) evaluate whether non-dominant language speakers or disabled users face degraded user experiences or exclusion from public information.
- 
### 3.2 ICT Development Lifecycle 
**Description:** This dimension focuses on the “shift-left” methodology, integrating accessibility, equity, privacy, safety, and sustainability into the initial design and development phases. It aims to build resilient infrastructure and foster innovation that is inclusive (<a href="#UN2015">UN, 2015</a>).

#### Figure 1 - ICT Development Lifecycle
<img src="https://github.com/w3c-cg/equity-cg/blob/main/maturity_model/emm_fig1.png" alt="Life cycle diagram with seven sections: plan, analyze, design, develop, test & evaluate, iterate, and retire. Each has a two-way arrow linking it to the sections either side. 'Retire' also has a second arrow pointing off to an unspecified direction.">

#### Proof Points
- Implementation of quality governance to manage the complexity of guidelines like Internationalization, Privacy, and Security (SDGs 9 and 16, <a href="#UN2015">UN, 2015</a>)).
- Design practices that support “Reduced Inequalities” (SDG 10, <a href="#UN2015">UN, 2015</a>) by ensuring technology does not perpetuate income or social convergence gaps (<a href="#UN2015">UN, 2015</a>).
- Any evidence of adherence to nationally or internationally recognised privacy and security standards as relevant. Examples include IEEE 7002 (<a href="#ieee2022">Institute of Electrical and Electronics Engineers [IEEE], 2022</a>) and ISO/IEC 29100:2024 (<a href="#iso2024">International Organization for Standardization & International Electrotechnical Commission [ISO/IEC], 2024</a>).
- <em>[Something about knowing who you are designing for and planning / engaging accordingly - reference for example GC25? Best interests GC? Rights of People with Disabilities?]</em>

#### Technical & Equity Framework Alignment
- **W3C Technical Rule:** W3C Privacy Interest Group (PING) Principles (<a href="#ping2025">W3C, 2025</a>), Web Security Standards (<a href="#w3c_security">W3C, n.d.</a>), & Web Neural Network/AI APIs (<a href="#w3c2026_webnn">W3C, 2026</a>).
- **Paired Equity Framework:** Data Justice HRIAs (<a href="#djl2019">Dencik et all, 2019</a>), HUDERIA (Human Rights, Democracy, and Rule of Law Impact Assessment for AI) (<a href="#arXiv2022">Leslie et al., 2022</a>), and Algorithmic Bias Audits.
- PING and W3C Security specifications technically limit data exposure and API vulnerabilities; Data Justice HRIAs and Algorithmic Bias Audits evaluate power asymmetries, training dataset bias, and whether automated scoring results in discriminatory outcomes for marginalized communities.

### 3.3 Knowledge and Skills
**Description: **Organizations must build and maintain the capacity to produce equitable products by assessing skills and addressing gaps (<a href="#W3CAMM">W3C Accessibility Maturity Model (AMM), 2025</a>). This aligns with the goal of “Quality Education” and ensuring all learners acquire the skills needed for sustainable development (<a href="#UN2015">UN, 2015</a>). <em>[Include something about education for users too maybe?]</em>

#### Proof Points
- Training programs that emphasize “Gender Equality” (SDG 5) and “Climate Action” (SDG 13) (<a href="#UN2015">UN, 2015</a>).
- Systematic integration of ICT accessibility and equity criteria into staff professional development (<a href="#W3CAMM">W3C AMM, 2025</a>).

#### Technical & Equity Framework Alignment
- **W3C Technical Rule:** W3C Accessibility Maturity Model (AMM) Knowledge & Skills Dimension (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Paired Equity Framework:** UN SDG 4 (Quality Education) (<a href="#UN2015">UN, 2015</a>) & UN SDG 5 (Gender Equality) (<a href="#UN2015">UN, 2015</a>).
- AMM rules measure internal skill integration; Equity Education Frameworks ensure staff and external users receive training on systemic bias, inclusive design, and digital literacy without tokenizing impacted groups.

### 3.4 Oversight and Culture
**Description:** This dimension assesses the organizational culture and the financial commitment to equity. It requires “Peace, Justice, and Strong Institutions” (SDG 16) within the corporate structure to ensure accountable and inclusive leadership (<a href="#UN2015">UN, 2015</a>). “Organizational culture consists of shared beliefs, values, policies, and processes established by leaders that ultimately shape employee perceptions, behaviors, and understanding.” (<a href="#W3CAMM">W3C AMM, 2025</a>) Every member of the organization should understand and be sensitive to the importance of equitable processes and outcomes.

#### Proof Points
- Executive leadership accountability for “Responsible Consumption and Production” (SDG 12) (<a href="#UN2015">UN, 2015</a>).
- Establishment of an organizational culture that promotes the “Full and Productive Employment” and inclusion of diverse groups (<a href="#UN2015">UN, 2015</a>).
- Certification to industry standards demonstrating a high standard of behaviour in relevant contexts, e.g. environmental sustainability, web accessibility, or children’s rights.

#### Technical & Equity Framework Alignment
- **W3C Technical Rule:** W3C AMM Oversight & Culture Guidelines (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Paired Equity Framework:** Lundy Model of Participation (<a href="#berj2007">Lundy, 2007</a>) & UN Guiding Principles on Business and Human Rights (UNGPs) (<a href="#ohchr2011">UN Office of the High Commissioner for Human Rights [OHCHR], 2011</a>).
- AMM provides metrics for institutional governance; the Lundy Model and UNGPs assess whether executive leadership grants impacted citizens meaningful decision-making authority (“Space,” “Voice,” “Audience,” and “Influence”).

#### <em>[Enhancement?]</em> How to Evaluate Oversight and Culture Maturity Level
- List all of the organization's culture documentation in relation to the identified proof points.
- Determine what equity maturity level your proof point documentation supports for culture.

### 3.5 Personnel
**Description:** This dimension focuses on targeted recruiting and accessible application platforms to ensure “Decent Work and Economic Growth” (<a href="#UN2015">UN, 2015</a>; W3C, 2024).

#### Proof Points
- Audits to ensure “Equal Pay for Work of Equal Value” to eliminate demographic  pay gaps (<a href="#UN2015">UN, 2015</a>).
- Strategic engagement to increase the representation of youth and other underrepresented groups in decision-making roles (<a href="#UN2015">UN, 2015</a>).

#### Technical & Equity Framework Alignment
- **W3C Technical Rule:** W3C AMM Personnel Metrics (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Paired Equity Framework:** UN SDG 8 (Decent Work and Economic Growth) (<a href="#UN2015">UN, 2015</a>) & U.S. Executive Order 14035 (DEIA in the Federal Workforce) (<a href="#eo14035">U.S. Exec. Order No. 14035, 2021</a>).
- AMM tracks accessible job platforms and recruitment workflows; DEIA and HRIA frameworks conduct pay equity audits and evaluate whether recruitment pipelines remove barriers for historically marginalized talent.

### 3.6 Procurement
**Description:** Organizational maturity in procurement involves consistent use of standardized language in contracts to ensure vendors meet equity and sustainability standards.

#### Proof Points
- Policies that prioritize “Partnerships for the Goals” (SDG 17) by selecting suppliers that adhere to sustainable and ethical practices (<a href="#UN2015">UN, 2015</a>).
- Alignment on key definitions that uphold and promote human rights as outlined in the UN Guiding Principles on Business and Human Rights (UNGPs) (OHCHR, 2011).
- Evaluation of third-party tools for privacy and security compliance.

#### Technical & Equity Framework Alignment
- **W3C Technical Rule:** W3C Web Sustainability Guidelines (WSG 1.0) (W3C WSG, 2025) & Voluntary Product Accessibility Template (VPAT) / Accessibility Conformance Report (ACR) Verification.
- **Paired Equity Framework:** UN SDG 17 (Partnerships for the Goals) (<a href="#UN2015">UN, 2015</a>) & UNGPs Supply Chain Human Rights Due Diligence (<a href="#ohchr2012">OHCHR, 2012</a>).
- WSG 1.0 and ACRs technically evaluate vendor code efficiency and compliance; UNGP assessments audit vendor labor practices, data privacy compliance, and supply chain environmental footprints.

### 3.7 Support
**Description:** Providing support for both internal employees and external users, ensuring that grievance mechanisms are accessible and inclusive (<a href="#W3CAMM">W3C AMM, 2025</a>).

#### Proof Points
- Mechanisms to report and detect trafficking or exploitation, supporting justice for all (<a href="#UN2015">UN, 2015</a>).
- Reporting and grievance processes that are effective and fully usable by the widest range of users possible, including children as relevant (<a href="#W3CAMM">W3C AMM, 2025</a>; General comment No. 25 (2021) on children’s rights in relation to the digital environment, 02 March 2021, CRC/C/GC/25) (<em>CITATION?</em>.
- Publicly transparent reporting on the organization’s environmental footprint and social impact (<a href="#UN2015">UN, 2015</a>).

#### Technical & Equity Framework Alignment
- **W3C Technical Rule:** W3C Web Performance Specifications (W3C, n.d.) & AMM Support Guidelines (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Paired Equity Framework:** UN Universal Declaration of Human Rights (Article 8: Right to Effective Remedy) (UN, 1948) & UN SDG 16 (Peace, Justice, and Strong Institutions) (<a href="#UN2015">UN, 2015</a>).
- Performance standards ensure support channels load on low-cost devices and poor networks; Human Rights frameworks verify that reporting mechanisms offer safe, non-retaliatory, and anonymous remedies for discrimination or exploitation.

## 4. Evaluation Process (How to Use)
The evaluation process for the Equity Maturity Model (EMM) is designed to be a collaborative and iterative journey that shifts an organization from a reactive posture to a proactive, “shift-left” approach to equity and sustainability. By following these steps, organizations can systematically integrate W3C guidelines (including accessibility, internationalization, privacy, security, and sustainable web practices) into their core operations.

### 4.1 Recommended Steps to Get Started
To effectively utilize the EMM, organizations should follow a structured evaluation cycle:
- **Form a Review Team:** Organizations should assemble a cross-functional team that includes executive leadership, management, and subject matter experts. This team is responsible for putting plans, actions, and governance in place to support operationalisation of the EMM. Team members must be given the appropriate authority and independence to review impartially, free from perceived conflicts of interest.
- **Gather Evidence (Proof Points):** The team must collect documentation and data that reflect current practices. This evidence is compared against the EMM dimensions to determine the actual (not aspirational) maturity level (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Validate and Assess:** Using the identified proof points and technical & equity frameworks, the team determines the maturity level (Inactive, Developing, Integrate, or Optimize) for each dimension. Maturity extends beyond internal operations to vendor procurement, third-party technology reliance, and overall supply-chain ethics. This assessment should explicitly account for systemic barriers as well as the environmental footprint of the organization’s digital practices (<a href="#UN2015">UN, 2015</a>).
- **Create a Roadmap for Improvement:** Based on the gaps identified, the organization should establish a roadmap toward greater maturity. This involves setting targets aligned with (but not necessarily limited to) the Sustainable Development Goals (<a href="#UN2015">UN, 2015</a>).
Reassess Regularly: Organizations should move away from “point-in-time” conformance testing and toward a continuous process of improvement and evaluation (<a href="#W3CAMM">W3C AMM, 2025</a>).

### 4.2 Customizing the Model
The EMM is designed to be flexible and can be customized to fit the specific needs of an organization or a particular subunit. Customization allows users to:
- **Tailor Proof Points:** Omit proof points that do not apply to the organization’s specific industry or digital environment (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Refine Language: **Adapt terms and practices to reflect the internal culture while maintaining alignment with the W3C framework (<a href="#W3CAMM">W3C AMM, 2025</a>).
- **Prioritize SDGs:** Focus on specific Sustainable Development Goals, such as “Gender Equality” or “Decent Work and Economic Growth,” that are most relevant to the organization’s mission (<a href="#UN2015">UN, 2015</a>).

### 4.3 Measuring Impact Over Time
The EMM measures the effectiveness of governance systems (<a href="#W3CAMM">W3C AMM, 2025</a>). Success is defined by the organization’s ability to minimize “intentional and unintentional harms” and ensure that digital products and services are essential for “inclusive digital environments.” By documenting organizational, cultural, and technical capabilities, the EMM provides a holistic picture of the organization’s long-term sustainability and equity (<a href="#W3CAMM">W3C AMM, 2025</a>).

## 5. Organizational Equity Maturity Spectrum

Long-term sustainability of equity initiatives requires tying organizational targets to transparent governance, leadership accountability, and sustained resource allocation. To operationalize the EMM, organizations can use this spectrum to determine their overall maturity stage across operational processes, governance, and evaluation practices. Each stage defines how deeply equity, web standards, and continuous data monitoring are embedded within the organization’s culture.

### 5.1 Stage 1: Inactive (Unaware / Overlooked)
- Little to no organizational awareness of equity, accessibility, or sustainability requirements; issues are unacknowledged or treated as non-essential.
- No formal testing, guidelines, or evaluations exist. Compliance is handled reactively only when external pressure or legal risk arises.
- Absence of governance systems or data collection regarding user outcomes and systemic barriers.

## 5.2 Stage 2: Developing (Beginning Awareness & Ad-Hoc Planning)
- Leadership acknowledges the need for equitable ICT practices and initiates initial discussions or siloed planning efforts.
- Teams begin applying W3C standards (e.g., WCAG, Web Sustainability Guidelines, Privacy principles) on a discretionary, project-by-project basis. Assessments are point-in-time audits conducted after product development.
- Early identification of equity-specific metrics, but execution remains ad-hoc without unified institutional oversight.

## 5.3 Stage 3: Integrating (Defined Plan & Systematic Evaluation)
- A formal organizational roadmap is established, backed by cross-functional leadership commitment and clear resource allocation.
- Multi-standard evaluations, combining W3C guidelines (accessibility, internationalization, privacy, security, sustainability, performance) with equity-specific impact assessments, are systematically integrated into project lifecycles.
- Standardized governance controls ensure consistent implementation across all business units and vendor procurements.

## 5.4 Stage 4: Optimizing (Embedded Culture & Data-Driven Adaptation)
- Equity, safety, and digital rights are fully embedded into the corporate DNA and everyday decision-making structures ("by design").
- “Shift-left” assessment workflows prevent harms early in the design phase. Evaluation is an ongoing, continuous operational process rather than a static compliance check.
- Organizations continuously collect, disaggregate, and analyze qualitative and quantitative feedback (e.g., community co-design feedback, audit data, performance metrics) to identify emerging disparities and proactively eliminate systemic barriers.

## 6. References
<ul>
  <li id="UN1948>United Nations. General Assembly. (1948). Universal Declaration of Human Rights (A/RES/217(III) A). <a href="https://www.un.org/sites/un2.un.org/files/2021/03/udhr.pdf" target="_blank" rel="noopener">https://www.un.org/sites/un2.un.org/files/2021/03/udhr.pdf</a></li>
  <li id="UN2006">United Nations. (2006). Convention on the Rights of Persons with Disabilities (Treaty Series, vol. 2515, p. 3). <a target="_blank" rel="noopener" href="https://www.ohchr.org/en/instruments-mechanisms/instruments/convention-rights-persons-disabilities">https://www.ohchr.org/en/instruments-mechanisms/instruments/convention-rights-persons-disabilities</a></li>
  <li id="UN1989">United Nations. (1989). Convention on the Rights of the Child (Treaty Series, vol. 1577, p. 3). <a target="_blank" rel="noopener" href="https://www.ohchr.org/en/instruments-mechanisms/instruments/convention-rights-child">https://www.ohchr.org/en/instruments-mechanisms/instruments/convention-rights-child</a></li>
  <li id="W3CAMM">World Wide Web Consortium. (2025). W3C Accessibility Maturity Model.<a target="_blank" rel="noopener" href="https://www.w3.org/TR/maturity-model/">https://www.w3.org/TR/maturity-model/</a></li>
  <li id="NACE">National Association of Colleges and Employers. (n.d.). Equity definition.<a target="_blank" rel="noopener" href="https://www.naceweb.org/about-us/equity-definition/">https://www.naceweb.org/about-us/equity-definition/</a></li>
  <li id="i18n">World Wide Web Consortium. (2024). Internationalization (I18n) activity.<a target="_blank" rel="noopener" href="https://www.w3.org/International/">https://www.w3.org/International/</a></li>
  <li id="ping">World Wide Web Consortium. (n.d.-a). W3C Privacy Interest Group (PING).<a target="_blank" rel="noopener" href="https://www.w3.org/2019/09/privacy-ig-charter.html">https://www.w3.org/2019/09/privacy-ig-charter.html</a></li>
  <li id="wsig">World Wide Web Consortium. (n.d.-b). W3C Web Security Interest Group.<a target="_blank" rel="noopener" href="https://www.w3.org/Security/wiki/IG">https://www.w3.org/Security/wiki/IG</a></li>
  <li id="wsg">World Wide Web Consortium. (2026). Web Sustainability Guidelines (WSG) <a target="_blank" rel="noopener" href="https://www.w3.org/TR/web-sustainability-guidelines/">https://www.w3.org/TR/web-sustainability-guidelines/</a></li>
  <li id="webperf">World Wide Web Consortium. (n.d.-c). Web Performance Working Group.<a target="_blank" rel="noopener" href="https://www.w3.org/groups/wg/webperf/">https://www.w3.org/groups/wg/webperf/</a></li>
  <li id="UN2015">United Nations. General Assembly. (2015). Transforming our world: The 2030 Agenda for Sustainable Development (A/RES/70/1).<a target="_blank" rel="noopener" href="https://sdgs.un.org/2030agenda">https://sdgs.un.org/2030agenda</a></li>
  <li id="ieee2022">Institute of Electrical and Electronics Engineers. (2022). IEEE standard for data privacy process (IEEE Std 7002-2022). IEEE. <a target="_blank" rel="noopener" href="https://standards.ieee.org/ieee/7002/6898/">https://standards.ieee.org/ieee/7002/6898/</a></li>
  <li id="iso2024">International Organization for Standardization, & International Electrotechnical Commission. (2024). Information technology — Security techniques — Privacy framework (ISO/IEC Standard No. 29100:2024). ISO.<a target="_blank" rel="noopener" href="https://www.iso.org/standard/85938.html">https://www.iso.org/standard/85938.html</a></li>
  <li id="wcag22">World Wide Web Consortium. (2023, October 5). Web content accessibility guidelines (WCAG) 2.2 (W3C Recommendation).<a target="_blank" rel="noopener" href="https://www.w3.org/TR/WCAG22/">https://www.w3.org/TR/WCAG22/</a></li>
  <li id="i18n_mission">World Wide Web Consortium. (n.d.). Internationalization | Our mission.<a target="_blank" rel="noopener" href="https://www.w3.org/mission/internationalization/">https://www.w3.org/mission/internationalization/</a></li>
  <li id="ping2025">World Wide Web Consortium. (2025, May 15). Privacy principles (W3C Group Note).<a target="_blank" rel="noopener" href="https://www.w3.org/TR/privacy-principles/">https://www.w3.org/TR/privacy-principles/</a></li>
  <li id="w3c_security">World Wide Web Consortium. (n.d.). Security activity. <a target="_blank" rel="noopener" href="https://www.w3.org/Security/">https://www.w3.org/Security/</a></li>
  <li id="w3c2026_webnn">Worldwide Web Consortium. (2026, August 13). Web neural network API (W3C Candidate Recommendation Draft).<a target="_blank" rel="noopener" href="https://www.w3.org/TR/webnn/">https://www.w3.org/TR/webnn/</a></li>
  <li id="djl2019">Dencik, L., Hintz, A., Redden, J., & Treré, E. (2019). Data justice: An international framework for policy and practice. Data Justice Lab, Cardiff University.<a target="_blank" rel="noopener" href="https://datajusticelab.org/data-justice-framework/">https://datajusticelab.org/data-justice-framework/</a></li>
  <li id="arXiv2022">Leslie, D., Burr, C., Aitken, M., Katell, M., Briggs, M., & Rincon, C. (2022). Human rights, democracy, and the rule of law assurance framework for AI systems: A proposal. arXiv.<a target="_blank" rel="noopener" href="https://doi.org/10.48550/arXiv.2202.02776">https://doi.org/10.48550/arXiv.2202.02776</a></li>
  <li id="berj2007">Lundy, L. (2007). ‘Voice’ is not enough: Conceptualising Article 12 of the United Nations Convention on the Rights of the Child. British Educational Research Journal, 33(6), 927–942.<a target="_blank" rel="noopener" href="https://doi.org/10.1080/01411920701657033">https://doi.org/10.1080/01411920701657033</a></li>
  <li id="ohchr2011">United Nations Office of the High Commissioner for Human Rights. (2011). Guiding principles on business and human rights: Implementing the United Nations “Protect, Respect and Remedy” framework (HR/PUB/11/04). United Nations. <a target="_blank" rel="noopener" href="https://www.ohchr.org/sites/default/files/documents/publications/guidingprinciplesbusinesshr_en.pdf">https://www.ohchr.org/sites/default/files/documents/publications/guidingprinciplesbusinesshr_en.pdf</a></li>
  <li id="eo14035">Exec. Order No. 14035, 3 C.F.R. 287 (2021). <a target="_blank" rel="noopener" href="https://www.federalregister.gov/documents/2021/06/30/2021-14127/diversity-equity-inclusion-and-accessibility-in-the-federal-workforce">https://www.federalregister.gov/documents/2021/06/30/2021-14127/diversity-equity-inclusion-and-accessibility-in-the-federal-workforce</a></li>
  <li id="ohchr2012">United Nations Office of the High Commissioner for Human Rights. (2012). The corporate responsibility to respect human rights: An interpretive guide (HR/PUB/12/02). United Nations. <a target="_blank" rel="noopener" href="https://www.ohchr.org/sites/default/files/Documents/Publications/HR.PUB.12.2_En.pdf">https://www.ohchr.org/sites/default/files/Documents/Publications/HR.PUB.12.2_En.pdf</a></li>
</ul>


