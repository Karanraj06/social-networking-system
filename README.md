# social-networking-system

![ER-Diagram](/docs/er-diagram.png)

## Getting Started

Requires Python 3.10+

1. To get started with this project, run

```bash
git clone https://github.com/Karanraj06/social-networking-system
```

2. Copy `.env.example` to `.env` file and update the variables

```bash
cp .env.example .env
```

3. Install dependencies using pip

```bash
pip install -r requirements.txt
```

Now, change the current working directory to `app`

4. Run the FastAPI Server with Uvicorn

```bash
uvicorn main:app --reload
```

Open http://localhost:8000/docs to view the API documentation

5. Create tables and seed the database
```bash
python crud.py
```

## Database Insider

1. Clone the repository

```bash
git clone https://github.com/Karanraj06/social-networking-system -b prisma
```

2. Start the app

```bash
npx prisma studio
# or
bunx prisma studio
```

Open http://localhost:5555 to view it in your browser

## Authors

- Atharva Suhas Mulay ([@AtharvaMulay25](https://github.com/AtharvaMulay25))
- Karanraj Mehta ([@Karanraj06](https://github.com/Karanraj06))
- Sahil Mangla ([@SahilMangla14](https://github.com/SahilMangla14))
- Harsh Raj Srivastava ([@Harsh290803](https://github.com/Harsh290803))