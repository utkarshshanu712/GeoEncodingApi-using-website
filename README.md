# GeoEncodingApi-using-website

IT is not any complex project but to show how can you use my GeoEncoding Api in your project 🌍 Geocoding API 🌍

This API provides geographical information based on latitude and longitude coordinates. It returns the closest state, district, and country for the provided coordinates.
### 🌏 [Geocoding-API](https://github.com/utkarshshanu712/Geocoding-API)
Geocoding-API.
## Overview
🌈 The Geocoding API allows users to find geographical locations worldwide based on latitude and longitude. It can return detailed location information, including the state, district, and country.

## Endpoint
**URL:** `/find-state`  
**Method:** `GET`

### Query Parameters
- `lat` (required): Latitude of the location.
- `long` (required): Longitude of the location.

### Example Request
```sh
curl 'https://geo-api-61zy.onrender.com/find-state?lat=28.6139&long=77.2090'
