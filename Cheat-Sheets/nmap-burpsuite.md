# Nmap & Burp Suite Quick Reference

## Nmap Basics

```bash
nmap -sC -sV <target>
nmap -p- <target>
nmap -A <target>
```

## Nmap Output Tips

- Confirm open ports and exposed services
- Prioritize unusual services for deeper testing

## Burp Suite Workflow

1. Configure browser proxy to Burp
2. Intercept and inspect HTTP requests
3. Send interesting requests to Repeater
4. Use Intruder for controlled fuzzing

## Common Checks

- Authentication/session handling
- Input validation and injection points
- Access control on hidden endpoints
