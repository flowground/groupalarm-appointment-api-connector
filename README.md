# ![LOGO](logo.png) groupalarm Appointment API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Appointment API API (version 1.16.3).

Generated from: https://app.groupalarm.com/api/v1<br/>
Generated at: 2019-07-26T13:59:32+03:00

## API Description

The appointment service implements all appointment and reminder functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### CreateAppointment
> Create an appointment with the passed parameters<br/>

*Tags:* `appointment`

### GetAppointment
> Get specific appointment with the requested id<br/>

*Tags:* `appointment`

#### Input Parameters
* `id` - _required_ - id of an appointment<br/>

### UpdateAppointment
> Update an appointment with the passed parameters<br/>

*Tags:* `appointment`

#### Input Parameters
* `id` - _required_ - id of an appointment<br/>

### DeleteAppointment
> Deletes the appointment with the passed id<br/>

*Tags:* `appointment`

#### Input Parameters
* `id` - _required_ - id of an appointment<br/>

### UpdateAppointmentParticipantFeedback
> Update an appointment with the passed parameters<br/>

*Tags:* `appointment`

#### Input Parameters
* `id` - _required_ - id of an appointment<br/>

### GetPersonalAppointments
> Get paginated personal appointments<br/>

*Tags:* `appointments`

#### Input Parameters
* `limit` - _optional_ - max. amount of entries in list<br/>
* `offset` - _optional_ - amount of entries to skip<br/>

### GetPersonalICal
> Returns all personal appointments in ical/ics format<br/>

*Tags:* `appointments`

#### Input Parameters
* `token` - _required_ - token to access personal appointments<br/>

### UpsertPersonalToken
> Get personal ical token<br/>

*Tags:* `appointments`

### UpsertPersonalToken
> Creates or updates the personal ical token<br/>

*Tags:* `appointments`

#### Input Parameters
* `token` - _required_ - token to access personal appointments<br/>

### GetOrganizationAppointments
> Get paginated personal appointments<br/>

*Tags:* `appointments`

#### Input Parameters
* `organization` - _required_ - id of an organization<br/>
* `limit` - _optional_ - max. amount of entries in list<br/>
* `offset` - _optional_ - amount of entries to skip<br/>

## License

**flow**ground :- Telekom iPaaS / groupalarm-appointment-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
