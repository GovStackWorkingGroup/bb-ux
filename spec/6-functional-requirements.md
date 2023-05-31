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

## Patterns for the common workflows

### **List of available patterns**&#x20;

\[Content required]

### **Considerations for choosing different patterns**

\[Content required]

### &#x20;Start page

Use this pattern to help users check if they are ready to start a service.

<figure><img src=".gitbook/assets/Start page (1).png" alt=""><figcaption><p>A wireframe of a typical start page</p></figcaption></figure>

#### How it works

**Service name**

This helps people understand what your service does and whether they need to use it.

**Documents and any fees required**

A list of things most users need to know: for example, what your service is, what will happen, what users will get or how much it'll cost. To keep the content concise, do not include details about anything that would be obvious to users.

**A call-to-action**

There should be a clear call to action button to start the service, usually “Start now”. You should also include a link to “sign in” or “continue journey” if the user is able to continue an existing journey.

**Other ways to access the service**

You should provide ways for people who can’t access the service online to get support, for example, by phone or text relay. You may also include details for support channels.

#### **When to use this pattern**

At the start of a service which involves the user inputting information in order to get something. For example, at the start of an application form.

### Asking users for consent

Use these patterns to give user’s control over how you manage their data. These patterns align with the [GovStack Consent building block](http://localhost:5000/o/pxmRWOPoaU8fUAbbcrus/s/MhCVws4MKdm6FWXf006q/).

#### How it works

Consent covers all activities done for the same reason. If you use the data for more than one reason, get separate consent for each. For example, accessing data to check eligibility is separate to accessing data to make an application.

Use these patterns when you need to:

* To access a user’s data
* To store, manage or share a user’s data
* Allow users to manage the data you hold on them



<figure><img src=".gitbook/assets/Example consent flow (1).png" alt=""><figcaption><p>An example consent user journey</p></figcaption></figure>

The image above shows an example user journey where a user:

1. starts a service
2. gives consent to access their data to perform an eligibility check and proceeds
3. refuses consent to access data to make the application
4. Confirms they do not want to give consent
5. Continues an alternative journey

#### When not to use these patterns

If the data is required for government to perform a specific task or function set out in law, you do not need to ask for consent. For example, terms and conditions — these are required so you do not need to ask for consent.

#### Consent to access or manage data

<figure><img src=".gitbook/assets/Consent page (1).png" alt=""><figcaption><p>A wireframe of an example consent page</p></figcaption></figure>

**Why we ask to share this data**\
Explain what data you are requesting and the benefit to the user for sharing that data. For example, “Provide your location data so that we can tailor offers relevant to you”

**About the data**

Be clear about:

* What data you need
* Why you need it
* The benefit to the user
* How the data will be used
* What duration

**Confirm or reject**

This could be buttons or radio buttons but you should consider how the user can continue the transaction in the case they do not consent to share information.

If users reject the consent request, consider reiterating how this will effect the user journey and ask them to confirm the choice.

**How to manage or revoke access**

Give details for how to manage data if the user changes their mind.

#### Details for information

When asking users information during questions flow consider using progressive disclosure drop-downs or inline content to explain why you are asking for that information and how you will handle the data.

<figure><img src=".gitbook/assets/Details for information (1).png" alt=""><figcaption><p>A wireframe of an example progressive disclosure details pattern</p></figcaption></figure>

\
\
\
\
\


####
