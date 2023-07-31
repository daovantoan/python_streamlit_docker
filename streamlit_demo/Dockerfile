FROM python:3.7
EXPOSE 8501
RUN PYTHONPATH=/usr/bin/python pip install streamlit && pip install numpy && pip install pandas
COPY app/ app/
WORKDIR /app
ENTRYPOINT ["streamlit", "run"]
CMD ["dashboard.py"]