# tool
Don't use this any personal work.. 
#!/bin/bash
clear
echo
echo
figlet LEGEND OF CRIMINAL
echo "Press Enter To Continue"
read a1
python2 password.py
clear
echo -e "\e[4;31m LEGEND OF CRIMINAL !!! \e[0m"
echo -e "\e[1;34m Presents \e[0m"
echo -e "\e[1;32m Tool \e[0m"
echo "Press Enter To Continue"
read a1
if [[ -s update.speedx ]];then
echo "All Requirements Found...."
else
echo 'Installing Requirements....'
echo .
echo .
pkg install toilet -y
pkg install figlet -y
apt install figlet toilet python curl -y
apt install python3-pip
pip install -r requirements.txt
echo This Script Was Made By LEGEND OF CRIMINAL
figlet INSTALLING SUCCESSFUL
echo Press Enter To Continue...
read upd
fi
while :
do
rm *.xxx >/dev/null 2>&1
clear
echo -e "\e[1;31m"
figlet Bomber
echo -e "\e[1;34m Created By \e[1;32m"
toilet -f mono12 -F border LEGEND OF CRIMINAL
echo -e "\e[4;34m This Tool Was Created By LOC \e[0m"
echo -e "\e[1;34m For Any Queries Mail Me!!!\e[0m"
echo -e "\e[1;32m           Mail: legendofcriminal@gmail.com \e[0m"
echo -e "\e[4;32m           FB  : https://www.facebook.com/THE.KING.IN.MEDIA.42 \e[0m"
echo " "
echo -e "\e[4;31m Please Read Instruction Carefully !!! \e[0m"
echo " "
echo "Press 1 To  Start SMS Tool "
echo "Press 2 To  Start Call Tool "
echo "Press 3 To  Update (Works On Linux Or Linux Emulators) "
echo "Press 4 To  View Features "
echo "Press 5 To  Exit "
read ch
if [ $ch -eq 1 ];then
clear
echo -e "\e[1;32m"
rm *.xxx >/dev/null 2>&1
python3 tool.py
rm *.xxx >/dev/null 2>&1
exit 0
elif [ $ch -eq 2 ];then
clear
echo -e "\e[1;32m"
echo 'Call Tool By LOS'> call.xxx
python3 tool.py call
rm *.xxx >/dev/null 2>&1
exit 0
elif [ $ch -eq 3 ];then
clear
apt install git -y
echo -e "\e[1;34m Downloading Latest Files..."
git clone https://github.com/labibhacker/Tool
if [[ -s Tool/tool.sh ]];then
cd Tool
cp -r -f * .. > temp
cd ..
rm -rf  TTool >> temp
rm update.speedx >> temp
rm temp
chmod +x tool.sh
fi
echo -e "\e[1;32m Tool Will Restart Now..."
echo -e "\e[1;32m All The Required Packages Will Be Installed..."
echo -e "\e[1;34m Press Enter To Proceed To Restart..."
read a6
./tool.sh
exit
elif [ $ch -eq 4 ];then
clear
echo -e "\e[1;33m"
figlet TOOL
echo -e "\e[1;34mCreated By \e[1;34m"
toilet -f mono12 -F border LOC
echo  " "
echo -e "\e[1;32m                   Features\e[1;34m"
echo "  [+] Unlimited And Super-Fast Tool"
echo "  [+] International Tool"
echo "  [+] Call Tool "
echo "  [+] Protection List"
echo "  [+] Automated Future Updates"
echo "  [+] Easy To Use And Embed in Code"
echo -e "\e[1;32m                   Contributors\e[1;33m"
echo -e "\e[1;33m      [*]  LEGEND OF CRIMINAL   \e[1;31m"
echo "         [-] Mail At: legendofcriminal@gmail.com"
echo -e "\e[1;33m      [*]  The Black Hacker Roxstar   \e[1;31m"
echo "         [-] Ping At: https://www.facebook.com/THE.KING.IN.MEDIA.42"
echo -e "\e[1;33m      [*]  Rieltar   \e[1;31m"
echo "         [-] Ping At: https://m.me/darkbet.ariyan"
echo -e "\e[1;33m      [*]  0n1cOn3 (Stefan)   \e[1;31m"
echo "         [-] Mail At: imamalilabib@gmail.com"
echo ""
echo ""
echo -e "\e[1;31m This Script is Only For Educational Purposes or To Prank.\e[0m"
echo -e "\e[1;31m Do not Use This To Harm Others. \e[0m"
echo -e "\e[1;31m I Am Not Responsible For The Misuse Of The Script. \e[0m"
echo -e "\e[1;32m Make Sure To Update it If It Does not Work.\e[0m"
echo  " "
echo -e "\e[4;31m That's All !!!\e[0m"
echo -e "\e[1;34m For Any Queries Mail Me!!!\e[0m"
echo -e "\e[1;32m           Mail: legendofcriminal@gmail.com \e[0m"
echo -e "\e[1;32m       Whatsapp: https://whatsapp.com/dl\e[0m"
echo -e "\e[4;32m             FB: https://www.facebook.com/THE.KING.IN.MEDIA.42 \e[0m"
echo "Press Enter To Go Home"
read a3
clear
elif [ $ch -eq 5 ];then
clear
echo -e "\e[1;31m"
figlet TOOL
echo -e "\e[1;34m Created By \e[1;32m"
toilet -f mono12 -F border LOC
echo -e "\e[1;34m For Any Queries Mail Me!!!\e[0m"
echo -e "\e[1;32m           Mail: legendofcriminal@gmail.com \e[0m"
echo -e "\e[1;32m             FB: https://www.facebook.com/THE.KING.IN.MEDIA.42 \e[0m"
echo -e "\e[4;32m             ME: https://www.facebook.com/THE.KING.IN.MEDIA.42 \e[0m"
echo -e "\e[1;34m Coded By \e[1;32m"
toilet -f mono12 -F border LABIB
echo " "
echo -e "\e[1;34m Modified By \e[1;32m"
toilet -f mono12 -F border LABIB
echo " "
exit 0
else
echo -e "\e[4;32m Invalid Input !!! \e[0m"
echo "Press Enter To Go Home"
read a3
clear
fi
done
