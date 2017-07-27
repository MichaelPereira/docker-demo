FROM ubuntu:15.04
COPY . /app
RUN cd /app && touch newfile
RUN cd /app && cp newfile newfile2
RUN cd /app && cp newfile2 newfile3
RUN cd /app && cp newfile4 newfile5
RUN cd /app && cp newfile5 newfile6
CMD python /app/app.py
