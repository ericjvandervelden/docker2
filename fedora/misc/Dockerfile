from my/fedora-locale 
run dnf -y install less procps-ng hostname iputils net-tools findutils
run setcap cap_net_raw,cap_net_admin+p  /usr/bin/ping
run dnf -y install httpd

#cmd ["ping","localhost"]
#cmd ping localhost

#entrypoint ["/usr/bin/ping"]			# geef $ docker ... <image> -d localhost 

#cmd ["read"]
#cmd read

#entrypoint ["top","-b"]
#cmd ["-c"]

expose 80 443
#entrypoint ["httpd","-D","FOREGROUND"]
cmd ["httpd","-D","FOREGROUND"]
run dnf -y install tar
run dnf -y install openssh-server openssh-clients
