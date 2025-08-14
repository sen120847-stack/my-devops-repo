# בסיס
FROM python:3.10-slim

# העתקת קבצים
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .

# הרצת האפליקציה
CMD ["python", "app.py"]
