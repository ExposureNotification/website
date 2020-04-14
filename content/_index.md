---
title: "Data Rights for Digital Contact Tracing and Alerting"
date: 2020-04-13T05:31:18Z
draft: false

menu: ["main", "footer"]

---

Individual Data Rights for Digital Contact Tracing and Alerting (DCTA) are best practices for how consumer DCTAs should respect and handle consumer data. The Rights were developed in collaboration with the privacy and security community, government agencies, technology community, and public health professionals, including epidemiologists. 

## WHY ARE THE RIGHTS NECESSARY?

Epidemiologists identify DCTA as a tool that can help get people treated earlier, and reopen society. For digital contact tracing to be effective, it must have high adoption. However, large scale centralized digital contact tracing can be used for unwanted surveillance. The solution to these problems is requiring that developers build apps on a foundation of privacy-preservation and interoperability. The Rights are necessary to achieve this end. 

## WHAT IS THE OBJECTIVE?

The Rights should be part of the standard toolkit for developing a DCTA app. 

## WHO IS THE AUDIENCE?

Open source communities, developers and private organizations seem to be leading the charge on creating DCTA apps. 

## WHAT HAPPENS NEXT? 

Developers: adopt the Rights and go build amazing apps that can help get us out of this pandemic! 

Use them to guide your user stories and UX. The Rights have been reviewed and agreed upon by many organizations. However, the Rights are a live document. They will likely evolve to address new approaches and standards. Developers are at the frontlines and will need to help contribute to make sure that the Rights remain the standard. 

## WHAT IS CONTACT TRACING?

Contact tracing is an epidemiological process to help model the spread of an epidemic. It has been used effectively to eradicate smallpox and in the fight against Ebola. It is currently being used as one of the better tools in the fight against COVID-19. 

DCTA takes parts of the epidemiological process and applies it to a consumer facing app. Instead of using this process for modeling and other epidemiological uses, the data and processes alert a consumer of a possible infection as early as possible so they can seek healthcare.

## GENERAL DCTA DATA USE

DCTA can be effective without a consumer having to divulge any personal information to anyone. Data processed within DCTA infrastructure may only reveal the following types of information to the following types of individuals:

  * Plausibly exposed individuals that they may have been exposed
  * Health officials, of high level trends in exposure (not individual level)
  * Verifying to authorities that an individual is healthy or sick, with the explicit consent of the individual at each verification.

Private-sector contact tracing apps should be open source and/or available for audit from an independent third party.

When developing a DCTA app, developers should identify one or more well-defined problems that will be mitigated, solved, or improved.

## INDIVIDUAL DATA RIGHTS FOR DIGITAL CONTACT TRACING

<div class="rights">

  1. Data collection should be limited to achieve a defined purpose and should only collect the minimum data necessary. 
  2. All information disclosed by consumers through a DCTA app should be completely opt-in, with clear informed consent both as to the nature of what they're disclosing, how it is used, the likely impacts of disclosure and use, and any choices the consumers may have. Any new use requires fresh consent. Consumers can withdraw their consent at any time.
  3. When consumers choose to altruistically share their health information, that information should remain completely anonymous: no information should be required other than that which is essential, based on epidemiological standards, for alerting others to potential exposure. 
  4. Information such as location history, symptom reports, demographic information, or similar shared with public health officials or researchers must never be linked back to or used to re-identify individuals, even by entities legally allowed to perform such linkage. 
  5. Data may be aggregated so that it may not allow for the identification of individuals. Aggregate data may be maintained for public research purposes. Precautions should be taken to ensure that shared aggregate data may not be re-identified downstream.  
  6. Application developers should have a very clear and reasonable data retention policy based on epidemiological standards, and must not retain any data for longer than required to achieve the app's objective.
  7. Aggregate data should be processed with privacy-protecting techniques such as differential privacy. The methodologies and techniques should be available for public review. 
  8. Data should be secured on the consumer's device according to industry best practices.
  9. An individual has ownership over the data collected and stored on their mobile device. 
  10. Data collected-by or derived-from contact tracing apps should not be monetized, shared, or used for any other non-public-health purpose. This includes third party analytics, ad tracking, and other common third party data collectors. 
  11. Contact tracing apps shall be developed in collaboration with the privacy and security community, human rights and civil liberties organizations, government agencies, technology community, and public health professionals, including epidemiologists.
  12. All contact tracing apps must be in compliance with local data protection laws and regulations.
  13. Contact tracing apps should use an openly published protocol to ensure that their solution is verifiable and interoperable. For example, [the TCN Protocol][4], and [Apple/Google COVID-19 contact tracing technology][5]. 
</div>

 [4]: https://github.com/TCNCoalition/TCN

 [5]: https://www.apple.com/newsroom/2020/04/apple-and-google-partner-on-covid-19-contact-tracing-technology/


## Other notable privacy principles:

  * [https://www.ccc.de/en/updates/2020/contact-tracing-requirements][10]
  * [https://law.mit.edu/pub/covid19contacttracingprivacyprinciples][11]

   [10]: https://www.ccc.de/en/updates/2020/contact-tracing-requirements
   [11]: https://law.mit.edu/pub/covid19contacttracingprivacyprinciples
