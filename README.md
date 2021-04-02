# Drawbot---VariableFont---Pipeline
Proof of Concept


to build font

open rect1010100100.py 
in the drawbot extenstion for robofont
run it 

save the resulting ufo

close both 

open a new ufo in robofont and run
rect1010900900.py
save as 
1010900900.ufo

using designspace edit produce a designspace file with a weight axis
100---900

save the resulting designspace file as SquareTest.designspace

in terminal

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

chmod +x build.sh

./build.sh

voila variable font


