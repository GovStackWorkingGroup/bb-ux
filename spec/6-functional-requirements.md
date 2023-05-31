# 6 Functional Requirements

{% hint style="success" %}
The functional requirements section lists the technical capabilities that this building block should have. These requirements should be sufficient to deliver all functionality that is listed in the Key Digital Functionalities section.

These functional requirements do not define specific APIs - they provide a list of information about functionality that must be implemented within the building block.

These requirements should be defined by subject-matter experts and don’t have to be highly technical in this section.

If there are multiple functional components of a building block, the functional requirements for each component may have its own section
{% endhint %}

## Frontend design standards and recommendations

### **1. Accessibility and Inclusion**

We want to build digital government services that are usable and equitable for all users, including those with disabilities and diverse backgrounds. The building blocks approach provides a foundation for creating accessible and inclusive services, but it's important to verify their implementation to ensure compliance with relevant accessibility standards and promote inclusivity.

#### Things you must do:

* Check that the implementation of the building blocks, as well as the overall digital government service, meets the Web Content Accessibility Guidelines (WCAG) standards for accessibility.
* Test the service using accessibility tools like screen readers to identify and fix any accessibility issues.
* Consider principles of inclusivity, such as Gender Equality and Social Inclusion (GESI) guidelines where applicable, and ensure that all interactive elements and components used in the service, including those based on the building blocks, are designed and tested to be inclusive, respectful, and representative of diverse user groups.

#### Considerations:

* Involve users with disabilities and users from diverse backgrounds in user testing and feedback gathering to identify any potential accessibility and inclusivity issues.
* Foster a culture of inclusivity within the team and encourage ongoing education and awareness on inclusivity and diversity best practices.
* Regularly review and update the implementation of the building blocks and the digital government service to ensure continued accessibility and inclusivity compliance.
* Stay informed about any updates or changes to accessibility standards, guidelines, and inclusivity best practices.
* Seek expert assistance or consultation on accessibility and inclusivity if needed.

#### Resources:

* [WCAG guidelines](https://www.w3.org/WAI/standards-guidelines/)
* [How to test for accessibility](https://www.gov.uk/service-manual/helping-people-to-use-your-service/testing-for-accessibility)&#x20;
* Inclusive design: [Universal barriers to access](https://uteschauberger.com/barrierstoaccess.html)
* [GESI guidelines](https://www.britishcouncil.org/sites/default/files/gender\_and\_social\_inclusion\_guide.pdf)

### **2. Iterative, user-centred design**

Iterative, user-centred design makes sure that digital government services are continuously improved to meet the needs of users effectively. By understanding the needs of the solution, with the building blocks as a starting point, conducting user testing and feedback gathering, and using iterative design processes, you can create services that are user-centric and continuously refined for optimal user experience.

#### Things You Must Do:

* Start by thoroughly understanding the needs and requirements of the solution, including user needs, expectations, and pain points.
* Begin with the patterns provided with the building blocks, unless research clearly indicates a need to diverge from them.
* Conduct user testing with real people and gather feedback at various stages of the design process to identify usability issues, user preferences, and opportunities for improvement.
* Use user feedback to inform iterative design and continuously improve the digital government service, making necessary adjustments to meet the evolving needs of users.

#### Considerations:

* Regularly review and update the design of the digital government service based on user feedback, changing needs, and evolving requirements.
* Collaborate closely with users, stakeholders, and other [team members with diverse multidisciplinary skills](https://app.gitbook.com/o/pxmRWOPoaU8fUAbbcrus/s/4D3oEcPGpYoKnwkQmCzJ/govstack-implementation-playbook/sample-digital-team-composition), throughout the iterative design process to ensure alignment and effective communication.
* Seek input and feedback from diverse user groups, including users with disabilities, to ensure that the digital government service is inclusive and accessible to all.
* Continuously monitor and evaluate the performance and usability of the service, and iterate the design accordingly to drive continuous improvement and optimise user experience.
* Share research findings and product progress with team members, senior members or strategic leaders, and even the general public whenever practical.&#x20;

#### Resources:

* Understanding user needs
* Overview of the design process
* GovStack design patterns
* How to do user research
* Pattern for how to collect feedback

### **3. Consistency**

Consistency in design elements, language, and terminology is important for creating a cohesive and user-friendly digital government service that meets the needs of its users, while also aligning with established design systems, style guides, and accessibility standards.

#### Things You Must Do:

* Use patterns provided with the building blocks, unless research clearly indicates a need to diverge from them.

#### Considerations:

* Use a consistent style guide, if your organisation has one, to ensure consistency in visual elements, typography, colour schemes, and other design elements.
* Use consistent language and terminology throughout the design to ensure clarity and understanding for users.
* Use simple and clear language, following the principles of the UK government's Content Design guidance (https://www.gov.uk/guidance/content-design), to ensure that content is accessible and easy to understand for all users.

#### Resources:

* Example implementation design patterns
* Choosing frontend frameworks
* [Using simple and clear language](https://www.gov.uk/guidance/content-design)

**4. Technology choices**

Technology choices impact the user experience, security, privacy, and performance of the digital government service. Informed technology choices make sure the service is accessible, usable, and efficient, while aligning with the principles of using building blocks for consistency and scalability.

Considerations:

* Understand your users and their needs. Develop knowledge of your users and what that means for your technology project or programme.
* Make sure your technology, infrastructure and systems are accessible and inclusive for all users.
* Choose proportionate security to control and monitor your technology programme. Security should protect your information technology and digital services, and enable users to access the data they need for their work.
* Make sure citizens’ rights are protected by integrating privacy as an essential part of your system.
* Optimise load times and page performance
* Account for connectivity issues in different regions, considering the deployment options provided by the building blocks.

Resources:

* [GOV.UK Technology Code of Practice](https://www.gov.uk/guidance/the-technology-code-of-practice#define-user-needs)

### **5. Interoperability**

#### Considerations:

* Design the service to work well with other government services, systems, and platforms, using standard data exchange formats and APIs as per the building blocks' recommendations.
* Consider potential integration points and interoperability requirements early in the design process, involving relevant stakeholders, including the building blocks development team.
* Test the service, verifying its compatibility with different devices, browsers, and assistive technologies.
* Follow established standards and guidelines for multi-modal design, ensuring consistency and usability across different interaction modes.
* Consider using internationalisation and localization best practices to ensure your interfaces can be easily adapted to different languages and cultural contexts.
* Consider user expectations and preferences for different interaction modes, ensuring inclusivity and accessibility for all users.
* Account for potential limitations and constraints of different platforms, systems, and devices, while maintaining interoperability and multi-modality.
* Collaborate with relevant government agencies and stakeholders to align with broader interoperability initiatives and best practices recommended by the building blocks

#### Resources:

* [designing for a global audience.](https://www.nngroup.com/articles/crosscultural-design/)

\
\
\
\
\
\
\


####
