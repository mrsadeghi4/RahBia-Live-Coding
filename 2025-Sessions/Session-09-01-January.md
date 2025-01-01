
# Rahbia Live Coding
### Organized by DockerMe group
  - **Speaker:** [Ahmad Rafiee](https://www.linkedin.com/in/ahmad-rafiee)
  - **Date:** 01 January 2025
  - **Number of Sessions:** 09 (Session 09)

### Video Link:
[![YouTube](http://i.ytimg.com/vi/amBjtXnUrT0/hqdefault.jpg)](https://www.youtube.com/live/amBjtXnUrT0)

### 🔴 Live Coding Session 9: GitLab Deployment on Docker with Ansible
In this session, we dive into deploying GitLab services on Docker using Ansible. Here's what we covered step by step:

# Live Coding Session: Advanced GitLab Configuration

This repository contains the steps and configurations demonstrated during my live coding session. The session covered various advanced GitLab configurations, including setting up the registry, SMTP, backups, and enhancing security.

## Topics Covered

### 1. **Setting Up GitLab Registry**
- Configured and enabled the GitLab container registry.
- Verified the external URL and functionality.

### 2. **SMTP Configuration**
- Set up SMTP for sending emails using GitLab.
- Verified the configuration through the GitLab admin interface.

### 3. **Backup Configuration**
- Configured GitLab's built-in backup system.
- Set a custom backup path and defined a retention period.
- Created cron jobs to automate backups.

### 4. **Backup Integration with MinIO**
- Connected MinIO for storing backups.
- Automated the process of uploading backups to MinIO via scripts and cron jobs.

### 5. **Disabling Unused Services**
- Disabled unnecessary services (e.g., Redis and PostgreSQL) to optimize resource usage.

### 6. **Custom Gitlab Nginx Configuration**
- Configured custom SSL certificates for GitLab.
- Added security headers like `X-Frame-Options` and `Strict-Transport-Security`.

### 7. **Authentication Security**
- Set up `fail2ban` to block IPs after repeated failed login attempts.
- Enhanced log monitoring for security purposes.

### 8. **Root Password Management**
- Securely updated the default root password via the GitLab console.

### 9. **Automated Cron Jobs**
- Scheduled automated backups at specific times.
- Automated backup uploads to MinIO storage.

---

## Key Highlights of the Session
- **Hands-on Approach:** All configurations were demonstrated live with step-by-step explanations.
- **Troubleshooting:** Addressed common issues encountered during setup.
- **Best Practices:** Discussed optimization and security best practices for GitLab.

---

#### Test if GitLab sends emails properly using the Rails console by executing the following commands. Replace USERNAME with your Gmail account username.
```bash
gitlab-rails console
irb(main):003:0> Notify.test_email('USERNAME@gmail.com', 'Message Subject', 'Message Body').deliver_now
```


📖 Whether you're just starting with Ansible or looking to improve your Docker and GitLab management skills, this session is for you!


## 🔗 Links
[![Site](https://img.shields.io/badge/Dockerme.ir-0A66C2?style=for-the-badge&logo=docker&logoColor=white)](https://dockerme.ir/)
[![YouTube](https://img.shields.io/badge/youtube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@dockerme)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-rafiee/)
[![Telegram](https://img.shields.io/badge/telegram-0A66C2?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/dockerme)
[![Instagram](https://img.shields.io/badge/instagram-FF0000?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/dockerme)