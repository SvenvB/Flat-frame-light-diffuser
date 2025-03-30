# Flat Frame Light Diffuser for the Orion SpaceProbe 130ST
A simple white light source and custom mount for capturing flat frames with the Orion SpaceProbe 130ST telescope. Most of the materials I had lying around, but you can likely build it for around **$15**.

I'm using the [Orion SpaceProbe 130ST telescope](https://www.highpointscientific.com/orion-spaceprobe-130st-short-tube-eq-reflector-telescope) with a [ZWO ASI224MC](https://www.zwoastro.com/product/zwo-asi224mc/) CMOS imaging camera, and I enjoy deep-sky imaging without breaking the bank.

While dark frames are easy to take with the dust cap on, I was looking for a convenient and budget-friendly way to make **flat frames**. I usually shoot early in the evening and don't have twilight available. While placing a white t-shirt over the telescope and using a [laptop screen](https://practicalastrophotography.com/a-brief-guide-to-calibration-frames/) is one option, I wanted a more straightforward and reusable solution. Hence, this flat frame light diffuser for the Orion SpaceProbe 130ST.



---

## Materials

* **Flexible 12V LED strip** – Ideally, use white LEDs with a balanced spectrum. I used this [AliExpress LED strip](https://www.aliexpress.us/item/3256803152712901.html) I already had (probably not ideal for high fidelity calibration).
* **2× 1/4" round plexiglass sheets, 6-inch diameter** – [Example](https://www.amazon.com/dp/B09ZSYX99P). You could also use an opaque acrylic sheet to avoid needing a t-shirt for diffusion. You can use only one (thicker) sheet, just make sure that your LED strips will fit on the perimeter.
* **White t-shirt** – For diffusing light (if you're using clear plexiglass).
* **Flexible plastic sheet** – To protect the t-shirt from getting dirty and to allow for easy cleaning.
* **Aluminum tape** – [Link](https://www.amazon.com/dp/B0B6NDFXPN) - to reflect and contain light.
* **12V DC power source** – I used this [8×AA battery holder with DC barrel jack](https://www.amazon.com/DKARDU-Battery-Holder-Plastic-Arduino/dp/B09PH35NNX) that I already had for my EQ-mount motor.
* **Female DC barrel jack** – [Link](https://www.amazon.com/California-JOS-Breadboard-Friendly-Mounting-Female/dp/B09ZBN38FS)
* **3D printer and filament**
* **4× M4×16mm bolts + nuts**

---

## Instructions

### 1. Cut the LED strip

Stack the two acrylic sheets and cut the LED strip to the correct length. I used two sheets so the height of the resulting cylinder would be greater than the width of the LED strip.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/1_Plexiglass_6in.jpg" width="400">
<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/2_Measure_LED_strip.jpg" width="400">

---

### 2. Apply the aluminum tape

Neatly apply aluminum tape to one side of the stack. Try to keep it flat to avoid wrinkles and light hotspots. Cut the tape long enough so that it can wrap around the sides and help secure the LED strip.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/3_Apply_tape.jpg" width="400">
<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/4_Apply_tape.jpg" width="400">

---

### 3. Tape the LED strip

Attach the LED strip to the side of the acrylic stack using the aluminum tape.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/5_Tape_LED_strip.jpg" width="400">

---

### 4. Trim excess tape

Trim any excess tape from the top of the acrylic sheets using a knife.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/6_Remove_tape_on_top.jpg" width="400">

---

### 5. Solder the power cable

Solder the power cable to the LED strip. The cable only needs to be a few centimeters long since the female DC jack will be integrated into the mount. Also solder the female power jack.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/7_Solder_power_cable.jpg" width="400">

---

### 6. Attach the white t-shirt

This step might not be necessary if you’re using opaque acrylic sheets. For clear sheets, use a white t-shirt to diffuse the light. Cut it into a square or circle, stretch it over the diffuser, and secure it using aluminum tape on the backside. I used two layers of t-shirt to improve diffusion.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/8_Cut_white_cloth.jpg" width="400">
<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/9_Test_diffusion_quality.jpg" width="400">

---

### 7. Make and install the mount

3D print the [mount](https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/CAD/CE3E3V2_FlatFrameDiffuser-Mount.gcode) and apply aluminum tape around the inner rim to reflect light from the LEDs, as shown below.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/10_Tape_Rim_Diffuser_Casing.jpg" width="400">

Cut a thin plastic sheet in a circle that will fit in the mount, to protect the white t-shirt from getting dirty. Then mount the diffuser into the printed part. I used a hot glue gun to secure the female DC power jack in place.

<img src="https://github.com/SvenvB/Flat-frame-light-diffuser/blob/main/Photos/11_Mount_Light_Diffuser.jpg" width="400">
