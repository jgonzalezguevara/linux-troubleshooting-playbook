# Disk Full Checklist

df -h

df -ih

du -xh / | sort -h | tail -50

lsof +L1

journalctl --disk-usage
