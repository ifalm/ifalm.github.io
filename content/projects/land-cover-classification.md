---
title: "Land Cover Classification with Sentinel-2"
date: 2026-02-26
draft: false
summary: "Supervised classification using Sentinel-2 imagery and Random Forest."
image: "/images/NDVI_sem_leg_.png"
---

## Overview

This project analyzes land cover using Sentinel-2 imagery.

## Tools Used

- QGIS
- Google Earth Engine
- Python (rasterio, numpy)

## Interactive Map

<div id="map" style="height:400px;"></div>

<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<script>
var map = L.map('map').setView([40.4168, -3.7038], 6);

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '© OpenStreetMap contributors'
}).addTo(map);
</script>

## Results

The classification achieved 87% overall accuracy.