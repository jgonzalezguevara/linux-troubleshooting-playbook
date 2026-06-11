# High CPU Checklist

## Load average

uptime

## Top CPU consumers

top

ps aux --sort=-%cpu | head -20

## Per-process details

pidstat 1 5

## Systemd failed services

systemctl --failed

## Kernel messages

dmesg -T | tail -100
