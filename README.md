## INSTALASI
git clone https://github.com/nalonal/sp3<br>
cd sp3<br>
echo -e "AIRFLOW_UID=$(id -u)\nAIRFLOW_GID=0" > .env
chmod u+x install.sh<br>
./install.sh

## PEMAKAIAN SETIAP HABIS STOP ENGINE
sudo chmod 666 /var/run/docker.sock

