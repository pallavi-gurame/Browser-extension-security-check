# Browser-extension-security-check
Task to identify and remove potentially harmful browser extensions, documenting the process with screenshots and review notes.


# Objective
Identify and remove potentially harmful or unused browser extensions to improve browser security and performance.

# Environment
- Browser: Google Chrome
- OS: Windows 11

# Steps I Followed
1. Opened the Chrome Extensions Manager (`chrome://extensions/`).
2. Reviewed all installed extensions for purpose, permissions, developer, and usage.
3. Identified suspicious or unused extensions.
4. Removed the extension "FoxyProxy" as it was not needed and could pose a privacy/security risk.
5. Kept "Google Docs Offline" as it is official and safe.
6. Left "360 Internet Protection" disabled since it is linked to antivirus software and not actively used.
7. Restarted the browser and verified that performance was unaffected and no suspicious activity remained.

# Extensions Review Table

| Extension Name          | Purpose                                     | Risk Level | Action Taken | Reason |
|-------------------------|---------------------------------------------|------------|--------------|--------|
| 360 Internet Protection | Browser protection via antivirus plugin     | Medium     | Disabled     | No longer using 360 antivirus actively |
| FoxyProxy               | Proxy management tool                       | Medium-High| Removed      | Not needed, potential privacy risk |
| Google Docs Offline     | Offline editing for Google Docs             | Low        | Kept         | Official Google extension, safe |

# Outcome
- 1 suspicious/unused extension removed.
- Browser is now free from unneeded proxy tools that could monitor traffic.
- Only essential and trusted extensions remain.

# Screenshots
1. screenshots/before-extensions.png
2. screenshots/after-extensions.png

# Best Practices Learned
- Always review permissions and developer information before installing extensions.
- Remove unused or suspicious extensions to reduce attack surface.
- Keep browser and extensions updated from official sources only.
