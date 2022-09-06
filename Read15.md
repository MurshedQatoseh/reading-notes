## What is OAuth? ##
**OAuth is an open-standard authorization convention or system that depicts how irrelevant servers and administrations can securely permit verified get to to their resources without really sharing the beginning, related, single logon credential. In verification speech, this is often known as secure, third-party, user-agent, assigned authorization**

### Give an example of what using OAuth would look like? ###
***The best example of OAuth is after you go to log onto web site and it offers one or more openings to log on utilizing another website’s/service’s logon.***

### How does OAuth work? What are the steps that it takes to authenticate the user? ###
1. The primary site interfaces to the moment site on sake of the client, utilizing OAuth, giving the user’s confirmed character.
2. The moment location produces a one-time token and a one-time mystery special to the exchange and parties included.
3. The primary location gives this token and mystery to the starting user’s client program.
4. The client’s program presents the ask token and mystery to their authorization supplier (which may or may not be the moment location).
5. On the off chance that not as of now confirmed to the authorization supplier, the client may be inquired to confirm. After verification, the client is inquired to endorse the authorization exchange to the moment site.

 ### What is OpenID? ###
***OpenID is an open standard and decentralized confirmation convention advanced by the non-profit OpenID Establishment.***


### What is the difference between authorization and authentication? ###
**Confirmation and authorization are two crucial data security forms that directors utilize to secure frameworks and data. Confirmation confirms the character of a client or benefit, and authorization decides their get to rights.**

### What is Authorization Code Flow? ###
***Exchanges an Authorization Code for a token.***

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)? ###
**Amid confirmation, versatile and local applications can utilize the Authorization Code Stream, but they require extra security. Moreover, single-page apps have uncommon challenges. To relieve these, OAuth 2.0 gives a adaptation of the Authorization Code Stream which makes utilize of a Confirmation Key for Code Trade (PKCE).**

### What is Implicit Flow with Form Post?###
***As an elective to the Authorization Code Stream, OAuth 2.0 gives the Verifiable Stream, which is aiming for Open Clients, or applications which are incapable to safely store Client Insider facts. Whereas this can be not considered a best hone for asking Get to Tokens, when utilized with Shape Post reaction mode, it does offer a streamlined workflow in the event that the application needs as it were an ID token to perform client verification.***

### What is Client Credentials Flow? ###
**With machine-to-machine (M2M) applications, such as CLIs, daemons, or administrations running on your back-end, the framework confirms and authorizes the app instead of a client. For this situation, normal confirmation plans like username + secret word or social logins do not make sense. Instep, M2M apps utilize the Client Qualifications Stream.**

### What is Device Authorization Flow? ###
**With input-constrained gadgets that interface to the web, instead of confirm the client straightforwardly, the gadget inquires the client to go to a interface on their computer or smartphone and authorize the gadget. This maintains a strategic distance from a destitute client experience for gadgets that don't have a simple way to enter content. To do this, gadget apps utilize the Gadget Authorization Stream. For utilize with mobile/native applications.**

### What is Resource Owner Password Flow? ### 
***Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.***

