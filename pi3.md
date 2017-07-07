#

# Steup

1. Installed latest pi3 thinclient software
1. Used builer ito install rdesktop
   - Setting - fix keyboard (US)
   - RPTC Config
      - Set TZ
      - condif rdesktop server
      - config rdesktop settings (to include USB devices)

   - Edit /opt/scripts/rdesktop.sh
      - add -u "" -p "" to rdesktop line
