# Out Of Memory Checklist

free -h

ps aux --sort=-%mem | head -20

swapon --show

dmesg -T | grep -i oom

journalctl -p err -n 100 --no-pager
