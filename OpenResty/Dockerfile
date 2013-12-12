FROM ubuntu

RUN apt-get update
RUN apt-get install -y wget libreadline-dev libncurses5-dev libpcre3-dev libssl-dev perl make
RUN wget --no-check-certificate http://openresty.org/download/ngx_openresty-1.4.3.6.tar.gz
RUN tar -zxf ngx_openresty-1.4.3.6.tar.gz
RUN cd ngx_openresty-1.4.3.6; echo pwd; ./configure --with-luajit; make; make install
