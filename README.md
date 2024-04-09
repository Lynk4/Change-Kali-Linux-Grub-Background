# Change-Kali-Linux-Grub-Background

I'm using a kali linux machine on a vmware fusion .

## ***Final Results***

---

<img width="1440" alt="Screenshot 2024-04-10 at 12 56 23 AM" src="https://github.com/Lynk4/Change-Kali-Linux-Grub-Background/assets/44930131/f93672a8-52ef-4418-8701-c6bba722c4db">

---

<img width="1440" alt="Screenshot 2024-04-10 at 12 56 33 AM" src="https://github.com/Lynk4/Change-Kali-Linux-Grub-Background/assets/44930131/bea99a35-60e8-423e-86e8-26bf6b018baa">

---


So basically we need three images..
I'll provide the images that I have used.

Also we have take consider of the dimensions of the images.

1) background_ii.png  - background_ii.png: PNG image data, 1920 x 1080, 8-bit/color RGBA, non-interlaced
2) grub-16x9.png  - grub-16x9.png: PNG image data, 1920 x 1080, 8-bit/color RGBA, non-interlaced
3) grub-4x3.png   - grub-4x3.png: PNG image data, 1440 x 1080, 8-bit/color RGBA, non-interlaced

#### To customize grub-background make sure you are a root user.

Now then we shall proceed.

### 1. Firstly place background_ii.png in ```/boot/grub``` directory.

---


<img width="1191" alt="Screenshot 2024-04-10 at 1 20 34 AM" src="https://github.com/Lynk4/Change-Kali-Linux-Grub-Background/assets/44930131/06397ecb-65cc-4dbd-a8be-3700f12e4805">



---

### 2. Then replace grub-16x9.png and grub-4x3.png images with our own choice of images in ```/boot/grub/themes/kali``` directory

make sure that the replaced images have the same name as ***grub-16x9.png and grub-4x3.png***

---

<img width="1242" alt="Screenshot 2024-04-10 at 1 18 02 AM" src="https://github.com/Lynk4/Change-Kali-Linux-Grub-Background/assets/44930131/4eb57101-d0f6-4460-a54f-ba51c299b74f">

---

Now we are done. we just need to update the grub by running the command.

```
sudo update-grub
```

After completion of the command restart your machine.

That’s it............
---
