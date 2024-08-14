Run in terminal (copy all lines at once):

git clone https://github.com/TadejMurovic/rvsummit_santaclara_2024_hackaton.git &&
apt-get install zip unzip &&
cd rvsummit_santaclara_2024_hackaton &&
unzip files.tar &&
mv codasip_urisc/ ../codasip_urisc &&
mv hackaton_sw/ ../hackaton_sw  &&
cd .. &&
rm -rf rvsummit_santaclara_2024_hackaton/ &&
rm -rf codasip_urisc/work/* 
