# Log Analysis Checklist

journalctl -p err -n 100 --no-pager

journalctl -b --no-pager

journalctl -b -1 --no-pager

dmesg -T | tail -100
