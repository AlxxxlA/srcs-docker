FROM python:2.7
RUN pip install flask requests
RUN useradd api -s /bin/bash
COPY ./api.py /api.py
USER api
EXPOSE 8001
CMD ["python", "api.py"]
