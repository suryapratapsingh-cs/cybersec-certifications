# Linux Privilege Escalation Cheat Sheet

## System Info

```bash
uname -a
cat /etc/os-release
id
whoami
hostname
```

## SUID Binaries

```bash
find / -perm -4000 -type f 2>/dev/null
```

### Notes

- Check unusual SUID binaries against GTFOBins
- Review permissions and potential path hijacking opportunities

## Sudo Privileges

```bash
sudo -l
```

### Notes

- Identify commands runnable without password
- Check for shell escapes in allowed binaries
