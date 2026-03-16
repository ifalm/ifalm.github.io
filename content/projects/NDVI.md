---
title: "NDVI Time-series Analysis"
date: 2026-03-20
draft: false
summary: "NDVI time-series analysis using Sentinel-2 imagery."
image: "/images/NDVI_sem_leg_.png"
featured: true
---

## Overview

This project analyzes NDVI time evolution in the city of Lisbon.

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

The analysis resulted in a decrase in NDVI values.
