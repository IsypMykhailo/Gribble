# Gribble - Educational Institution Management Platform

Gribble is a modular **High Schools, Colleges, and Universities Management Platform**, designed to handle various aspects of educational institution administration efficiently. This repository serves as an **aggregator** for different microservices, each managed in separate submodules.

Each service is managed in its own **Git submodule**, enabling independent development and deployment.

---

## 📂 **Repository Structure**
This repository does not contain direct source code but instead organizes and links to multiple submodules. To initialize the project correctly, follow the setup instructions below.

### **Submodules**
| Submodule | Description |
|-----------|------------|
| `web` | Frontend |
| `NotificationService` | Handles in-app notifications |
| `OAuthService` | Handles authentication and user management |
| `SchedulerService` | Handles most of the functionality |
| `HomeworkService` | Handles homeworks |

---

## 🛠 **Setup Instructions**
Since this repository uses submodules, ensure you clone it with all dependencies properly.

### **1️⃣ Clone with Submodules**
```bash
 git clone --recurse-submodules https://github.com/IsypMykhailo/Gribble.git
 cd Gribble
```

### **2️⃣ Initialize and Update Submodules (If Already Cloned)**
```bash
git submodule update --init --recursive
```

### **3️⃣ Pull the Latest Updates**
Whenever submodules are updated, run:
```bash
git submodule update --remote --merge
```
