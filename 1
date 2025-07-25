import os
import requests
from flask import Flask

app = Flask(__name__)

TOKEN = os.environ.get("TOKEN")
CHAT_ID = os.environ.get("CHAT_ID")

@app.route("/")
def home():
    return "Bot çalışıyor!"

@app.route("/test")
def test():
    message = (
        "🟢 TEST SİNYALİ – Railway Başarılı!\n"
        "Pair: BTCUSDT\n"
        "Strateji: EMA + OB + FVG + MSS\n"
        "Zaman Dilimi: 15dk\n"
        "Durum: 🚀 Railway tetikleme çalıştı!"
    )
    url = f"https://api.telegram.org/bot{TOKEN}/sendMessage"
    data = {"chat_id": CHAT_ID, "text": message}
    response = requests.post(url, data=data)
    return f"{response.status_code} - {response.text}"

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=8000)
