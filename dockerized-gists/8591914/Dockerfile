FROM python:2.7.13
ADD snippet.py snippet.py
RUN ["pip", "install", "keychain"]
RUN ["pip", "install", "requests"]
RUN ["pip", "install", "console"]
CMD ["python", "snippet.py"]