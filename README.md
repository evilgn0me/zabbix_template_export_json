# zabbix_template_export_json
This script exports templates from zabbix as json.

# dependencies
This module requires py-zabbix and zabbix-api module.

# usage
  --url URL  
  --user USER
  --password PASSWORD
  --templates TEMPLATES
  --out-dir OUT_DIR

python zabbix_export.py --url http://zabbix.example.com --user Admin --password strongpassword
