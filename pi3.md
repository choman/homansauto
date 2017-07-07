#

# Setup

1. Installed latest pi3 thin client software
1. Used builder ito install rdesktop
   - Setting - fix keyboard (US)
   - RPTC Config
      - Set TZ
      - config rdesktop server
      - config rdesktop settings (to include USB devices)

   - Edit /opt/scripts/rdesktop.sh
      - add -u "" -p "" to rdesktop line
