#AWS #documentation 
### 🔐 **AWS Permissions Boundaries

- **Permissions boundaries** are advanced IAM features that **limit the maximum permissions** a user or role can have.
    
- They **do not grant** permissions themselves — they only define the _upper limit_ of what is allowed.
    
- A user’s **effective permissions** are the intersection of:
    
    - Identity-based policies
        
    - Permissions boundary (if set)
        
    - Resource-based policies
        
    - Session policies
        
    - Service Control Policies (SCPs, if in an AWS Organization)
        
- **Explicit `Deny` in any policy** (boundary or otherwise) overrides all `Allow`s.
    

### ✅ Key Rule:

> A user can perform an action **only if all relevant policies allow it**, and **none explicitly deny it**.

---
