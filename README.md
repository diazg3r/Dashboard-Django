# Dashboard-Django

Database and analytics dashboard modules for Circular Solutions: AI-Powered Smart Waste Monitoring, Analytics & Prediction System (capstone with Boston Mountain, mentored by Dr. Justus).


Built ahead of the camera/detection module, using mock data, so the schema and dashboard are ready when detection lands. Kept in a separate repo for now in case it doesn't end up merging into the main one.


What's here
- PostgreSQL schema (WasteEvent, WasteCategory, Location) matching the fields detection will produce
- Dashboard (Django + Chart.js): waste by category/location, daily/weekly/monthly trends, filters
- Mock data generator standing in for the detection pipeline



Stack
Django 6.x · PostgreSQL · Chart.js (CDN) · Django Admin
