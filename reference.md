# Reference
## Actions V1
<details><summary><code>client.actionsV1.<a href="/src/api/resources/actionsV1/client/Client.ts">list</a>({ ...params }) -> IncidentIO.ActionsListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all actions for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.actionsV1.list({
    incident_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    is_follow_up: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.ActionsV1ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ActionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.actionsV1.<a href="/src/api/resources/actionsV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.ActionsShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident action.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.actionsV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.ActionsV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ActionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Custom Field Options V1
<details><summary><code>client.customFieldOptionsV1.<a href="/src/api/resources/customFieldOptionsV1/client/Client.ts">list</a>({ ...params }) -> IncidentIO.CustomFieldOptionsListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show custom field options for a custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldOptionsV1.list({
    page_size: 25,
    after: "01G0J1EXE7AXZ2C93K61WBPYEH",
    custom_field_id: "01FCNDV6P870EA6S7TK1DSYD5H"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldOptionsV1ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldOptionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldOptionsV1.<a href="/src/api/resources/customFieldOptionsV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.CustomFieldOptionsCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a custom field option. If the sort key is not supplied, it'll default to 1000, so the option appears near the end of the list.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldOptionsV1.create({
    custom_field_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    sort_key: 10,
    value: "Product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldOptionsCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldOptionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldOptionsV1.<a href="/src/api/resources/customFieldOptionsV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.CustomFieldOptionsShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single custom field option
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldOptionsV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldOptionsV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldOptionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldOptionsV1.<a href="/src/api/resources/customFieldOptionsV1/client/Client.ts">update</a>({ ...params }) -> IncidentIO.CustomFieldOptionsUpdateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update a custom field option
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldOptionsV1.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    sort_key: 10,
    value: "Product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldOptionsUpdatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldOptionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldOptionsV1.<a href="/src/api/resources/customFieldOptionsV1/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a custom field option
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldOptionsV1.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldOptionsV1DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldOptionsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Custom Fields V1
<details><summary><code>client.customFieldsV1.<a href="/src/api/resources/customFieldsV1/client/Client.ts">list</a>() -> IncidentIO.CustomFieldsListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all custom fields for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV1.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CustomFieldsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV1.<a href="/src/api/resources/customFieldsV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.CustomFieldsCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV1.create({
    description: "Which team is impacted by this issue",
    field_type: "single_select",
    name: "Affected Team",
    required: "never",
    required_v2: "never",
    show_before_closure: true,
    show_before_creation: true,
    show_before_update: true,
    show_in_announcement_post: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV1.<a href="/src/api/resources/customFieldsV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.CustomFieldsShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single custom field.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV1.<a href="/src/api/resources/customFieldsV1/client/Client.ts">update</a>({ ...params }) -> IncidentIO.CustomFieldsUpdateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update the details of a custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV1.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    description: "Which team is impacted by this issue",
    name: "Affected Team",
    required: "never",
    required_v2: "never",
    show_before_closure: true,
    show_before_creation: true,
    show_before_update: true,
    show_in_announcement_post: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsUpdatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV1.<a href="/src/api/resources/customFieldsV1/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV1.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsV1DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Utilities V1
<details><summary><code>client.utilitiesV1.<a href="/src/api/resources/utilitiesV1/client/Client.ts">identity</a>() -> IncidentIO.UtilitiesIdentityResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Test if your API key is valid, and which roles it has.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.utilitiesV1.identity();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `UtilitiesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Attachments V1
<details><summary><code>client.incidentAttachmentsV1.<a href="/src/api/resources/incidentAttachmentsV1/client/Client.ts">list</a>({ ...params }) -> IncidentIO.IncidentAttachmentsListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident attachments for a given external resource or incident. You must provide either a specific incident ID or a specific external resource type and external ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentAttachmentsV1.list({
    incident_id: "01G0J1EXE7AXZ2C93K61WBPYEH",
    external_id: "123"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentAttachmentsV1ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentAttachmentsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentAttachmentsV1.<a href="/src/api/resources/incidentAttachmentsV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentAttachmentsCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Attaches an external resource to an incident
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentAttachmentsV1.create({
    incident_id: "01FDAG4SAP5TYPT98WGR2N7W91",
    resource: {
        external_id: "123",
        resource_type: "pager_duty_incident"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentAttachmentsCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentAttachmentsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentAttachmentsV1.<a href="/src/api/resources/incidentAttachmentsV1/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Unattaches an external resource from an incident
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentAttachmentsV1.delete({
    id: "01FCNDV6P870EA6S7TK1DSYD5H"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentAttachmentsV1DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentAttachmentsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Memberships V1
<details><summary><code>client.incidentMembershipsV1.<a href="/src/api/resources/incidentMembershipsV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentMembershipsCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Makes a user a member of a private incident
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentMembershipsV1.create({
    incident_id: "01ET65M7ZADYFCKD4K1AE2QNMC",
    user_id: "01FCQSP07Z74QMMYPDDGQB9FTG"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentMembershipsCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentMembershipsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentMembershipsV1.<a href="/src/api/resources/incidentMembershipsV1/client/Client.ts">revoke</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Revoke a user's membership of a private incident
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentMembershipsV1.revoke({
    incident_id: "01FCNDV6P870EA6S7TK1DSYD5H",
    user_id: "01FCQSP07Z74QMMYPDDGQB9FTG"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentMembershipsRevokePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentMembershipsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Relationships V1
<details><summary><code>client.incidentRelationshipsV1.<a href="/src/api/resources/incidentRelationshipsV1/client/Client.ts">list</a>({ ...params }) -> IncidentIO.IncidentRelationshipsListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List related incidents for a specific incident.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRelationshipsV1.list({
    incident_id: "01FCNDV6P870EA6S7TK1DSYD5H",
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRelationshipsV1ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRelationshipsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Roles V1
<details><summary><code>client.incidentRolesV1.<a href="/src/api/resources/incidentRolesV1/client/Client.ts">list</a>() -> IncidentIO.IncidentRolesListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident roles for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV1.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IncidentRolesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV1.<a href="/src/api/resources/incidentRolesV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentRolesCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new incident role
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV1.create({
    description: "The person currently coordinating the incident",
    instructions: "Take point on the incident; Make sure people are clear on responsibilities",
    name: "Incident Lead",
    required: false,
    shortform: "lead"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV1.<a href="/src/api/resources/incidentRolesV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentRolesShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident role.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV1.<a href="/src/api/resources/incidentRolesV1/client/Client.ts">update</a>({ ...params }) -> IncidentIO.IncidentRolesUpdateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing incident role
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV1.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    description: "The person currently coordinating the incident",
    instructions: "Take point on the incident; Make sure people are clear on responsibilities",
    name: "Incident Lead",
    required: false,
    shortform: "lead"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesUpdatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV1.<a href="/src/api/resources/incidentRolesV1/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes an existing role
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV1.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesV1DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Statuses V1
<details><summary><code>client.incidentStatusesV1.<a href="/src/api/resources/incidentStatusesV1/client/Client.ts">list</a>() -> IncidentIO.IncidentStatusesListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident statuses for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentStatusesV1.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IncidentStatusesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentStatusesV1.<a href="/src/api/resources/incidentStatusesV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentStatusesCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new incident status
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentStatusesV1.create({
    category: "live",
    description: "Impact has been **fully mitigated**, and we're ready to learn from this incident.",
    name: "Closed"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentStatusesCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentStatusesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentStatusesV1.<a href="/src/api/resources/incidentStatusesV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentStatusesShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident status.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentStatusesV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYD5H"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentStatusesV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentStatusesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentStatusesV1.<a href="/src/api/resources/incidentStatusesV1/client/Client.ts">update</a>({ ...params }) -> IncidentIO.IncidentStatusesUpdateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing incident status
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentStatusesV1.update({
    id: "01FCNDV6P870EA6S7TK1DSYD5H",
    description: "Impact has been **fully mitigated**, and we're ready to learn from this incident.",
    name: "Closed"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentStatusesUpdatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentStatusesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentStatusesV1.<a href="/src/api/resources/incidentStatusesV1/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete an incident status
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentStatusesV1.delete({
    id: "01FCNDV6P870EA6S7TK1DSYD5H"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentStatusesV1DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentStatusesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Types V1
<details><summary><code>client.incidentTypesV1.<a href="/src/api/resources/incidentTypesV1/client/Client.ts">list</a>() -> IncidentIO.IncidentTypesListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident types for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentTypesV1.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IncidentTypesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentTypesV1.<a href="/src/api/resources/incidentTypesV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentTypesShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentTypesV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentTypesV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentTypesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incidents V1
<details><summary><code>client.incidentsV1.<a href="/src/api/resources/incidentsV1/client/Client.ts">list</a>({ ...params }) -> IncidentIO.IncidentsListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incidents for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV1.list({
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsV1ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentsV1.<a href="/src/api/resources/incidentsV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentsCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new incident.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV1.create({
    custom_field_entries: [{
            custom_field_id: "01FCNDV6P870EA6S7TK1DSYDG0",
            values: [{
                    id: "01FCNDV6P870EA6S7TK1DSYDG0",
                    value_catalog_entry_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                    value_link: "https://google.com/",
                    value_numeric: "123.456",
                    value_option_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                    value_text: "This is my text field, I hope you like it",
                    value_timestamp: ""
                }]
        }],
    idempotency_key: "alert-uuid",
    incident_role_assignments: [{
            assignee: {
                email: "bob@example.com",
                id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                slack_user_id: "USER123"
            },
            incident_role_id: "01FH5TZRWMNAFB0DZ23FD1TV96"
        }],
    incident_type_id: "01FH5TZRWMNAFB0DZ23FD1TV96",
    mode: "real",
    name: "Our database is sad",
    severity_id: "01FH5TZRWMNAFB0DZ23FD1TV96",
    slack_team_id: "T02A1FSLE8J",
    source_message_channel_id: "C02AW36C1M5",
    source_message_timestamp: "1653650280.526509",
    status: "triage",
    summary: "Our database is really really sad, and we don't know why yet.",
    visibility: "public"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentsV1.<a href="/src/api/resources/incidentsV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentsShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV1.show({
    id: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## IPAllowlists V1
<details><summary><code>client.ipallowlistsV1.<a href="/src/api/resources/ipallowlistsV1/client/Client.ts">showipallowlist</a>() -> IncidentIO.IpAllowlistsShowIpAllowlistResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show the IP allowlist for your organisation
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ipallowlistsV1.showipallowlist();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IpallowlistsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ipallowlistsV1.<a href="/src/api/resources/ipallowlistsV1/client/Client.ts">updateipallowlist</a>({ ...params }) -> IncidentIO.IpAllowlistsUpdateIpAllowlistResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update the IP allowlist for your organisation
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ipallowlistsV1.updateipallowlist({
    allowlist: [{
            label: "London HQ",
            value: "192.0.2.0"
        }],
    enabled: true,
    version: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IpAllowlistsUpdateIpAllowlistPayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IpallowlistsV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Severities V1
<details><summary><code>client.severitiesV1.<a href="/src/api/resources/severitiesV1/client/Client.ts">list</a>() -> IncidentIO.SeveritiesListResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident severities for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.severitiesV1.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `SeveritiesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.severitiesV1.<a href="/src/api/resources/severitiesV1/client/Client.ts">create</a>({ ...params }) -> IncidentIO.SeveritiesCreateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new severity
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.severitiesV1.create({
    description: "Issues with **low impact**.",
    name: "Minor",
    rank: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SeveritiesCreatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SeveritiesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.severitiesV1.<a href="/src/api/resources/severitiesV1/client/Client.ts">show</a>({ ...params }) -> IncidentIO.SeveritiesShowResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident severity.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.severitiesV1.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SeveritiesV1ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SeveritiesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.severitiesV1.<a href="/src/api/resources/severitiesV1/client/Client.ts">update</a>({ ...params }) -> IncidentIO.SeveritiesUpdateResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing severity
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.severitiesV1.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    description: "Issues with **low impact**.",
    name: "Minor",
    rank: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SeveritiesUpdatePayloadV1` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SeveritiesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.severitiesV1.<a href="/src/api/resources/severitiesV1/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a severity
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.severitiesV1.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SeveritiesV1DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SeveritiesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Status Pages V1
<details><summary><code>client.statusPagesV1.<a href="/src/api/resources/statusPagesV1/client/Client.ts">listresponseincidents</a>({ ...params }) -> IncidentIO.StatusPagesListResponseIncidentsResultV1</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List the linked Response incidents for a status page incident.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.statusPagesV1.listresponseincidents({
    id: "abc123",
    incident_id: "abc123"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.StatusPagesV1ListResponseIncidentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StatusPagesV1Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Actions V2
<details><summary><code>client.actionsV2.<a href="/src/api/resources/actionsV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.ActionsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all actions for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.actionsV2.list({
    incident_id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.ActionsV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ActionsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.actionsV2.<a href="/src/api/resources/actionsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.ActionsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident action.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.actionsV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.ActionsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ActionsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Alert Attributes V2
<details><summary><code>client.alertAttributesV2.<a href="/src/api/resources/alertAttributesV2/client/Client.ts">list</a>() -> IncidentIO.AlertAttributesListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List alert attributes.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertAttributesV2.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AlertAttributesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertAttributesV2.<a href="/src/api/resources/alertAttributesV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.AlertAttributesCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new alert attribute.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertAttributesV2.create({
    array: false,
    name: "service",
    required: false,
    type: "CatalogEntry[\"01GW2G3V0S59R238FAHPDS1R67\"]"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertAttributesCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertAttributesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertAttributesV2.<a href="/src/api/resources/alertAttributesV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.AlertAttributesShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show an alert attribute.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertAttributesV2.show({
    id: "01GW2G3V0S59R238FAHPDS1R66"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertAttributesV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertAttributesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertAttributesV2.<a href="/src/api/resources/alertAttributesV2/client/Client.ts">update</a>({ ...params }) -> IncidentIO.AlertAttributesUpdateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an alert attribute.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertAttributesV2.update({
    id: "01GW2G3V0S59R238FAHPDS1R66",
    array: false,
    name: "service",
    required: false,
    type: "CatalogEntry[\"01GW2G3V0S59R238FAHPDS1R67\"]"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertAttributesUpdatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertAttributesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertAttributesV2.<a href="/src/api/resources/alertAttributesV2/client/Client.ts">destroy</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Destroy an alert attribute.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertAttributesV2.destroy({
    id: "01GW2G3V0S59R238FAHPDS1R66"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertAttributesV2DestroyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertAttributesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Alert Events V2
<details><summary><code>client.alertEventsV2.<a href="/src/api/resources/alertEventsV2/client/Client.ts">createhttp</a>({ ...params }) -> IncidentIO.AlertEventsCreateHttpResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an alert event using an HTTP source.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertEventsV2.createhttp({
    alert_source_config_id: "01GW2G3V0S59R238FAHPDS1R66",
    token: "some-random-string",
    deduplication_key: "4293868629",
    description: "We've detected a number of timeouts on hello.world.com, the service may be down. To fix...",
    metadata: {
        "service": "hello.world.com",
        "team": [
            "my-team"
        ]
    },
    source_url: "https://www.my-alerting-platform.com/alerts/my-alert-123",
    status: "firing",
    title: "*errors.withMessage: PG::Error failed to connect"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertEventsCreateHttpPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertEventsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Alert Routes V2
<details><summary><code>client.alertRoutesV2.<a href="/src/api/resources/alertRoutesV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.AlertRoutesListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all alert routes in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertRoutesV2.list({
    page_size: 25,
    after: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertRoutesV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertRoutesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertRoutesV2.<a href="/src/api/resources/alertRoutesV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.AlertRoutesCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new alert route in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertRoutesV2.create({
    alert_sources: [{
            alert_source_id: "01FCNDV6P870EA6S7TK1DSYDG0",
            condition_groups: [{
                    conditions: [{
                            operation: "one_of",
                            param_bindings: [{
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }],
                            subject: "incident.severity"
                        }]
                }]
        }],
    channel_config: [{
            condition_groups: [{
                    conditions: [{
                            operation: "one_of",
                            param_bindings: [{
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }],
                            subject: "incident.severity"
                        }]
                }],
            ms_teams_targets: {
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                channel_visibility: "abc123"
            },
            slack_targets: {
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                channel_visibility: "abc123"
            }
        }],
    condition_groups: [{
            conditions: [{
                    operation: "one_of",
                    param_bindings: [{
                            array_value: [{
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }],
                            value: {
                                literal: "SEV123",
                                reference: "incident.severity"
                            }
                        }],
                    subject: "incident.severity"
                }]
        }],
    created_at: "2021-08-17T13:28:57Z",
    enabled: false,
    escalation_config: {
        auto_cancel_escalations: false,
        escalation_targets: [{
                escalation_paths: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                users: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            }]
    },
    expressions: [{
            else_branch: {
                result: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            },
            label: "Team Slack channel",
            operations: [{
                    branches: {
                        branches: [{
                                condition_groups: [{
                                        conditions: [{
                                                operation: "one_of",
                                                param_bindings: [{
                                                        array_value: [{
                                                                literal: "SEV123",
                                                                reference: "incident.severity"
                                                            }],
                                                        value: {
                                                            literal: "SEV123",
                                                            reference: "incident.severity"
                                                        }
                                                    }],
                                                subject: "incident.severity"
                                            }]
                                    }],
                                result: {
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }
                            }],
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        }
                    },
                    concatenate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    filter: {
                        condition_groups: [{
                                conditions: [{
                                        operation: "one_of",
                                        param_bindings: [{
                                                array_value: [{
                                                        literal: "SEV123",
                                                        reference: "incident.severity"
                                                    }],
                                                value: {
                                                    literal: "SEV123",
                                                    reference: "incident.severity"
                                                }
                                            }],
                                        subject: "incident.severity"
                                    }]
                            }]
                    },
                    navigate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    operation_type: "navigate",
                    parse: {
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        },
                        source: "metadata.annotations[\"github.com/repo\"]"
                    }
                }],
            reference: "abc123",
            root_reference: "incident.status"
        }],
    incident_config: {
        auto_decline_enabled: false,
        auto_relate_grouped_alerts: false,
        condition_groups: [{
                conditions: [{
                        operation: "one_of",
                        param_bindings: [{
                                array_value: [{
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }],
                                value: {
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }
                            }],
                        subject: "incident.severity"
                    }]
            }],
        defer_time_seconds: 1,
        enabled: false,
        grouping_keys: [{
                reference: "alert.title"
            }],
        grouping_window_seconds: 1
    },
    incident_template: {
        custom_fields: [{
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                custom_field_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                merge_strategy: "first-wins"
            }],
        incident_mode: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        incident_type: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        name: {
            autogenerated: false,
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        severity: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            },
            merge_strategy: "first-wins"
        },
        start_in_triage: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        summary: {
            autogenerated: false,
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        workspace: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        }
    },
    is_private: false,
    name: "Production incidents",
    owning_team_ids: ["01G0J1EXE7AXZ2C93K61WBPYEH"],
    updated_at: "2021-08-17T13:28:57Z",
    version: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertRoutesCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertRoutesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertRoutesV2.<a href="/src/api/resources/alertRoutesV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.AlertRoutesShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Load details about a specific alert route in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertRoutesV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertRoutesV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertRoutesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertRoutesV2.<a href="/src/api/resources/alertRoutesV2/client/Client.ts">update</a>({ ...params }) -> IncidentIO.AlertRoutesUpdateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing alert route in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertRoutesV2.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    alert_sources: [{
            alert_source_id: "01FCNDV6P870EA6S7TK1DSYDG0",
            condition_groups: [{
                    conditions: [{
                            operation: "one_of",
                            param_bindings: [{
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }],
                            subject: "incident.severity"
                        }]
                }]
        }],
    channel_config: [{
            condition_groups: [{
                    conditions: [{
                            operation: "one_of",
                            param_bindings: [{
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }],
                            subject: "incident.severity"
                        }]
                }],
            ms_teams_targets: {
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                channel_visibility: "abc123"
            },
            slack_targets: {
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                channel_visibility: "abc123"
            }
        }],
    condition_groups: [{
            conditions: [{
                    operation: "one_of",
                    param_bindings: [{
                            array_value: [{
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }],
                            value: {
                                literal: "SEV123",
                                reference: "incident.severity"
                            }
                        }],
                    subject: "incident.severity"
                }]
        }],
    created_at: "2021-08-17T13:28:57Z",
    enabled: false,
    escalation_config: {
        auto_cancel_escalations: false,
        escalation_targets: [{
                escalation_paths: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                users: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            }]
    },
    expressions: [{
            else_branch: {
                result: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            },
            label: "Team Slack channel",
            operations: [{
                    branches: {
                        branches: [{
                                condition_groups: [{
                                        conditions: [{
                                                operation: "one_of",
                                                param_bindings: [{
                                                        array_value: [{
                                                                literal: "SEV123",
                                                                reference: "incident.severity"
                                                            }],
                                                        value: {
                                                            literal: "SEV123",
                                                            reference: "incident.severity"
                                                        }
                                                    }],
                                                subject: "incident.severity"
                                            }]
                                    }],
                                result: {
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }
                            }],
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        }
                    },
                    concatenate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    filter: {
                        condition_groups: [{
                                conditions: [{
                                        operation: "one_of",
                                        param_bindings: [{
                                                array_value: [{
                                                        literal: "SEV123",
                                                        reference: "incident.severity"
                                                    }],
                                                value: {
                                                    literal: "SEV123",
                                                    reference: "incident.severity"
                                                }
                                            }],
                                        subject: "incident.severity"
                                    }]
                            }]
                    },
                    navigate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    operation_type: "navigate",
                    parse: {
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        },
                        source: "metadata.annotations[\"github.com/repo\"]"
                    }
                }],
            reference: "abc123",
            root_reference: "incident.status"
        }],
    incident_config: {
        auto_decline_enabled: false,
        auto_relate_grouped_alerts: false,
        condition_groups: [{
                conditions: [{
                        operation: "one_of",
                        param_bindings: [{
                                array_value: [{
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }],
                                value: {
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }
                            }],
                        subject: "incident.severity"
                    }]
            }],
        defer_time_seconds: 1,
        enabled: false,
        grouping_keys: [{
                reference: "alert.title"
            }],
        grouping_window_seconds: 1
    },
    incident_template: {
        custom_fields: [{
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                },
                custom_field_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                merge_strategy: "first-wins"
            }],
        incident_mode: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        incident_type: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        name: {
            autogenerated: false,
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        severity: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            },
            merge_strategy: "first-wins"
        },
        start_in_triage: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        summary: {
            autogenerated: false,
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        },
        workspace: {
            binding: {
                array_value: [{
                        literal: "SEV123",
                        reference: "incident.severity"
                    }],
                value: {
                    literal: "SEV123",
                    reference: "incident.severity"
                }
            }
        }
    },
    is_private: false,
    name: "Production incidents",
    owning_team_ids: ["01G0J1EXE7AXZ2C93K61WBPYEH"],
    updated_at: "2021-08-17T13:28:57Z",
    version: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertRoutesUpdatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertRoutesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertRoutesV2.<a href="/src/api/resources/alertRoutesV2/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete an existing alert route in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertRoutesV2.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertRoutesV2DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertRoutesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Alert Sources V2
<details><summary><code>client.alertSourcesV2.<a href="/src/api/resources/alertSourcesV2/client/Client.ts">list</a>() -> IncidentIO.AlertSourcesListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all alert sources in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertSourcesV2.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AlertSourcesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertSourcesV2.<a href="/src/api/resources/alertSourcesV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.AlertSourcesCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new alert source in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertSourcesV2.create({
    http_custom_options: {
        deduplication_key_path: "$.alert_id",
        transform_expression: "return {\n  title: $.title || $.name || 'Unknown Alert',\n  status: $.status === 'resolved' ? 'resolved' : 'firing',\n  description: $.description || $.message || '',\n  sourceURL: $.url || $.link || '',\n  metadata: { team: $.team, severity: $.severity }\n}"
    },
    jira_options: {
        project_ids: ["01GBSQF3FHF7FWZQNWGHAVQ804", "10043"]
    },
    name: "Production Web Dashboard Alerts",
    owning_team_ids: ["01G0J1EXE7AXZ2C93K61WBPYEH"],
    source_type: "alertmanager",
    template: {
        attributes: [{
                alert_attribute_id: "abc123",
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            }],
        description: {
            literal: "SEV123",
            reference: "incident.severity"
        },
        expressions: [{
                else_branch: {
                    result: {
                        array_value: [{
                                literal: "SEV123",
                                reference: "incident.severity"
                            }],
                        value: {
                            literal: "SEV123",
                            reference: "incident.severity"
                        }
                    }
                },
                label: "Team Slack channel",
                operations: [{
                        branches: {
                            branches: [{
                                    condition_groups: [{
                                            conditions: [{
                                                    operation: "one_of",
                                                    param_bindings: [{
                                                            array_value: [{
                                                                    literal: "SEV123",
                                                                    reference: "incident.severity"
                                                                }],
                                                            value: {
                                                                literal: "SEV123",
                                                                reference: "incident.severity"
                                                            }
                                                        }],
                                                    subject: "incident.severity"
                                                }]
                                        }],
                                    result: {
                                        array_value: [{
                                                literal: "SEV123",
                                                reference: "incident.severity"
                                            }],
                                        value: {
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }
                                    }
                                }],
                            returns: {
                                array: true,
                                type: "IncidentStatus"
                            }
                        },
                        concatenate: {
                            reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                        },
                        filter: {
                            condition_groups: [{
                                    conditions: [{
                                            operation: "one_of",
                                            param_bindings: [{
                                                    array_value: [{
                                                            literal: "SEV123",
                                                            reference: "incident.severity"
                                                        }],
                                                    value: {
                                                        literal: "SEV123",
                                                        reference: "incident.severity"
                                                    }
                                                }],
                                            subject: "incident.severity"
                                        }]
                                }]
                        },
                        navigate: {
                            reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                        },
                        operation_type: "navigate",
                        parse: {
                            returns: {
                                array: true,
                                type: "IncidentStatus"
                            },
                            source: "metadata.annotations[\"github.com/repo\"]"
                        }
                    }],
                reference: "abc123",
                root_reference: "incident.status"
            }],
        is_private: false,
        title: {
            literal: "SEV123",
            reference: "incident.severity"
        },
        visible_to_teams: {
            array_value: [{
                    literal: "SEV123",
                    reference: "incident.severity"
                }],
            value: {
                literal: "SEV123",
                reference: "incident.severity"
            }
        }
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertSourcesCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertSourcesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertSourcesV2.<a href="/src/api/resources/alertSourcesV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.AlertSourcesShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Load details about a specific alert source in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertSourcesV2.show({
    id: "01GW2G3V0S59R238FAHPDS1R66"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertSourcesV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertSourcesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertSourcesV2.<a href="/src/api/resources/alertSourcesV2/client/Client.ts">update</a>({ ...params }) -> IncidentIO.AlertSourcesUpdateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing alert source in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertSourcesV2.update({
    id: "01GW2G3V0S59R238FAHPDS1R66",
    http_custom_options: {
        deduplication_key_path: "$.alert_id",
        transform_expression: "return {\n  title: $.title || $.name || 'Unknown Alert',\n  status: $.status === 'resolved' ? 'resolved' : 'firing',\n  description: $.description || $.message || '',\n  sourceURL: $.url || $.link || '',\n  metadata: { team: $.team, severity: $.severity }\n}"
    },
    jira_options: {
        project_ids: ["01GBSQF3FHF7FWZQNWGHAVQ804", "10043"]
    },
    name: "Production Web Dashboard Alerts",
    owning_team_ids: ["01G0J1EXE7AXZ2C93K61WBPYEH"],
    template: {
        attributes: [{
                alert_attribute_id: "abc123",
                binding: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            }],
        description: {
            literal: "SEV123",
            reference: "incident.severity"
        },
        expressions: [{
                else_branch: {
                    result: {
                        array_value: [{
                                literal: "SEV123",
                                reference: "incident.severity"
                            }],
                        value: {
                            literal: "SEV123",
                            reference: "incident.severity"
                        }
                    }
                },
                label: "Team Slack channel",
                operations: [{
                        branches: {
                            branches: [{
                                    condition_groups: [{
                                            conditions: [{
                                                    operation: "one_of",
                                                    param_bindings: [{
                                                            array_value: [{
                                                                    literal: "SEV123",
                                                                    reference: "incident.severity"
                                                                }],
                                                            value: {
                                                                literal: "SEV123",
                                                                reference: "incident.severity"
                                                            }
                                                        }],
                                                    subject: "incident.severity"
                                                }]
                                        }],
                                    result: {
                                        array_value: [{
                                                literal: "SEV123",
                                                reference: "incident.severity"
                                            }],
                                        value: {
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }
                                    }
                                }],
                            returns: {
                                array: true,
                                type: "IncidentStatus"
                            }
                        },
                        concatenate: {
                            reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                        },
                        filter: {
                            condition_groups: [{
                                    conditions: [{
                                            operation: "one_of",
                                            param_bindings: [{
                                                    array_value: [{
                                                            literal: "SEV123",
                                                            reference: "incident.severity"
                                                        }],
                                                    value: {
                                                        literal: "SEV123",
                                                        reference: "incident.severity"
                                                    }
                                                }],
                                            subject: "incident.severity"
                                        }]
                                }]
                        },
                        navigate: {
                            reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                        },
                        operation_type: "navigate",
                        parse: {
                            returns: {
                                array: true,
                                type: "IncidentStatus"
                            },
                            source: "metadata.annotations[\"github.com/repo\"]"
                        }
                    }],
                reference: "abc123",
                root_reference: "incident.status"
            }],
        is_private: false,
        title: {
            literal: "SEV123",
            reference: "incident.severity"
        },
        visible_to_teams: {
            array_value: [{
                    literal: "SEV123",
                    reference: "incident.severity"
                }],
            value: {
                literal: "SEV123",
                reference: "incident.severity"
            }
        }
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertSourcesUpdatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertSourcesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertSourcesV2.<a href="/src/api/resources/alertSourcesV2/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete an existing alert source in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertSourcesV2.delete({
    id: "01GW2G3V0S59R238FAHPDS1R66"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertSourcesV2DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertSourcesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Alerts V2
<details><summary><code>client.alertsV2.<a href="/src/api/resources/alertsV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.AlertsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all alerts for your account.
		
This endpoint supports a number of filters, which can help find alerts matching certain
criteria. These filters work similarly to the filters on the incidents endpoint, where 
a field is specified alongside a comparison operator in the query string.

Note that:
- Filters may be used together, and the result will be alerts that match all filters.
- All query parameters must be URI encoded.

### By deduplication_key

Find all alerts with deduplication_key ABC:

		curl --get 'https://api.incident.io/v2/alerts' \
			--data 'deduplication_key[is]=ABC'

### By status

Find all alerts in a firing state:

		curl --get 'https://api.incident.io/v2/alerts' \
			--data 'status[one_of]=firing'

### By created_at
Find all alerts that follow specified date parameters for created_at field.
Possible values are "gte" (greater than or equal to), "lte" (less than or equal to), and 
"date_range" (between two dates). The following example finds all alerts created after 
2025-01-01:

		curl --get 'https://api.incident.io/v2/alerts' \
			--data 'created_at[gte]=2025-01-01'

To find alerts created within a specific date range, use the date_range option with 
tilde-separated dates:

		curl --get 'https://api.incident.io/v2/alerts' \
			--data 'created_at[date_range]=2024-12-02~2024-12-08'
		
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertsV2.list({
    page_size: 25,
    after: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertsV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertsV2.<a href="/src/api/resources/alertsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.AlertsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a single alert for your account
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertsV2.show({
    id: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.alertsV2.<a href="/src/api/resources/alertsV2/client/Client.ts">listincidentalerts</a>({ ...params }) -> IncidentIO.AlertsListIncidentAlertsResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List the connections between incidents and alerts
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.alertsV2.listincidentalerts({
    page_size: 25,
    after: "01FCNDV6P870EA6S7TK1DSYDG0",
    alert_id: "01FCNDV6P870EA6S7TK1DSYDG1",
    incident_id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.AlertsV2ListIncidentAlertsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AlertsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Catalog V2
<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">listentries</a>({ ...params }) -> IncidentIO.CatalogListEntriesResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List entries for a catalog type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.listentries({
    catalog_type_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV2ListEntriesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">createentry</a>({ ...params }) -> IncidentIO.CatalogCreateEntryResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an entry within the catalog. We support a maximum of 50,000 entries per type.

If you call this API with a payload where the external_id and catalog_type_id match an existing entry, the existing entry will be updated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.createentry({
    aliases: ["lawrence@incident.io", "lawrence"],
    attribute_values: {
        "abc123": {
            array_value: [{
                    literal: "SEV123",
                    reference: "incident.severity"
                }],
            value: {
                literal: "SEV123",
                reference: "incident.severity"
            }
        }
    },
    catalog_type_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    external_id: "761722cd-d1d7-477b-ac7e-90f9e079dc33",
    name: "Primary On-call",
    rank: 3
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogCreateEntryPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">showentry</a>({ ...params }) -> IncidentIO.CatalogShowEntryResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a single catalog entry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.showentry({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV2ShowEntryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">updateentry</a>({ ...params }) -> IncidentIO.CatalogUpdateEntryResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an existing catalog entry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.updateentry({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    aliases: ["lawrence@incident.io", "lawrence"],
    attribute_values: {
        "abc123": {
            array_value: [{
                    literal: "SEV123",
                    reference: "incident.severity"
                }],
            value: {
                literal: "SEV123",
                reference: "incident.severity"
            }
        }
    },
    external_id: "761722cd-d1d7-477b-ac7e-90f9e079dc33",
    name: "Primary On-call",
    rank: 3
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogUpdateEntryPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">destroyentry</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives a catalog entry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.destroyentry({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV2DestroyEntryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">listresources</a>() -> IncidentIO.CatalogListResourcesResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List available engine resources for the catalog.

A resource represents a type of data that can be held within the catalog, so this
endpoint can be used to see what attribute types can be used when updating the
schema of a catalog type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.listresources();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">listtypes</a>() -> IncidentIO.CatalogListTypesResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all catalog types for an organisation, including those synced from external resources.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.listtypes();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">createtype</a>({ ...params }) -> IncidentIO.CatalogCreateTypeResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a catalog type. The schema must be updated using the UpdateTypeSchema endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.createtype({
    annotations: {
        "incident.io/catalog-importer/id": "id-of-config"
    },
    categories: ["customer"],
    color: "yellow",
    description: "Represents Kubernetes clusters that we run inside of GKE.",
    icon: "alert",
    name: "Kubernetes Cluster",
    ranked: true,
    source_repo_url: "https://github.com/my-company/incident-io-catalog",
    type_name: "Custom[\"BackstageGroup\"]"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogCreateTypePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">showtype</a>({ ...params }) -> IncidentIO.CatalogShowTypeResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a single catalog type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.showtype({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV2ShowTypeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">updatetype</a>({ ...params }) -> IncidentIO.CatalogUpdateTypeResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an existing catalog type. The schema must be updated using the UpdateTypeSchema endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.updatetype({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    annotations: {
        "incident.io/catalog-importer/id": "id-of-config"
    },
    categories: ["customer"],
    color: "yellow",
    description: "Represents Kubernetes clusters that we run inside of GKE.",
    icon: "alert",
    name: "Kubernetes Cluster",
    ranked: true,
    source_repo_url: "https://github.com/my-company/incident-io-catalog"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogUpdateTypePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">destroytype</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives a catalog type and associated entries.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.destroytype({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV2DestroyTypeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV2.<a href="/src/api/resources/catalogV2/client/Client.ts">updatetypeschema</a>({ ...params }) -> IncidentIO.CatalogUpdateTypeSchemaResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing catalog types schema, adding or removing attributes.

Updating the schema is handled separately from creating and updating types, so that you don't
have to worry about dependencies between types. For example, if type A has an attribute that
relies on type B, you would have to create type B first.

By allowing the creation of types without a schema, they can be created in any order, but it
means that you need to make a separate call to this endpoint to update the schema.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV2.updatetypeschema({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    attributes: [{
            array: false,
            backlink_attribute: "abc123",
            id: "01GW2G3V0S59R238FAHPDS1R66",
            mode: "",
            name: "tier",
            path: [{
                    attribute_id: "abc123"
                }],
            type: "Custom[\"Service\"]"
        }],
    version: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogUpdateTypeSchemaPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Custom Fields V2
<details><summary><code>client.customFieldsV2.<a href="/src/api/resources/customFieldsV2/client/Client.ts">list</a>() -> IncidentIO.CustomFieldsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all custom fields for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV2.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CustomFieldsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV2.<a href="/src/api/resources/customFieldsV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.CustomFieldsCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV2.create({
    catalog_type_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    description: "Which team is impacted by this issue",
    field_type: "single_select",
    filter_by: {
        catalog_attribute_id: "01H2FW182TAH0NHEVBY34SCAK0",
        custom_field_id: "01H2FW182TAH0NHEVBY34SCAK0"
    },
    group_by_catalog_attribute_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    helptext_catalog_attribute_id: "01H2FW182TAH0NHEVBY34SCAK0",
    name: "Affected Team"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV2.<a href="/src/api/resources/customFieldsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.CustomFieldsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single custom field.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV2.<a href="/src/api/resources/customFieldsV2/client/Client.ts">update</a>({ ...params }) -> IncidentIO.CustomFieldsUpdateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update the details of a custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV2.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    description: "Which team is impacted by this issue",
    filter_by: {
        catalog_attribute_id: "01H2FW182TAH0NHEVBY34SCAK0",
        custom_field_id: "01H2FW182TAH0NHEVBY34SCAK0"
    },
    group_by_catalog_attribute_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    helptext_catalog_attribute_id: "01H2FW182TAH0NHEVBY34SCAK0",
    name: "Affected Team"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsUpdatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customFieldsV2.<a href="/src/api/resources/customFieldsV2/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a custom field
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customFieldsV2.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CustomFieldsV2DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomFieldsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Escalations V2
<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">createpath</a>({ ...params }) -> IncidentIO.EscalationsCreatePathResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an escalation path.

An escalation path is a series of steps that describe how a page should be escalated,
represented as graph, supporting conditional branches based on alert priority and working
intervals.

We recommend you create escalation paths in the incident.io dashboard where our path
builder makes it easy to use conditions and visualise the path.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.createpath({
    name: "Urgent Support",
    path: [{
            id: "01FCNDV6P870EA6S7TK1DSYDG0",
            if_else: {
                conditions: [{
                        operation: "one_of",
                        param_bindings: [{
                                array_value: [{
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }],
                                value: {
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }
                            }],
                        subject: "incident.severity"
                    }],
                else_path: [],
                then_path: []
            },
            level: {
                ack_mode: "all",
                round_robin_config: {
                    enabled: false,
                    rotate_after_seconds: 120
                },
                targets: [{
                        id: "lawrencejones",
                        schedule_mode: "currently_on_call",
                        type: "schedule",
                        urgency: "high"
                    }],
                time_to_ack_interval_condition: "active",
                time_to_ack_seconds: 1800,
                time_to_ack_weekday_interval_config_id: "01FCNDV6P870EA6S7TK1DSYDG0"
            },
            notify_channel: {
                targets: [{
                        id: "lawrencejones",
                        schedule_mode: "currently_on_call",
                        type: "schedule",
                        urgency: "high"
                    }],
                time_to_ack_interval_condition: "active",
                time_to_ack_seconds: 1800,
                time_to_ack_weekday_interval_config_id: "01FCNDV6P870EA6S7TK1DSYDG0"
            },
            repeat: {
                repeat_times: 3,
                to_node: "01FCNDV6P870EA6S7TK1DSYDG0"
            },
            type: "if_else"
        }],
    team_ids: ["01JPQA75EPNEES4479P16P4XAB"],
    working_hours: [{
            id: "abc123",
            name: "abc123",
            timezone: "abc123",
            weekday_intervals: [{
                    end_time: "17:00",
                    start_time: "09:00",
                    weekday: "monday"
                }]
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsCreatePathPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">showpath</a>({ ...params }) -> IncidentIO.EscalationsShowPathResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show an escalation path.

We recommend you create escalation paths in the incident.io dashboard where our path
builder makes it easy to use conditions and visualise the path.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.showpath({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsV2ShowPathRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">updatepath</a>({ ...params }) -> IncidentIO.EscalationsUpdatePathResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an escalation path.

We recommend you create escalation paths in the incident.io dashboard where our path
builder makes it easy to use conditions and visualise the path.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.updatepath({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    name: "Urgent Support",
    path: [{
            id: "01FCNDV6P870EA6S7TK1DSYDG0",
            if_else: {
                conditions: [{
                        operation: "one_of",
                        param_bindings: [{
                                array_value: [{
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }],
                                value: {
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }
                            }],
                        subject: "incident.severity"
                    }],
                else_path: [],
                then_path: []
            },
            level: {
                ack_mode: "all",
                round_robin_config: {
                    enabled: false,
                    rotate_after_seconds: 120
                },
                targets: [{
                        id: "lawrencejones",
                        schedule_mode: "currently_on_call",
                        type: "schedule",
                        urgency: "high"
                    }],
                time_to_ack_interval_condition: "active",
                time_to_ack_seconds: 1800,
                time_to_ack_weekday_interval_config_id: "01FCNDV6P870EA6S7TK1DSYDG0"
            },
            notify_channel: {
                targets: [{
                        id: "lawrencejones",
                        schedule_mode: "currently_on_call",
                        type: "schedule",
                        urgency: "high"
                    }],
                time_to_ack_interval_condition: "active",
                time_to_ack_seconds: 1800,
                time_to_ack_weekday_interval_config_id: "01FCNDV6P870EA6S7TK1DSYDG0"
            },
            repeat: {
                repeat_times: 3,
                to_node: "01FCNDV6P870EA6S7TK1DSYDG0"
            },
            type: "if_else"
        }],
    team_ids: ["01JPQA75EPNEES4479P16P4XAB"],
    working_hours: [{
            id: "abc123",
            name: "abc123",
            timezone: "abc123",
            weekday_intervals: [{
                    end_time: "17:00",
                    start_time: "09:00",
                    weekday: "monday"
                }]
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsUpdatePathPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">destroypath</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives an escalation path.

We recommend you create escalation paths in the incident.io dashboard where our path
builder makes it easy to use conditions and visualise the path.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.destroypath({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsV2DestroyPathRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.EscalationsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all escalations for your account.

This endpoint supports a number of filters, which can help find escalations matching certain
criteria.

Note that:
- Filters may be used together, and the result will be escalations that match all filters.
- All query parameters must be URI encoded.

To use this API, you will need an API key with the "View data" or "Create and manage on-call resources" permission.

### By escalation_path

Find all escalations that escalated to escalation path with id=ABC:

		curl --get 'https://api.incident.io/v2/escalations' \
			--data 'escalation_path[one_of]=ABC'

### By status

Find all escalations with a current status of "triggered":

		curl --get 'https://api.incident.io/v2/escalations' \
			--data 'status[one_of]=triggered'

Possible values are "pending", "triggered", "acked", "resolved", "expired" and "cancelled".
Escalations are in "pending" when they are in a grace period when the related alert has
been grouped in an incident.

### By alert

Find all escalations that were created by alert with id=ABC:

		curl --get 'https://api.incident.io/v2/escalations' \
			--data 'alert[one_of]=ABC'

### By created_at and updated_at
Find all escalations that follow specified date parameters for created_at and updated_at fields.
Possible values are "gte" (greater than or equal to), "lte" (less than or equal to), and
"date_range" (between two dates).
For example, to find all escalations updated after 2025-01-01:

		curl --get 'https://api.incident.io/v2/escalations' \
			--data 'updated_at[gte]=2025-01-01'

To find all escalations created between 2025-01-01 and 2025-01-31:

		curl --get 'https://api.incident.io/v2/escalations' \
            --data 'created_at[date_range]=2025-01-01~2025-01-31'
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.list({
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.EscalationsCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an escalation.

An escalation pages people, either according to an escalation path, or directly to
specific users. You must provide either an escalation_path_id OR user_ids, but not both.

When escalating via an escalation path, the escalation will follow the configured path
with its levels and timeouts, using your default [alert
priority](https://app.incident.io/~/settings/alerts/configuration/priorities).

When escalating directly to users, they will receive a high-urgency
notification, based on their notification rules.

This endpoint is rate-limited to 60 requests per minute, since it is intended for
interactive use cases (for example someone clicking a "escalate to team" button
in your internal developer platform). To escalate based on automated alerts, we
recommend sending events to an alert source instead.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.create({
    description: "Database CPU has been above 90% for 5 minutes",
    escalation_path_id: "01H0J1EXE7AXZ2C93K61WBPYEH",
    idempotency_key: "2024-01-15-abc123",
    title: "Production database experiencing high CPU",
    user_ids: ["01H0J1EXE7AXZ2C93K61WBPYEH", "01H0J1EXE7AXZ2C93K61WBPYEI"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.escalationsV2.<a href="/src/api/resources/escalationsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.EscalationsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a specific escalation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.escalationsV2.show({
    id: "01G0J1EXE7AXZ2C93K61WBPYEH"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.EscalationsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EscalationsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Follow-ups V2
<details><summary><code>client.followUpsV2.<a href="/src/api/resources/followUpsV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.FollowUpsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all follow-ups for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.followUpsV2.list({
    incident_id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.FollowUpsV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FollowUpsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.followUpsV2.<a href="/src/api/resources/followUpsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.FollowUpsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident follow-up.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.followUpsV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.FollowUpsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FollowUpsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Roles V2
<details><summary><code>client.incidentRolesV2.<a href="/src/api/resources/incidentRolesV2/client/Client.ts">list</a>() -> IncidentIO.IncidentRolesListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident roles for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV2.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IncidentRolesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV2.<a href="/src/api/resources/incidentRolesV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentRolesCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new incident role
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV2.create({
    description: "The person currently coordinating the incident",
    instructions: "Take point on the incident; Make sure people are clear on responsibilities",
    name: "Incident Lead",
    shortform: "lead"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV2.<a href="/src/api/resources/incidentRolesV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentRolesShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident role.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV2.<a href="/src/api/resources/incidentRolesV2/client/Client.ts">update</a>({ ...params }) -> IncidentIO.IncidentRolesUpdateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing incident role
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV2.update({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    description: "The person currently coordinating the incident",
    instructions: "Take point on the incident; Make sure people are clear on responsibilities",
    name: "Incident Lead",
    shortform: "lead"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesUpdatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentRolesV2.<a href="/src/api/resources/incidentRolesV2/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes an existing role
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentRolesV2.delete({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentRolesV2DeleteRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentRolesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Timestamps V2
<details><summary><code>client.incidentTimestampsV2.<a href="/src/api/resources/incidentTimestampsV2/client/Client.ts">list</a>() -> IncidentIO.IncidentTimestampsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident timestamps for an organisation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentTimestampsV2.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IncidentTimestampsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentTimestampsV2.<a href="/src/api/resources/incidentTimestampsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentTimestampsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident timestamp.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentTimestampsV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYD5H"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentTimestampsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentTimestampsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incident Updates V2
<details><summary><code>client.incidentUpdatesV2.<a href="/src/api/resources/incidentUpdatesV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.IncidentUpdatesListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incident updates for an organisation, or for a specific incident.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentUpdatesV2.list({
    incident_id: "01G0J1EXE7AXZ2C93K61WBPYEH",
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentUpdatesV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentUpdatesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Incidents V2
<details><summary><code>client.incidentsV2.<a href="/src/api/resources/incidentsV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.IncidentsListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all incidents for an organisation.

This endpoint supports a number of filters, which can help find incidents matching certain
criteria.

Filters are provided as query parameters, but due to the dynamic nature of what you can
query by (different accounts have different custom fields, statuses, etc) they are more
complex than most.

The maximum page size that can be requested is 250.

To help, here are some exemplar curl requests with a human description of what they search
for.

Note that:
- Filters may be combined using the filter_mode parameter: 'all' (default) requires all filters
to match (AND logic), while 'any' requires at least one filter to match (OR logic).
- IDs are normally in UUID format, but have been replaced with shorter strings to improve
readability.
- All query parameters must be URI encoded.

### By status

With status of id=ABC, find all incidents that are set to that status:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'status[one_of]=ABC'

Or all incidents that are not set to status with id=ABC:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'status[not_in]=ABC'

### By created_at or updated_at

Find all incidents that follow specified date parameters for created_at and updated_at fields.
Possible values are "gte" (greater than or equal to), "lte" (less than or equal to), and
"date_range" (between two dates). The following example finds all incidents created before
or on 2021-01-02T00:00:00Z:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'created_at[lte]=2021-01-02'

To find incidents created within a specific date range, use the date_range option with
tilde-separated dates:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'created_at[date_range]=2024-12-02~2024-12-08'

### By status category

Find all incidents that are in a status category. Possible values are "triage",
"declined", "merged", "canceled", "live", "learning" and "closed":

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'status_category[one_of]=live'

Or all incidents that are not in a status category:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'status_category[not_in]=live'


### By severity

With severity of id=ABC, find all incidents that are set to that severity:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'severity[one_of]=ABC'

Or all incidents where severity rank is greater-than-or-equal-to the rank of severity
id=ABC:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'severity[gte]=ABC'

Or all incidents where severity rank is less-than-or-equal-to the rank of severity id=ABC:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'severity[lte]=ABC'

### By incident type

With incident type of id=ABC, find all incidents that are of that type:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'incident_type[one_of]=ABC'

Or all incidents not of that type:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'incident_type[not_in]=ABC'

### By incident mode

By default, we return standard and retrospective incidents. This means that test and
tutorial incidents are filtered out. To override this behaviour, you can use the
mode filter to specify which modes you want to get.

To find incidents of all modes:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'mode[one_of]=standard&mode[one_of]=retrospective&mode[one_of]=test&mode[one_of]=tutorial'

To find just test incidents:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'mode[one_of]=test'


### By incident role

Roles and custom fields have another nested layer in the query parameter, to account for
operations against any of the roles or custom fields created in the account.

With incident role id=ABC, find all incidents where that role is unset:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'incident_role[ABC][is_set]=true'

Or where the role has been set:

		curl --get 'https://api.incident.io/v2/incidents' \
			--data 'incident_role[ABC][is_set]=false'

### By option custom fields

With an option custom field id=ABC, all incidents that have field ABC set to the custom
field option of id=XYZ:

		curl \
			--get 'https://api.incident.io/v2/incidents' \
			--data 'custom_field[ABC][one_of]=XYZ'

Or all incidents that do not have custom field id=ABC set to option id=XYZ:

		curl \
			--get 'https://api.incident.io/v2/incidents' \
			--data 'custom_field[ABC][not_in]=XYZ'
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV2.list({
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentsV2.<a href="/src/api/resources/incidentsV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.IncidentsCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new incident.

Note that if the incident mode is set to "retrospective" then the new incident
will not be announced in Slack.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV2.create({
    custom_field_entries: [{
            custom_field_id: "01FCNDV6P870EA6S7TK1DSYDG0",
            values: [{
                    id: "01FCNDV6P870EA6S7TK1DSYDG0",
                    value_catalog_entry_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                    value_link: "https://google.com/",
                    value_numeric: "123.456",
                    value_option_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                    value_text: "This is my text field, I hope you like it",
                    value_timestamp: ""
                }]
        }],
    idempotency_key: "alert-uuid",
    incident_role_assignments: [{
            assignee: {
                email: "bob@example.com",
                id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                slack_user_id: "USER123"
            },
            incident_role_id: "01FH5TZRWMNAFB0DZ23FD1TV96"
        }],
    incident_status_id: "01G0J1EXE7AXZ2C93K61WBPYEH",
    incident_timestamp_values: [{
            incident_timestamp_id: "01FCNDV6P870EA6S7TK1DSYD5H",
            value: "2021-08-17T13:28:57Z"
        }],
    incident_type_id: "01FH5TZRWMNAFB0DZ23FD1TV96",
    mode: "standard",
    name: "Our database is sad",
    retrospective_incident_options: {
        external_id: 123,
        postmortem_document_url: "https://docs.google.com/my_doc_id",
        slack_channel_id: "abc123"
    },
    severity_id: "01FH5TZRWMNAFB0DZ23FD1TV96",
    slack_channel_name_override: "inc-123-database-down",
    slack_team_id: "T02A1FSLE8J",
    summary: "Our database is really really sad, and we don't know why yet.",
    visibility: "public"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentsV2.<a href="/src/api/resources/incidentsV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.IncidentsShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single incident.

The ID supplied can be either the incident's full ID, or the numeric part of its
reference. For example, to get INC-123, you could use either its full ID or:

		curl \
			--get 'https://api.incident.io/v2/incidents/123
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV2.show({
    id: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.incidentsV2.<a href="/src/api/resources/incidentsV2/client/Client.ts">edit</a>({ ...params }) -> IncidentIO.IncidentsEditResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Edit an existing incident.

This endpoint allows you to edit the properties of an existing incident: e.g. set the severity or update custom fields.

When using this endpoint, only fields that are provided will be edited (omitted fields
will be ignored).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.incidentsV2.edit({
    id: "01G18REBY9AYH6CMWCJ2CVCYCH",
    incident: {
        call_url: "https://zoom.us/foo",
        custom_field_entries: [{
                custom_field_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                values: [{
                        id: "01FCNDV6P870EA6S7TK1DSYDG0",
                        value_catalog_entry_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                        value_link: "https://google.com/",
                        value_numeric: "123.456",
                        value_option_id: "01FCNDV6P870EA6S7TK1DSYDG0",
                        value_text: "This is my text field, I hope you like it",
                        value_timestamp: ""
                    }]
            }],
        incident_role_assignments: [{
                assignee: {
                    email: "bob@example.com",
                    id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                    slack_user_id: "USER123"
                },
                incident_role_id: "01FH5TZRWMNAFB0DZ23FD1TV96"
            }],
        incident_status_id: "abc123",
        incident_timestamp_values: [{
                incident_timestamp_id: "01FCNDV6P870EA6S7TK1DSYD5H",
                value: "2021-08-17T13:28:57Z"
            }],
        name: "Our database is sad",
        severity_id: "01G0J1EXE7AXZ2C93K61WBPYEH",
        slack_channel_name_override: "inc-123-database-down",
        summary: "Our database is really really sad, and we don't know why yet."
    },
    notify_incident_channel: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.IncidentsEditPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `IncidentsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Schedules V2
<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">listscheduleentries</a>({ ...params }) -> IncidentIO.SchedulesListScheduleEntriesResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a list of schedule entries. The endpoint will return all entries that overlap with the given window, if one is provided.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.listscheduleentries({
    schedule_id: "01FDAG4SAP5TYPT98WGR2N7W91",
    entry_window_start: "2021-01-01T00:00:00Z",
    entry_window_end: "2021-01-01T00:00:00Z"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesV2ListScheduleEntriesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">createoverride</a>({ ...params }) -> IncidentIO.SchedulesCreateOverrideResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new schedule override.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.createoverride({
    end_at: "2021-08-17T14:00:00Z",
    layer_id: "01G0J1EXE7AXZ2C93K61WBPYNH",
    rotation_id: "01G0J1EXE7AXZ2C93K61WBPYEH",
    schedule_id: "01G0J1EXE7AXZ2C93K61WBPYEH",
    start_at: "2021-08-17T13:00:00Z",
    user: {
        email: "bob@example.com",
        id: "01G0J1EXE7AXZ2C93K61WBPYEH",
        slack_user_id: "USER123"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesCreateOverridePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.SchedulesListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List configured schedules.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.list({
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">create</a>({ ...params }) -> IncidentIO.SchedulesCreateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new schedule.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.create({
    schedule: {
        annotations: {
            "incident.io/terraform/version": "version-of-terraform"
        },
        config: {
            rotations: [{
                    effective_from: "2021-08-17T13:28:57Z",
                    handover_start_at: "2021-08-17T13:28:57Z",
                    handovers: [{
                            interval: 1,
                            interval_type: "hourly"
                        }],
                    id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                    layers: [{
                            id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                            name: "Layer 1"
                        }],
                    name: "My Rotation",
                    scheduling_mode: "fair",
                    users: [{
                            email: "bob@example.com",
                            id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                            slack_user_id: "USER123"
                        }],
                    working_interval: [{
                            end_time: "17:00",
                            start_time: "09:00",
                            weekday: "monday"
                        }]
                }]
        },
        holidays_public_config: {
            country_codes: ["abc123"]
        },
        name: "Primary On-call Schedule",
        team_ids: ["01JPQA75EPNEES4479P16P4XAB"],
        timezone: "America/Los_Angeles"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesCreatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.SchedulesShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single schedule.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.show({
    id: "01G0J1EXE7AXZ2C93K61WBPYEH"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">update</a>({ ...params }) -> IncidentIO.SchedulesUpdateResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update a schedule.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.update({
    id: "01G0J1EXE7AXZ2C93K61WBPYEH",
    schedule: {
        annotations: {
            "incident.io/terraform/version": "version-of-terraform"
        },
        config: {
            rotations: [{
                    effective_from: "2021-08-17T13:28:57Z",
                    handover_start_at: "2021-08-17T13:28:57Z",
                    handovers: [{
                            interval: 1,
                            interval_type: "hourly"
                        }],
                    id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                    layers: [{
                            id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                            name: "Layer 1"
                        }],
                    name: "My Rotation",
                    scheduling_mode: "fair",
                    users: [{
                            email: "bob@example.com",
                            id: "01G0J1EXE7AXZ2C93K61WBPYEH",
                            slack_user_id: "USER123"
                        }],
                    working_interval: [{
                            end_time: "17:00",
                            start_time: "09:00",
                            weekday: "monday"
                        }]
                }]
        },
        holidays_public_config: {
            country_codes: ["abc123"]
        },
        name: "Primary On-call Schedule",
        team_ids: ["01JPQA75EPNEES4479P16P4XAB"],
        timezone: "America/Los_Angeles"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesUpdatePayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.schedulesV2.<a href="/src/api/resources/schedulesV2/client/Client.ts">destroy</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives a single schedule.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.schedulesV2.destroy({
    id: "01G0J1EXE7AXZ2C93K61WBPYEH"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.SchedulesV2DestroyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SchedulesV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Users V2
<details><summary><code>client.usersV2.<a href="/src/api/resources/usersV2/client/Client.ts">list</a>({ ...params }) -> IncidentIO.UsersListResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List users in your account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.usersV2.list({
    email: "john.doe@incident.io",
    slack_user_id: "U12345678",
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.UsersV2ListRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UsersV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.usersV2.<a href="/src/api/resources/usersV2/client/Client.ts">show</a>({ ...params }) -> IncidentIO.UsersShowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a single user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.usersV2.show({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.UsersV2ShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UsersV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Workflows V2
<details><summary><code>client.workflowsV2.<a href="/src/api/resources/workflowsV2/client/Client.ts">listworkflows</a>() -> IncidentIO.WorkflowsListWorkflowsResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all workflows
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workflowsV2.listworkflows();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `WorkflowsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.workflowsV2.<a href="/src/api/resources/workflowsV2/client/Client.ts">createworkflow</a>({ ...params }) -> IncidentIO.WorkflowsCreateWorkflowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new workflow
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workflowsV2.createworkflow({
    annotations: {
        "incident.io/terraform/version": "3.0.0"
    },
    condition_groups: [{
            conditions: [{
                    operation: "one_of",
                    param_bindings: [{
                            array_value: [{
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }],
                            value: {
                                literal: "SEV123",
                                reference: "incident.severity"
                            }
                        }],
                    subject: "incident.severity"
                }]
        }],
    continue_on_step_error: true,
    delay: {
        conditions_apply_over_delay: false,
        for_seconds: 60
    },
    expressions: [{
            else_branch: {
                result: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            },
            label: "Team Slack channel",
            operations: [{
                    branches: {
                        branches: [{
                                condition_groups: [{
                                        conditions: [{
                                                operation: "one_of",
                                                param_bindings: [{
                                                        array_value: [{
                                                                literal: "SEV123",
                                                                reference: "incident.severity"
                                                            }],
                                                        value: {
                                                            literal: "SEV123",
                                                            reference: "incident.severity"
                                                        }
                                                    }],
                                                subject: "incident.severity"
                                            }]
                                    }],
                                result: {
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }
                            }],
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        }
                    },
                    concatenate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    filter: {
                        condition_groups: [{
                                conditions: [{
                                        operation: "one_of",
                                        param_bindings: [{
                                                array_value: [{
                                                        literal: "SEV123",
                                                        reference: "incident.severity"
                                                    }],
                                                value: {
                                                    literal: "SEV123",
                                                    reference: "incident.severity"
                                                }
                                            }],
                                        subject: "incident.severity"
                                    }]
                            }]
                    },
                    navigate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    operation_type: "navigate",
                    parse: {
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        },
                        source: "metadata.annotations[\"github.com/repo\"]"
                    }
                }],
            reference: "abc123",
            root_reference: "incident.status"
        }],
    folder: "My folder 01",
    include_private_escalations: true,
    include_private_incidents: true,
    name: "My little workflow",
    once_for: ["incident.url"],
    runs_on_incident_modes: ["standard", "test", "retrospective"],
    runs_on_incidents: "newly_created",
    shortform: "page-the-ceo",
    state: "active",
    steps: [{
            for_each: "abc123",
            id: "abc123",
            name: "pagerduty.escalate",
            param_bindings: [{
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }]
        }],
    trigger: "incident.updated"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.WorkflowsCreateWorkflowPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkflowsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.workflowsV2.<a href="/src/api/resources/workflowsV2/client/Client.ts">showworkflow</a>({ ...params }) -> IncidentIO.WorkflowsShowWorkflowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a workflow by ID
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workflowsV2.showworkflow({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    skip_step_upgrades: false
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.WorkflowsV2ShowWorkflowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkflowsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.workflowsV2.<a href="/src/api/resources/workflowsV2/client/Client.ts">updateworkflow</a>({ ...params }) -> IncidentIO.WorkflowsUpdateWorkflowResultV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a workflow
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workflowsV2.updateworkflow({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    annotations: {
        "incident.io/terraform/version": "3.0.0"
    },
    condition_groups: [{
            conditions: [{
                    operation: "one_of",
                    param_bindings: [{
                            array_value: [{
                                    literal: "SEV123",
                                    reference: "incident.severity"
                                }],
                            value: {
                                literal: "SEV123",
                                reference: "incident.severity"
                            }
                        }],
                    subject: "incident.severity"
                }]
        }],
    continue_on_step_error: true,
    delay: {
        conditions_apply_over_delay: false,
        for_seconds: 60
    },
    expressions: [{
            else_branch: {
                result: {
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }
            },
            label: "Team Slack channel",
            operations: [{
                    branches: {
                        branches: [{
                                condition_groups: [{
                                        conditions: [{
                                                operation: "one_of",
                                                param_bindings: [{
                                                        array_value: [{
                                                                literal: "SEV123",
                                                                reference: "incident.severity"
                                                            }],
                                                        value: {
                                                            literal: "SEV123",
                                                            reference: "incident.severity"
                                                        }
                                                    }],
                                                subject: "incident.severity"
                                            }]
                                    }],
                                result: {
                                    array_value: [{
                                            literal: "SEV123",
                                            reference: "incident.severity"
                                        }],
                                    value: {
                                        literal: "SEV123",
                                        reference: "incident.severity"
                                    }
                                }
                            }],
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        }
                    },
                    concatenate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    filter: {
                        condition_groups: [{
                                conditions: [{
                                        operation: "one_of",
                                        param_bindings: [{
                                                array_value: [{
                                                        literal: "SEV123",
                                                        reference: "incident.severity"
                                                    }],
                                                value: {
                                                    literal: "SEV123",
                                                    reference: "incident.severity"
                                                }
                                            }],
                                        subject: "incident.severity"
                                    }]
                            }]
                    },
                    navigate: {
                        reference: "catalog_attribute[\"01FCNDV6P870EA6S7TK1DSYD5H\"]"
                    },
                    operation_type: "navigate",
                    parse: {
                        returns: {
                            array: true,
                            type: "IncidentStatus"
                        },
                        source: "metadata.annotations[\"github.com/repo\"]"
                    }
                }],
            reference: "abc123",
            root_reference: "incident.status"
        }],
    folder: "My folder 01",
    include_private_escalations: true,
    include_private_incidents: true,
    name: "My little workflow",
    once_for: ["incident.url"],
    runs_on_incident_modes: ["standard", "test", "retrospective"],
    runs_on_incidents: "newly_created",
    shortform: "page-the-ceo",
    state: "active",
    steps: [{
            for_each: "abc123",
            id: "abc123",
            name: "pagerduty.escalate",
            param_bindings: [{
                    array_value: [{
                            literal: "SEV123",
                            reference: "incident.severity"
                        }],
                    value: {
                        literal: "SEV123",
                        reference: "incident.severity"
                    }
                }]
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.WorkflowsUpdateWorkflowPayloadV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkflowsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.workflowsV2.<a href="/src/api/resources/workflowsV2/client/Client.ts">destroyworkflow</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives a workflow
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workflowsV2.destroyworkflow({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.WorkflowsV2DestroyWorkflowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkflowsV2Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Catalog V3
<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">listentries</a>({ ...params }) -> IncidentIO.CatalogListEntriesResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List entries for a catalog type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.listentries({
    catalog_type_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    page_size: 25,
    after: "01FDAG4SAP5TYPT98WGR2N7W91",
    identifier: "abc123"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV3ListEntriesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">createentry</a>({ ...params }) -> IncidentIO.CatalogCreateEntryResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an entry within the catalog. We support a maximum of 50,000 entries per type.

If you call this API with a payload where the external_id and catalog_type_id match an existing entry, the existing entry will be updated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.createentry({
    aliases: ["lawrence@incident.io", "lawrence"],
    attribute_values: {
        "abc123": {
            array_value: [{
                    literal: "SEV123"
                }],
            value: {
                literal: "SEV123"
            }
        }
    },
    catalog_type_id: "01FCNDV6P870EA6S7TK1DSYDG0",
    external_id: "761722cd-d1d7-477b-ac7e-90f9e079dc33",
    name: "Primary On-call",
    rank: 3
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogCreateEntryPayloadV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">bulkupdateentries</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update multiple catalog entries in a single operation. You can update up to 250 entries at once. This operation is atomic - either all entries are updated successfully, or none are updated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.bulkupdateentries({
    catalog_type_id: "01GW2G3V0S59R238FAHPDS1R66",
    entries: [{
            aliases: ["abc123"],
            attribute_values: {
                "abc123": {
                    array_value: [{
                            literal: "SEV123"
                        }],
                    value: {
                        literal: "SEV123"
                    }
                }
            },
            entry_id: "abc123",
            external_id: "abc123",
            name: "abc123",
            rank: 1
        }, {
            aliases: ["abc123"],
            attribute_values: {
                "abc123": {
                    array_value: [{
                            literal: "SEV123"
                        }],
                    value: {
                        literal: "SEV123"
                    }
                }
            },
            entry_id: "abc123",
            external_id: "abc123",
            name: "abc123",
            rank: 1
        }],
    update_attributes: ["01GW2G3V0S59R238FAHPDS1R66", "01GW2G3V0S59R238FAHPDS1R67"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogBulkUpdateEntriesPayloadV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">showentry</a>({ ...params }) -> IncidentIO.CatalogShowEntryResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a single catalog entry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.showentry({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV3ShowEntryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">updateentry</a>({ ...params }) -> IncidentIO.CatalogUpdateEntryResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an existing catalog entry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.updateentry({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    aliases: ["lawrence@incident.io", "lawrence"],
    attribute_values: {
        "abc123": {
            array_value: [{
                    literal: "SEV123"
                }],
            value: {
                literal: "SEV123"
            }
        }
    },
    external_id: "761722cd-d1d7-477b-ac7e-90f9e079dc33",
    name: "Primary On-call",
    rank: 3,
    update_attributes: ["abc123"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogUpdateEntryPayloadV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">destroyentry</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives a catalog entry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.destroyentry({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV3DestroyEntryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">listresources</a>() -> IncidentIO.CatalogListResourcesResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List available engine resources for the catalog.

A resource represents a type of data that can be held within the catalog, so this
endpoint can be used to see what attribute types can be used when updating the
schema of a catalog type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.listresources();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">listtypes</a>() -> IncidentIO.CatalogListTypesResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List all catalog types for an organisation, including those synced from external resources.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.listtypes();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">createtype</a>({ ...params }) -> IncidentIO.CatalogCreateTypeResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a catalog type. The schema must be updated using the UpdateTypeSchema endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.createtype({
    annotations: {
        "incident.io/catalog-importer/id": "id-of-config"
    },
    categories: ["customer"],
    color: "yellow",
    description: "Represents Kubernetes clusters that we run inside of GKE.",
    icon: "alert",
    name: "Kubernetes Cluster",
    ranked: true,
    source_repo_url: "https://github.com/my-company/incident-io-catalog",
    type_name: "Custom[\"BackstageGroup\"]",
    use_name_as_identifier: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogCreateTypePayloadV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">showtype</a>({ ...params }) -> IncidentIO.CatalogShowTypeResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Show a single catalog type.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.showtype({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV3ShowTypeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">updatetype</a>({ ...params }) -> IncidentIO.CatalogUpdateTypeResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an existing catalog type. The schema must be updated using the UpdateTypeSchema endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.updatetype({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    annotations: {
        "incident.io/catalog-importer/id": "id-of-config"
    },
    categories: ["customer"],
    color: "yellow",
    description: "Represents Kubernetes clusters that we run inside of GKE.",
    icon: "alert",
    name: "Kubernetes Cluster",
    ranked: true,
    source_repo_url: "https://github.com/my-company/incident-io-catalog",
    use_name_as_identifier: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogUpdateTypePayloadV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">destroytype</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Archives a catalog type and associated entries.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.destroytype({
    id: "01FCNDV6P870EA6S7TK1DSYDG0"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogV3DestroyTypeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalogV3.<a href="/src/api/resources/catalogV3/client/Client.ts">updatetypeschema</a>({ ...params }) -> IncidentIO.CatalogUpdateTypeSchemaResultV3</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing catalog types schema, adding or removing attributes.

Updating the schema is handled separately from creating and updating types, so that you don't
have to worry about dependencies between types. For example, if type A has an attribute that
relies on type B, you would have to create type B first.

By allowing the creation of types without a schema, they can be created in any order, but it
means that you need to make a separate call to this endpoint to update the schema.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.catalogV3.updatetypeschema({
    id: "01FCNDV6P870EA6S7TK1DSYDG0",
    attributes: [{
            array: false,
            backlink_attribute: "abc123",
            id: "01GW2G3V0S59R238FAHPDS1R66",
            mode: "",
            name: "tier",
            path: [{
                    attribute_id: "abc123"
                }],
            type: "Custom[\"Service\"]"
        }],
    version: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `IncidentIO.CatalogUpdateTypeSchemaPayloadV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CatalogV3Client.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>
