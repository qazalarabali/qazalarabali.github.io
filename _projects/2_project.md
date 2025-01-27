---
layout: page
title: IoT-Powered Smart Home Automation
description: An IoT-based project to control and monitor home appliances remotely.
img: assets/img/smart-home-overview.jpg
importance: 4
category: work
tags:
  - IoT
  - smart-home
  - automation
  - remote-control
  - energy-monitoring
---

### Overview

This project implemented a smart home automation system that allows users to control and monitor home appliances remotely. The system combines IoT devices with a mobile app to provide a seamless user experience.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-home-overview.jpg" title="Smart Home Overview" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-home-control.jpg" title="Remote Control" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-home-automation.jpg" title="Automation Rules" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    From remote control to energy monitoring: The future of smart homes.
</div>

### Features

- **Remote Control:** Operate home appliances such as lights, fans, and air conditioners via a mobile app.
- **Energy Monitoring:** View real-time data on energy consumption for better efficiency.
- **Automation Rules:** Set rules like turning on lights at a specific time or when entering a room.
- **Voice Command Support:** Integrated with Google Assistant for hands-free control.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/smart-home-demo.jpg" title="Smart Home Demo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/smart-home-energy.jpg" title="Energy Monitoring" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Example features: Control, monitor, and automate your home.
</div>

### Technologies Used

- **Arduino Microcontroller:** To interface with IoT sensors and actuators.
- **MQTT Protocol:** Ensures secure and lightweight communication between devices.
- **Android Studio:** For building the mobile app.
- **Node-RED:** Used to create workflows for automation.

### Architecture

The system comprises three main layers:

1. **IoT Devices:** Sensors and actuators connected to an Arduino board.
2. **Communication Layer:** Uses the MQTT protocol to transmit data between devices.
3. **Mobile Application:** Provides a user-friendly interface for control and monitoring.

### Results

- Improved energy efficiency by 30% through automation.
- Enhanced user convenience with remote and voice-controlled operations.

### Future Plans

- Add compatibility with Alexa and Siri.
- Expand the system to include security features like motion detection and CCTV monitoring.

{% if page.tags.size > 0 %}

  <p class="post-tags">
    <strong>Tags:</strong>
    {% for tag in page.tags %}
      <a href="{{ '/tags/' | append: tag | relative_url }}" class="tag-link">{{ tag }}</a>
      {% unless forloop.last %}
        &nbsp;|&nbsp;
      {% endunless %}
    {% endfor %}
  </p>
{% endif %}
