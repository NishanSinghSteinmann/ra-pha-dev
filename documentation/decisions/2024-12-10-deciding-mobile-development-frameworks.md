* **Status:** Proposed  
* **Last Updated:** 2024-12-10
* **Objective:** Choose the most suitable technology stack for building a new mobile application that maximizes efficiency, maintainability, and performance.

## Context & Problem Statement

The team is planning to develop a cross-platform mobile application. The choice between React Native, Flutter, and native development is critical as it will impact the development speed, application performance, and ease of maintenance. Each option has strengths and weaknesses, making the decision complex.

## Priorities & Constraints

* **Performance**: Ensure the app performs smoothly, especially for graphics-intensive features.  
* **Development Speed**: Optimize for faster time-to-market.  
* **Cross-Platform Capability**: Minimize duplicate work for iOS and Android.  
* **Developer Expertise**: Leverage existing skillsets within the team.  
* **Maintenance and Scalability**: Ensure long-term maintainability and ease of scaling.  
* **Ecosystem and Community Support**: Availability of resources, libraries, and community help.

## Considered Options

* **Option 1: React Native**  
  - Pros: Cross-platform support, large community, reusable components.  
  - Cons: 1. Performance can lag in complex UIs; reliance on native modules for certain features. 

* **Option 2: Flutter**  
  - Pros: Cross-platform, strong performance, consistent UI across devices, robust community support.  
  - Cons: Steeper learning curve, larger app sizes, less native feel for platform-specific features.  

* **Option 3: Native Development (IOS and Android)**  
  - Pros: Best performance, platform-specific customizations, long-term reliability.  
  - Cons: Requires two separate codebases, higher development time and costs.

* **Option 4: Native Development (IOS only)**  
  - Pros: Best performance, long-term reliability. Quick Start.
  - Cons: Will delay development of android app.

## Decision

**Chosen Option: [Option 4: Native (IOS only)]**

Swift allows best performance and consistency on IOS devices. Ignoring kotlin for now allows faster development speed and will suffice for a POC. Will also eliminate cross-plattform dependencies. 

### Expected Consequences

* Improved development efficiency with a single codebase for iOS.
* Long-term saving of migration to native application code.
* Lack of android support will limit number of possible users in short term scope.

### Revisiting this Decision

* Unlikely.
* If adroid becomes priority.
* If code development stagnates and faster crossplatform speed is absolutley essential for further growth.  

