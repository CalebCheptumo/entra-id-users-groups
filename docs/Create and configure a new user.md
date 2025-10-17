### Lab 01 – Task 1: Create and configure user accounts (Portal)

#### Overview

Create a new internal user and invite an external guest. Screenshots show the exact portal blades and fields.

---

### Task 1a — Create a new internal user

1. Sign in to the Azure portal.
   ![Azure portal home](../screenshots/Create%20and%20configure%20user%20accounts/azure%20portal.png)

2. Open Microsoft Entra ID and review the tenant Overview.
   ![Microsoft Entra ID overview](../screenshots/Create%20and%20configure%20user%20accounts/Entra%20ID%20overview.png)

3. Review Manage tenants.
   ![Manage tenants](../screenshots/Create%20and%20configure%20user%20accounts/manage%20tenants.png)

4. Go to Users to see existing accounts.
   ![Users — overview](../screenshots/Create%20and%20configure%20user%20accounts/users%20overview.png)

6. Select New user → Create new user, then complete Basics:

- User principal name: `az104-user1`
- Display name: `az104-user1`
- Auto-generate password: checked
- Account enabled: checked  
  ![Create user — Basics](../screenshots/Create%20and%20configure%20user%20accounts/create%20new%20user.png)

7. Open the Properties tab and enter data:

- First name: Amani, Last name: Njoroge, User type: Member
- Job title: IT Lab Administrator, Company: LabWorks KE, Department: IT
- Employee ID: KE-IT-00124, Employee type: Full-time, Hire date: 2024-08-15
- Address: 12 Riverside Drive, Nairobi, Nairobi County, 00100
- Country/Region: Kenya, Usage location: Kenya  
  ![Create user — Properties](../screenshots/Create%20and%20configure%20user%20accounts/create%20new%20user%20info.png)

8. Review + create, then Create.
   ![Create user — Review + create](../screenshots/Create%20and%20configure%20user%20accounts/create%20new%20user%20review.png)

9. Verify the new user appears in the list.
   ![Users — list (after user created)](../screenshots/Create%20and%20configure%20user%20accounts/az104-user1%20added.png)

---

### Task 1b — Invite an external (guest) user

1. In Users, select New user → Invite external user. Fill in:

- Email: guest’s email (`kibusia@calebcheptumo.com`)
- Display name: guest’s name (Caleb)
- Send invite message: checked; Message: “Welcome to Azure and our group project”
- (Optional) Properties: Job title IT Lab Administrator, Department IT, Usage location Kenya  
  ![Invite external user — form](../screenshots/Create%20and%20configure%20user%20accounts/invite%20external%20user.png)

2. Review + invite, then Invite.
   ![Invite external user — Review + invite](../screenshots/Create%20and%20configure%20user%20accounts/invite%20external%20user%20review.png)


3. Validate the guest receives the email invitation.
   ![Invite external user — email received](../screenshots/Create%20and%20configure%20user%20accounts/email%20invite.png)

4. Return to Users and verify both the new internal user and the invited guest are listed.
   ![Users — list (after user + guest)](../screenshots/Create%20and%20configure%20user%20accounts/users.png)

---

