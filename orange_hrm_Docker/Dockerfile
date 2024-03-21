from python
workdir /app
copy . /app
RUN pip install bs4
RUN pip install pandas
RUN pip install pytest-playwright
RUN playwright install
RUN playwright install-deps
CMD ["pytest","-s","app.py"]