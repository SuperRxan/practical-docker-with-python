FROM python:3-alpine

COPY * /apps/subredditfetcher/
WORKDIR /apps/subredditfetcher/

VOLUME [ "/apps/subredditfetcher" ]
RUN ["pip", "install", "-r", "requirements.txt"]
# RUN ["python", "one_time.py"]

ENV NBT_ACCESS_TOKEN="495637361:AAHIhiDTX1UeX17KJy0-FsMZEqEtCFYfcP8"

CMD ["python", "newsbot.py"]
