#AWS #documentation 

**Amazon CloudFront** is a **Content Delivery Network (CDN)** service that securely delivers data, videos, applications, and APIs to users globally with low latency and high transfer speeds.

### 🔧 What CloudFront does:

- 📥 **Fetches content** from an origin server (like S3, EC2, or API Gateway).
    
- 📤 **Caches it** at edge locations around the world (close to end users).
    
- 🚀 **Delivers content** quickly and reliably by serving from the nearest edge.
    
- 🔐 **Secures access** with features like HTTPS, signed URLs, Origin Access Control (OAC), and AWS WAF.
    
- 📈 **Optimizes performance** with features like compression, caching policies, and custom error responses.

## Distribution

Step 1:
`Single website or app` one domain name for one website
`Multi-tenant architecture` group of domains with the same distribution setting that use the same files (website)

Step 2: 
Choose where files stored for example [[AWS S3]]

Step 3: 
Enable or disable WAF (Web Application Firewall)


