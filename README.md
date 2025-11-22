### How to run

project/
├── backend/
│   ├── .../
│   ├── users/
│   └── backend/
└── frontend/
    ├── src/
    └── .../

## Run backend

1. Create and activate venv
```bash
python -m venv venv
```

```UNIX
source venv/bin/activate
```

```Window
source venv/Scipts/activate
```

2. Install requirements
```bash
pip install -r requirements.txt
```

3. Apply migrations
```bash
cd backend
python manage.py migrate
```

4. Run backend
```bash
python manage.py runserver
```

## Run fronend

1. Create Vite
```
npm create vite@latest frontend -- --template react
```

2. Install packages
```
cd frontend
npm install
```

3. Run dev
```
npm run dev
```

