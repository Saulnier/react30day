# Adam's Website

## The Beginning

And so we start!

```
func (gnc *gnc) fortniteDrop(w http.ResponseWriter, r *http.Request) {
	landingZone := randomLandingZone()
	w.Header().Set("Content-Type", "image/png")
	w.Header().Set("Content-Length", "1000")
	gnc.writeLandingZoneImage(landingZone, w)
	// Save landing zone
}
```

