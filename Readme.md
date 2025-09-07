```bash
# Create a Pixel Android Device
avdmanager create avd -n Pixel_6_API_34 -k "system-images;android-34;google_apis;x86_64" --device "pixel_6"

# Use it
emulator -avd Pixel_6_API_34

```
