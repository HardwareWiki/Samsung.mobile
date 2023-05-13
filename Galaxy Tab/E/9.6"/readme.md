# Galaxy Tab E
# postmarketOS

## Variants:
- https://wiki.postmarketos.org/wiki/Samsung_Galaxy_Tab_E_9.6_(SM-T560)_(samsung-gtelwifi)
- https://wiki.postmarketos.org/wiki/Samsung_Galaxy_Tab_E_9.6_(SM-T561)_(samsung-gtel3g)

### **SM-T560NU - uses: LK2nd bootloader**
- https://wiki.postmarketos.org/wiki/Samsung_Galaxy_Tab_E_9.6_(SM-T560NU)_(samsung-gtelwifiue)
  - flash: https://wiki.postmarketos.org/wiki/Qualcomm_Snapdragon_410/412_(MSM8916)#Installation


wiki: https://en.wikipedia.org/wiki/Samsung_Galaxy_Tab_E_9.6

SoC:
- SM-T560NU: Qualcomm APQ8016

# Bootloader
status: works!
variant: lk2nd-msm8916.img
source: https://github.com/msm8916-mainline/lk2nd

command: `sudo ./heimdall flash --BOOT lk2nd-msm8916.img`
