FROM java:8

RUN mkdir /jmeter \
    && cd /jmeter/ 
RUN  -v "$PWD":/Users/frederickishimwe/Desktop/takealot-repo/jmeter -w /Users/frederickishimwe/Desktop/takealot-repo/jmeter 

    #git clone https://github.com/frederickishimwe/jmeter.git
    #git pull && git fetch

ENV JMETER_HOME /jmeter/

# Add Jmeter to the Path
ENV PATH $JMETER_HOME/bin:$PATH
