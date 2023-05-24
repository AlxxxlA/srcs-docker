FROM python:2.7
RUN pip install flask requests
RUN useradd api -s /bin/bash
ENV API_BACKEND_URL=api-backend
ENV API_BACKEND_PORT=8001
COPY ./api.py /api.py
USER api
EXPOSE 8000
CMD ["python", "api.py"]
