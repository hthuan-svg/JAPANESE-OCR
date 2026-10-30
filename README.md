ONLINE SERVER:

cd japanese-ocr\backend
\venv\Scripts\activate

pip install paddlepaddle==3.2.2 --index-url https://www.paddlepaddle.org.cn/packages/stable/cpu/
pip install -r requirements.txt
uvicorn main:app --port 8000



