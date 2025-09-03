Title: Enable user to reset password via email

**As a** [As a registered user]  
**I need** [I need a way to reset my password via email]  
**So that** [So that I can regain access if I forget my credentials]  
      
### Details and Assumptions

Email service is already configured
Frontend form design is available in Figma
Backend must validate token expiration      

### Acceptance Criteria     
gherkin 
Given [Given a user has forgotten their password]

When [When they request a password reset]

Then [Then they receive an email with a reset link]
