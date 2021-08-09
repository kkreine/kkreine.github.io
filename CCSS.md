---
title: "about kori"
layout: default
filename: about-me.md
---

## Corporate Cybersecurity Strategy COSC-A243
# Loyola University New Orleans
# Module 4 Assignment

1. Define Authentication and describe how it works.

	Authentication is what we think of as a login. It attributes a particular interaction with an information asset to an identified party or person. Essentially, it is the mechanism by which the system determines access to some system, like a password for an email. It works by requiring a challenge or knowledge of secret information in order to access some system or information asset. This challenge or information can be something you know (password or pin), something you have (key or token), or something you are (personal trait).

2. Define Authorization and describe how it works.

	Authorization is the process by which the system allows authenticated users to perform specific operations and is the process by which these permissions are enforced. It works as a simple yes or no question (“may I have access?”) that maps subject (person, organization, programs) to object (information assets) to action (read, write, execute). Authorization grants the permission for the authenticated subject to perform a certain action on a specific object. Most importantly, it utilizes user access controls to ensure authorized users can access information and unauthorized cannot.

3. Define Auditing and describe how it works.

	Auditing is a process to evaluate the effectiveness and sufficiency of the subject being audited against the business objectives. The process identifies problems, weaknesses, and security vulnerabilities of the audited entity. It works as a review of the organization. It is beneficial because it ensures the organization is following company policies & laws, decreases security violations, makes the organization for accountable, among other benefits. Auditing can take two forms: forensic and operational.

Part 4A. Identify a cybersecurity incident in this corporate 'social network' could cause damage to the business.  Describe what type of cybersecurity incident it is and what technical aspects of the 'social network' are involved.  Then describe how this could impair business processes, harm internal relationships, or cause damage to contractual or regulatory obligations.  I will evaluate this primarily on how effectively you assess business damage for a cybersecurity incident.

Scenario: When the social network was set up, they did not set up secure authentication, so it is easy for anyone to log on. A competing company was able to log in to the network and acquired trade secrets—specifically problems with their products that were not made public—and leaked them online. This damages the company’s reputation, resulting in losses of sales and/or clients. Investors may pull out because they no longer trust the company. Further, the employee who posted the information is ostracized, employee relations decline, and there is reduced productivity. Perhaps most importantly, whatever problem there is with the product could result in a breach of contract or regulation violations accruing high legal counsel costs.

Part 4B. Define a corporate policy governing the structure or the use of the 'social network' that addresses the risk of your cybersecurity incident from part 4A. I will evaluate this mainly from the criteria for policy given in Santos chapter 1.

Policy must be endorsed, relevant, realistic, attainable, adaptable, enforceable, inclusive. For this example, let me assume that the non-secure authentication is that passwords were initialized to the employee’s employee number that is listed on their employee directory.

Passwords are important to keep private and difficult to guess in order to keep accounts and the network safe. To avoid password theft and unauthorized access of the company social network, we instruct employees to: 

- Make passwords unique with no personally identifiable information (e.g., birthdays) and changed every 3 months.
- Never post trade secrets or private company information on the social network.


Part 4C. Describe a corporate standard or procedure for the 'social network' that would support policy in section 4B. This could be a standard for configuring the 'social network' to prevent such incidents as from 4A, or might have steps for investigating an apparent breach of the policy in 4B, or other things.  Describe clearly how this standard or procedure will address the risk you describe in part 4A.  This will be evaluated on how specific and realistic it is, and whether it seems that it would be effective.

When establishing the network, the employees must be required to enter their personal information into their profile (birthday, employee number, full name) and that should be compared against their proposed password. If the password contains personally identifiable information, the user should be given an error and not be allowed to use that password.

The company should have an activity log for the social network and any systems that provide access to an information asset. Similar to how emails operate, if a user tries to access the social network from a device not recognized or registered, additional verification should be required. This would have avoided the incident, since the attacker in this case was not accessing the network from a company registered machine. Activity logs would also assist in catching unauthorized users who do use authorized devices (why is someone accessing the computer at 1 am?) and responding to it promptly.