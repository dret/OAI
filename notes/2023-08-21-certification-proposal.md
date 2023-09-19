# Proposal for OAI Certification

## Erik Wilde, erik.wilde@dret.net, August 21, 2023

OAI has a strong brand but that one is eclipsed by far by the OpenAPI brand. However, even the OpenAPI brand is not as visible as it could be and probably should be, because it often is treated more as a side issue and not so much as one of the central pillars of how API management happens today. This proposal aims at strengthening both brands with the goal of an overall improved recognition and visibility, which will translate into increased participation, increased interest in membership, and a better way to work on specifications because of more community involvement.


### OAI Certification: Introduction

OAI Certification has a set of certification programs. All of them will be managed in the same way and will be aligned in terms of processes for how to get accredited, how to acquire certificates, and how certificates are designed and issued.

Possible providers for this kind of service are Accredible and Credly and similar providers. There are a variety of providers for this kind of service, and at this point the only important aspect is that OAI does not need to run their own infrastructure. However, of course there need to be processes around how these services are being used and how data and workflows underlying the certification process are managed.


### OAI Certification: Certification Programs and Levels

OAI may decide to extend the certification practice, but even at the start there already are two programs of certificates that can be envisioned. In order for this to be clearly communicated, it would be necessary to make sure that OAI certificates are always presented in a way that present three levels:

- This is a certificate issued by OAI.
- This is an OAI certificate in a certain program.
- Optional: This certificate represents a certain level in an OAI certification program.

As a start, there are two promising candidates for certification programs:

- One program is for certifying implementations in terms of their OpenAPI compliance. Whether this program may have different levels or not is not yet clear.
- One program is for OpenAPI proficiency for practitioners. More about possible levels further down, but this program likely would have levels such as "API Foundations", "API developer", "API product manager", and "API business specialist".

All programs and levels should be clearly described on the OAI Web site. More about how they are defined later on.


### OAI Certification: Accreditation

This is different for different programs. For the OpenAPI proficiency program, accreditation is based on a syllabus and on other course requirements. Without this being a final proposal, this would be a possible approach:

- For "OpenAPI Proficiency: API Foundations", the goal is basically OpenAPI literacy, i.e. the ability to understand OpenAPI (without every single detail). The syllabus would list OpenAPI features that would need to be discussed. The syllabus might also require some minimal context around APIs, such as understanding API styles, private/partner/public scenarios, and the API lifecycle.

- For "OpenAPI Proficiency: API Developer", the syllabus may include "API Foundations", adds more details/features of the OpenAPI specification, and may also add requirements for hands-on training, for example at the minimum two UI tools (something like Postman or Stoplight) and two developer tools (something like Spectral and Prism). The syllabus would make it clear that this is not intended to be a product training, but that some hands-on experience with products helps to better ease into using OpenAPI as a developer.

How accreditation works is up for discussion. One way to go would be to require submission of a course outline and the teaching materials and also require access to the course being taught. 

Because accreditation will take effort there may be a nominal fee. The fee should not be much more than the effort required, but if going through the course materials and attending the course takes two days, then the accreditation fee should reflect that effort.

Accreditation should have an expiration date, accredited training providers are allowed to claim their training as issuing "OpenAPI Proficiency Certificates", and OAI keeps track of accredited training providers. Renewing the accreditation should be easy but still be required to make sure that the list of accredited training providers is carefully managed.


### OAI Certification: Issuing Certificates

It's necessary to strike a balance between reasonable effort for issuing certificates and making sure that there is some quality control in place.

For the "OpenAPI Proficiency" program, the "API Foundations" level could be a simple online test. It would be difficult to make sure that the test wouldn't be leaked online relatively quickly, but on the other hand the foundations level could be considered a beginners level.

For levels above foundations it would still be necessary to make sure that issuing certificates can be done online. It may require a system similar to what online courses at universities are doing: A combination of an honour system with a platform that at least makes it a little harder to cheat.

In terms of economics testing for certificates could be treated as not being charged for, because the value is not in the testing but in the certificates. This would mean that failing students are not being charged for, which depending on success rates may or may not be a problem.


### OAI Certification: Certification Platform

As mentioned above, there are existing services such as Accredible and Credly (and others) that provide platforms for certification. Possible features of such a platform we might want to look for are:

- Bulk upload of student data (all successful students of a training).
- Bulk notification email to all students.
- Ability to separate and manage several programs.
- PDF version of the certificate.
- Social features for easy sharing of the certificate via social media.
- Verification feature so that others (such as potential employers) can verify the certificate.

This mostly all looks at certification for trainings. It may also fit the needs of the implementation certification program mentioned above, but that remains to be seen once more details of that initiative become available.

Using a commercial service and processing certification reports will take some effort. For this reason, a nominal fee should be assessed to pay for these efforts. It may be somewhere around $20 per certificate.

It is not quite clear how this would work in terms of accounting. The fee would go to OAI which means that OAI would need to invoice everybody who is issuing certificates. This may or may not be realistic, but maybe that's something where the Linux foundation has infrastructure that could help.
