# absensi-siakad-ftl
Faster than light absensi siakad

# Usage

Mengabsen masuk luring:
```
python3 main.py -m masuk -d luring <email> <password>
```

Mengambil status absen dari server:
```
python3 main.py --get-status <email> <password>
```

## Session File

Percepat absen menggunakan session file:
```
python3 main.py --generate-session my-session.pkl <email> <password>
python3 main.py --use-session my-session.pkl -m masuk -d luring
```

Percepat lagi dengan `--skip-session-check`