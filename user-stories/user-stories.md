# Airbnb Clone - User Stories  
*Translated from [Use Case Diagram](../use-case-diagram/AirBnB_UseCase_Diagram.png) to INVEST-compliant stories*  

---

## Core User Stories  

### 🧑‍💻 Guest Perspective  
1. **`US-001`** As a guest, I want to register using email or social login so I can access the platform  
   *Related Use Case: User Registration (Email/OAuth)*  

2. **`US-002`** As a guest, I want to search properties with filters (price, amenities) so I can find perfect matches  
   *Related Use Case: Search & Filter Listings*  

### � Host Perspective  
3. **`US-003`** As a host, I want to upload property photos with descriptions so I can attract more guests  
   *Related Use Case: Add Listing + Cloud Storage*  

4. **`US-004`** As a host, I want to receive automated payout notifications so I know when payments arrive  
   *Related Use Case: Payment Processing + Notifications*  

### 👨‍💼 Admin Perspective  
5. **`US-005`** As an admin, I want to remove inappropriate content with one click so I can maintain platform quality  
   *Related Use Case: Moderate Content*  

---

## Traceability  
| Story ID | Use Case Origin | Priority |
|----------|-----------------|----------|
| US-001   | User Registration | High     |
| US-002   | Search & Filter | Critical |
| US-003   | Add Listing      | High     |
| US-004   | Payment Processing | Medium  |
| US-005   | Admin Moderation | High     |

---

> **Format**: All stories follow the *"As a [role], I want [action] so that [benefit]"* template  
> **Location**: `user-stories/user-stories.md`  
> **Diagram Source**: `use-case-diagram/AirBnB_UseCase_Diagram.puml`