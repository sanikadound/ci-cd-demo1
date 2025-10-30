$ git clone https://github.com/sanikadound/ci-cd-demo1.git
$ cd ci-cd-demo1
$ nano app.py
$ nano deploy.sh
{
echo "----CI/CD Pipeline started-----"
echo "step1:building the aplication"
sleep2
echo "step2 :running test"
sleep2
echo "test passed sucesfully"
echo "step3 :deploying application..."
sleep2
echo "application deployed succesfully sucesfully"
echo "step3 :"CI/CD Pipeline finish..."
$ chmod +x deploy.sh
$ nano deploy.sh
git add .
git commiy -m "initial commmit"
git push -u origin
