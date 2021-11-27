FROM python
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  midterm_app.py /home/myapp/
EXPOSE 5000
RUN python3 -m pip install flask
RUN python3 -m pip install urllib3
RUN python3 -m pip install requests
CMD python3 /home/myapp/midterm_app.py
