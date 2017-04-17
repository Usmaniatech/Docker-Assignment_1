FROM python:2
WORKDIR .
RUN pip install pandas
RUN pip install jupyter

ADD Muhammad_Usman_lhr_python_assignment2.ipynb .

EXPOSE 8888

CMD ["jupyter", "notebook", "--allow-root", "--no-browser","--ip","0.0.0.0"]
