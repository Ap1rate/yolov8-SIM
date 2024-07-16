# SSWnet-yolo
Camouflaged Detection: Optimization-Based Computer Vision for Alligator sinensis with Low Detectability in Complex Wild Environments

![image](https://github.com/user-attachments/assets/fcb1f77e-857a-49cf-a8f6-9a0978146b53)


# Introduction
Abstract
The Alligator sinensis is among the world's rarest wild animals, often camouflaged to blend seamlessly with its natural habitat. This camouflage complicates detection efforts by both humans and automated systems, underscoring the urgent need for advanced wildlife monitoring technologies. To address this, we introduce YOLO v8-SIM, a novel detection method designed to significantly boost identification accuracy. The YOLO v8-SIM employs an advanced dual-layer attention mechanism, a refined Inner-IoU optimized loss function, and a Slim Neck cross-layer hopping technique. Our findings indicate that the model achieves a precision of 91%, a recall of 89.9%, and a mean average precision (mAP) of 92.3% at an IoU threshold of 0.5, with a frame rate of 72.21 FPS, excelling in detecting partially visible or smaller objects. Further enhancing our efforts, we propose an open-source dataset featuring camouflaged Alligator sinensis in their natural habitat. These advancements collectively contribute to the improved detection of camouflaged species, thereby advancing biodiversity monitoring and protection and aiding ecosystem sustainability. 



# Algorithmic Network Module Diagram
![Image 1](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/618b741a-8d96-4797-a358-d8d2836e1583)

<p style="text-align:center;"><a href="#"><img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0 0 24 24'%3E%3Cpath%20d='M12 8l-6 6 1.41 1.41L12 10.83l4.59 4.58L18 14z'/%3E%3C/svg%3E" alt="Down Arrow" width="24" height="24" /></a></p>

![Image 2](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/4e496116-1438-4358-ac37-de0bb556425c)

<p style="text-align:center;"><a href="#"><img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0 0 24 24'%3E%3Cpath%20d='M12 8l-6 6 1.41 1.41L12 10.83l4.59 4.58L18 14z'/%3E%3C/svg%3E" alt="Down Arrow" width="24" /></a></p>

![Image 3](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/56d8f553-ef4a-4dde-8320-d09a02f54cab)

<p style="text-align:center;"><a href="#"><img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0 0 24 24'%3E%3Cpath%20d='M12 8l-6 6 1.41 1.41L12 10.83l4.59 4.58L18 14z'/%3E%3C/svg%3E" alt="Down Arrow" width="24" height="24" /></a></p>

![Image 4](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/6657a793-0512-4bec-ab4b-14c9702dd425)
# Performance
Single Scale Inference on VGA resolution（max side is equal to 640 and scale).

![1720294869401](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/6a81066a-acb8-44cd-b647-27e0db51ea95)
# datasets
![1720295365537](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/d3ef968a-152b-470a-a492-23c42faca337)

# install
```bash
git clone https://github.com/SSWnet-yolo  # clone
cd SSWnet-yolo
pip install -r requirements.txt  # install
```
# run
```bash
python3 test_widerface.py --weights 'your test model' --img-size 640
cd widerface_evaluate
python3 evaluation.py
```
# Experimental Configuration
![image](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/b3fbfb47-f201-4292-8e59-73f631dc63d9)

# test
![1720294833476](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/27340f78-7d51-4101-8129-98ba78c19fe5)
![1720294874768](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/eefc89b8-dd3a-4ab6-92a0-3016313ef007)
![1720294892330](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/26fc9e0b-66fa-47cc-896c-5256c9c7619b)
![1720294899751](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/68b951b2-4e19-42d7-8409-085e9a989426)
![1720294909944](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/284c5655-f402-40e6-8bb6-36de7cc7f69f)

# References
https://github.com/ultralytics/yolov5

https://github.com/ultralytics/yolov7

https://github.com/ultralytics/yolov8

https://github.com/ultralytics/yolovX

# Citation
If you think this work is useful for you, please cite


## <div align="center">License</div>

YOLOv8 is available under two different licenses:

- **AGPL-3.0 License**: See [LICENSE](https://github.com/ultralytics/ultralytics/blob/main/LICENSE) file for details.
- **Enterprise License**: Provides greater flexibility for commercial product development without the open-source requirements of AGPL-3.0. Typical use cases are embedding Ultralytics software and AI models in commercial products and applications. Request an Enterprise License at [Ultralytics Licensing](https://ultralytics.com/license).

## <div align="center">Contact</div>

For YOLOv8 bug reports and feature requests please visit [GitHub Issues](https://github.com/ultralytics/ultralytics/issues), and join our [Discord](https://discord.gg/n6cFeSPZdD) community for questions and discussions!

<br>
<div align="center">
  <a href="https://github.com/ultralytics" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-github.png" width="3%" alt="" /></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="" />
  <a href="https://www.linkedin.com/company/ultralytics/" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-linkedin.png" width="3%" alt="" /></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="" />
  <a href="https://twitter.com/ultralytics" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-twitter.png" width="3%" alt="" /></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="" />
  <a href="https://youtube.com/ultralytics" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-youtube.png" width="3%" alt="" /></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="" />
  <a href="https://www.tiktok.com/@ultralytics" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-tiktok.png" width="3%" alt="" /></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="" />
  <a href="https://www.instagram.com/ultralytics/" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-instagram.png" width="3%" alt="" /></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="" />
  <a href="https://discord.gg/n6cFeSPZdD" style="text-decoration:none;">
    <img src="https://github.com/ultralytics/assets/blob/main/social/logo-social-discord.png" width="3%" alt="" /></a>
</div>
