# Smart India Hackathon Workshop
## Register Number:212224240150
## Name: Sharveshwaran M
## Problem Title
SIH 1392 - E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
Background: Improper disposal of electronic waste (e-waste) is a growing environmental and public health concern. E-waste contains harmful components such as lead, mercury, cadmium, and brominated flame retardants, which can contaminate soil, water, and air if not disposed of properly. Many people are unaware of nearby e-waste collection and recycling facilities, leading to unsafe disposal practices. A system that informs users about proper e-waste disposal and incentivizes responsible behavior can significantly reduce environmental harm
Description: The problem involves developing a comprehensive digital solution that helps users locate the nearest e-waste collection and recycling facilities. The platform should provide educational information about the hazardous components of e-waste and their effects on the environment and human health. Users should also be able to input details of their old electronic devices and earn credits based on the value of precious metals recovered if disposed of correctly.

Expected Solution: 
The expected solution is a multi-platform system that:
Provides a location-based service to find nearby e-waste collection points.
Offers interactive educational pop-ups detailing the environmental and health impact of e-waste.
Allows users to input device models and estimate recovered precious metals, earning incentive points.
Integrates with government or NGO programs to encourage proper disposal.
Provides notifications and reminders for e-waste disposal drives.


## Problem Creater's Organization
Ministry of Environment

## Idea
Develop a platform that combines geolocation services, educational content, and user incentives to promote proper e-waste disposal.

## Proposed Solution / Architecture Diagram

![WhatsApp Image 2025-10-07 at 16 00 53_b66bf3d5](https://github.com/user-attachments/assets/f9a89a8d-dfd4-4ef1-8926-91b49ce82bc9)

<img width="1536" height="1024" alt="ChatGPT Image Apr 22, 2026, 04_08_25 PM" src="https://github.com/user-attachments/assets/d5fd564a-a780-497c-ad91-41170a33790f" />

Architecture Components:

User Interface (UI) – Web and Mobile App for users to search facilities, view educational content, and track credits.

Geolocation Module – Detects the user's location and suggests nearby e-waste facilities.

Database – Stores facility information, device models, hazardous component data, and user credit points.
Educational Content Engine – Provides pop-ups and interactive material about e-waste hazards.

Incentive Module – Calculates credits based on device input and precious metal recovery.

Admin Panel – Facility managers and government bodies can update locations, campaigns, and educational resources.

## Use Cases 

Locate Facility: User opens the app → system displays nearest e-waste collection points.

Learn about E-Waste: User clicks on a device type → pop-up shows harmful components and risks.

Earn Credits: User inputs old device model → system calculates potential credits based on precious metals.

Receive Notifications: User receives reminders about upcoming e-waste drives or campaigns.

## Technology Stack

Frontend: React.js, Flutter for mobile apps

Backend: Node.js / Django

Database: PostgreSQL / MongoDB

Geolocation Services: Google Maps API / OpenStreetMap

Notifications: Firebase Cloud Messaging / Twilio

Cloud Hosting: AWS / Azure / GCP


## Dependencies

Accurate and updated facility data from local authorities or certified e-waste recyclers

Device database with material composition and precious metal content

Government or NGO support for incentive program integration
