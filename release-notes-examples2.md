# Swimlane Release Notes Examples

## Release Notes for a Major Release

### **New Features**

**Parallel Actions:**

Our latest release brings a game-changing feature to orchestrators—Parallel Actions, equipped with a user-friendly visual indicator. This empowers orchestrators to       seamlessly execute parallel branches, ensuring each task concludes before moving on to the next downstream action. With this innovative addition, efficiency is taken to new heights, saving valuable time as multiple tasks can now be effortlessly handled simultaneously.

**Record Action UI:**

We are introducing four new user interfaces tailored for the following Record Actions: Create Record, Update/Create Record, Search Records, and Delete Record native actions. These enhancements redefine the user experience by providing intuitive interfaces for creating and maintaining data within Turbine application records. Designed to be both user-friendly and straightforward, the new Record Actions UI ensures ease of use while handling various data functions.

**Rename Transformation Blocks:**

You can now rename transformation blocks in the playbook builder. This feature comes with two key functions. During the initial block creation and before applying changes, users have the ability to edit the block name, automatically updating the block name. Additionally, for users who have already applied changes to the playbook and wish to rename a block, this feature allows them to edit the name while preserving the original block name. This enhancement is designed to safeguard users from unintentionally disrupting current downstream actions, providing a secure experience when modifying block names within the playbook

**New Basic Transformations:**

We are also introducing new advanced transformations accompanied by example syntax and code snippets. To make it even more accessible, we've presented them in a user-friendly table with a revamped grouping format. Take a moment to explore these powerful additions and their practical application by checking out the provided examples. Elevate your experience with the enhanced transformations, designed to bring clarity and ease of implementation. For more information, see the Advanced Transformation Options topic in the Turbine User Guide.

**Audit Logs:**

You can now access audit logs using a dedicated API specifically designed for this purpose. Experience transparency and control like never before with our upgraded audit logging system. See the Audit Logging topic in the Turbine User Guide for more information.

**Tenant Management:**

When a user provisions a new account, the default number of tenants is 3. In the past the default was 5.



## Release Notes for a Minor Release

_December 22, 2023_

We have confirmed correct workflow for authentication failures for LDAP users. This includes making “email” a unique identifier and not allowing users to login with a username from previous releases. This is the same for LDAP user sync as well. We recommend that users who currently use “uid” in the LDAP user settings change that to “mail” to improve the authentication workflow.
