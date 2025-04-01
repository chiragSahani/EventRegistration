

# Event Registration

This project is an **Events** app built using React.js, CSS, and HTML. The app allows users to view and register for different events.

## Features

- **No Active Event View**: Initially, the page displays a view indicating that no event is active.
- **Yet To Register View**: Displays when an event with `registrationStatus` as `YET_TO_REGISTER` is clicked.
- **Registered View**: Displays when an event with `registrationStatus` as `REGISTERED` is clicked.
- **Registrations Closed View**: Displays when an event with `registrationStatus` as `REGISTRATIONS_CLOSED` is clicked.

## Design Files

Refer to the following design files to understand the layout and structure of the app:

- [No Active Event View](https://assets.ccbp.in/frontend/content/react-js/events-no-active-event-view-output.png)
- [Yet To Register View](https://assets.ccbp.in/frontend/content/react-js/events-yet-to-register-view-output.png)
- [Registered View](https://assets.ccbp.in/frontend/content/react-js/events-registered-view-output.png)
- [Registrations Closed View](https://assets.ccbp.in/frontend/content/react-js/events-registrations-closed-view-output.png)

## Set Up Instructions

To set up the project locally, follow these steps:

1. Download dependencies by running `npm install`.
2. Start the app using `npm start`.

## Completion Instructions

The app must have the following functionalities:

- Initially display the [No Active Event View](https://assets.ccbp.in/frontend/content/react-js/events-no-active-event-view-output.png).
- Display the [Yet To Register View](https://assets.ccbp.in/frontend/content/react-js/events-yet-to-register-view-output.png) when an event with `YET_TO_REGISTER` status is clicked.
- Display the [Registered View](https://assets.ccbp.in/frontend/content/react-js/events-registered-view-output.png) when an event with `REGISTERED` status is clicked.
- Display the [Registrations Closed View](https://assets.ccbp.in/frontend/content/react-js/events-registrations-closed-view-output.png) when an event with `REGISTRATIONS_CLOSED` status is clicked.

The `Events` component is provided with `eventsList`, which consists of a list of event objects with the following properties:

| Key                | Data Type |
|--------------------|-----------|
| id                 | String    |
| imageUrl           | String    |
| name               | String    |
| location           | String    |
| registrationStatus | String    |

## Components Structure

Refer to the following component structure breakdown:

![Component Structure Breakdown](https://assets.ccbp.in/frontend/content/react-js/events-compoment-structure-breakdown.png)

## Implementation Files

Use these files to complete the implementation:

- `src/components/Events/index.js`
- `src/components/Events/index.css`
- `src/components/EventItem/index.js`
- `src/components/EventItem/index.css`
- `src/components/ActiveEventRegistrationDetails/index.js`
- `src/components/ActiveEventRegistrationDetails/index.css`

## Important Note

The following instructions are required for the tests to pass:

- The image for each event item should have the alt attribute value as **event**.

## Resources

### Image URLs

- [Yet to Register Image](https://assets.ccbp.in/frontend/react-js/events-register-img.png) - alt should be **yet to register**
- [Registered Image](https://assets.ccbp.in/frontend/react-js/events-regestered-img.png) - alt should be **registered**
- [Registrations Closed Image](https://assets.ccbp.in/frontend/react-js/events-registrations-closed-img.png) - alt should be **registrations closed**

### Colors

- Hex: #64748b
- Hex: #0967d2
- Hex: #323f4b
- Hex: #f8fafc
- Hex: #475569
- Hex: #ffffff
- Hex: #2dd4bf
- Hex: #3a4b63

### Font Families

- Roboto

