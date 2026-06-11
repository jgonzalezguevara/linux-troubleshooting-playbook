# Systemd Service Checklist

systemctl --failed

systemctl status SERVICE_NAME --no-pager

journalctl -u SERVICE_NAME -n 100 --no-pager

journalctl -u SERVICE_NAME -f

systemctl cat SERVICE_NAME
