# Leaflet 0.7.7 with patches applied by Windy.com
This is Windy's version of Leaflet library containing some tweaks

## CHANGELOG of patches
### 1.0.0 - 2017/11
- Added ability to fix zoom center in doubleTap zoom and pinch zoom (to be used in connection with mobile picker). Use `L.Map` methods `setZoomCenter(x,y)` and `removeZoomCenter` where x,y are container points
- New `L.Map` options `longTapTimeout` (set by default to 500ms)

