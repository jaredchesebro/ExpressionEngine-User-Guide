<!--
    This source file is part of the open source project
    ExpressionEngine User Guide (https://github.com/ExpressionEngine/ExpressionEngine-User-Guide)

    @link      https://expressionengine.com/
    @copyright Copyright (c) 2003-2020, Packet Tide, LLC (https://www.packettide.com)
    @license   https://expressionengine.com/license Licensed under Apache License, Version 2.0
-->

# Member Manager

**Control Panel Location: `Members`**

This page is used both to search and to browse through active members within your ExpressionEngine installation. Also, you can filter the members by member group and search members.

This page also allows you to do the following:

[TOC=2-3]

![Member Manager Control Panel Page](_images/cp-members.png)

## Member Groups

**Control Panel Location: `Members > Member Groups`**

The _Member Groups_ area of the Control Panel permits you to manage your Member Groups. The member groups can be sorted by ID, Group Title, and Status.

Each member of your site must be a member of one of your Member Groups. These groups allow you to restrict and control what a given member is allowed to do, and which pages they are allowed to access. Each Member Group has over 50 different privileges that can be allowed or denied, giving you precise control over what each of your members can do.

### Create/Edit All Member Groups

**Control Panel Location: `Members > Member Groups > Create/Edit`**

This sections allows you to set the various permissions and settings for the selected Member Group

## Custom Member Fields

**Control Panel Location: `Members > Member Fields`**

The _Member Fields_ feature permits you to add fields to the member registration form and/or member profile and My Account areas.

### Create/Edit

**Control Panel Location: `Members > Member Fields > New/Edit`**

This section allows you to create or edit Member Fields.

The following fields are available:

- **Type** -- You may choose what type of field this is. There are three choices: 1. **Text Input**: This is a single input line for text. It is the type of field you might use for a title, name, or other short information. 2. **Textarea**: This is a standard text entry box with multiple lines. This is what you would use for larger amount of text. 3. **Drop-down List**: This creates a standard HTML `<select>` drop-down list. You will need to define contents of the list in the provided form.

- **Name** -- This is the descriptive name for the field. It will appear as the field title. This is a required field and it may contain spaces or punctuation.
- **Short name** -- This is the internal or 'short name' for the field. This is a required field and must be a single word with no spaces or punctuation. The short name is typically used as the variable name in your member profile and registration templates. You may optionally add a description of the field, which can be useful if you need to provide instructions for the field's use.

NOTE: **Note:** The fields are typically added automatically by the system so you do not need to edit the templates.

- **Require field?** -- You may optionally add a description of the field, which can be useful if you need to provide instructions for the field’s use.
- **Exclude from Anonymization Actions?** -- When enabled, the contents of the field will **not** be removed it the user requests to be 'forgotten'. Otherwise the custom field data will be deleted if the user is anonymized.
- **Show in Registration** -- When enabled, the field will be available in the public member registration form.
- **Show in Profile** -- When enabled, the field will be available within the Member Profile areas (both the public one and the My Account page in the Control Panel).

## Register a New Member

**Control Panel Location: `Members > Create`**

The New Member Registration section of the Control Panel allows you to manually create a new membership account.

This section has the following options:

- **Member Group** -- The member group to assign the user to.
- **Username** -- The unique username for the user. This is a required field.
- **Email** -- The email address for the current user.
- **Password** -- Change the user's password.

## Ban Settings

**Control Panel Location: `Members sidebar > Ban Settings`**

The User Banning section of the Control Panel allows you to ban users by IP address, email, or name.

The ban section has the following options:

- **IP addresses** -- Specify IP addresses to ban from site registration and login. Use wildcards to ban blocks of IP addresses. For example, `123.321.*`. Each IP address should be placed on a separate line. You also set what happens when a user with a banned IP address tries to access the site: - Restrict the user to viewing the site only. They will not be able to submit comments or do anything else except passively view the content. - Show the user a specific message. - Redirect the user to another specified site.

- **Email addresses** -- Specify email addresses to ban from site registration and login. Use wildcards for partial email addresses. For example, `*@spammydomain.com`. Each address should be placed on a separate line.
- **Restricted usernames** -- Specify usernames that cannot be used for member accounts, which can be handy for reserving certain usernames for your own use.
- **Restricted screen names** -- Specify screen names that cannot be used for member accounts, which can be handy for reserving certain screen names for your own use.
- **When a banned user attempts access** -- You can prevent access completely by forwarding them to another website, or show them an unavailable message, or allow them to access the website in view only mode.
