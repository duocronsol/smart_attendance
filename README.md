# Smart Attendance

Smart Attendance is a Frappe based application used for managing employee attendance using face recognition.

## Features
- Face based attendance
- Auto attendance marking
- Attendance device management
- Attendance reports
- Kiosk mode support

## Technology Used
- Frappe Framework
- Python
- JavaScript
- HTML

## System requirements
`face_recognition` and `dlib` are compiled when the app is fetched, so the server needs these system packages
before `bench get-app` (installed by an administrator, for example `sudo apt-get install cmake build-essential libopencv-dev python3-dev`):

- cmake
- build-essential
- libopencv-dev
- python3-dev

## Installation
```bash
bench get-app smart_attendance
bench --site yoursite install-app smart_attendance
