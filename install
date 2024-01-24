###-------[IMPORT MODULES]-----------####

import os
import sys
import time
import uuid
import json
import string
import random
import requests


###-------[BASIC COLORS]-----------####
reset = "\033[0m"
red = "\033[1;31m"
green = "\033[1;32m"
yellow = "\033[1;33m"
blue = "\033[1;34m"
cyan = "\033[1;36m"
white = "\033[1;37m"

###-------[FLASH COLORS]-----------####
colors = ["\033[1;30m", "\033[1;30m", "\033[0;31m", "\033[1;31m", "\033[0;32m", "\033[1;32m","\033[0;92m","\033[1;92m","\033[1;93m","\033[1;94m","\033[1;95m","\033[1;96m","\033[0;33m", "\033[1;33m", "\033[0;34m", "\033[1;34m", "\033[0;35m", "\033[1;35m", "\033[0;36m", "\033[1;36m", "\033[0;37m", "\033[1;37m", "\033[1;90m", "\033[0;91m","\033[1;91m", "\033[0;92m", "\033[1;93m", "\033[0;94m", "\033[1;94m", "\033[0;95m","\033[1;95m", "\033[0;96m", "\033[1;96m", "\033[0;97m", "\033[0;100m", "\033[1;100m","\033[0;101m", "\033[1;101m", "\033[0;102m", "\033[1;102m","\033[0;104m", "\033[1;104m", "\033[0;105m", "\033[1;105m", "\033[0;106m", "\033[1;106m"]

###-------[LOOP]-----------####
loop = 0
idz = []
oks = []
cps = []

###-------[LOGO]-----------####
logo= f'''\033[1;97m
     


$$$$$$$$\                  $$\       $$$$$$$$\ 
\__$$  __|                 $$ |      \____$$  |
   $$ | $$$$$$\   $$$$$$\  $$ |          $$  / 
   $$ |$$  __$$\ $$  __$$\ $$ |$$$$$$\  $$  /  
   $$ |$$ /  $$ |$$ /  $$ |$$ |\______|$$  /   
   $$ |$$ |  $$ |$$ |  $$ |$$ |       $$  /    
   $$ |\$$$$$$  |\$$$$$$  |$$ |      $$$$$$$$\ 
   \__| \______/  \______/ \__|      \________|\033[1;97m\033[1;92mV2.0
   
\033[1;97m====================================================
\033[1;33m|           Install Best Hacking Tool              |
\033[1;97m==================================================== 
 '''


###-------[CLEAR TERMINAL]-----------####
def clear():
    os.system("clear")
    print(logo)



###-------[LINE]-----------####
def linex():
    print(f"\033[1;97m====================================================")



###-------[MSIN MENU]-----------####
def menu():
    clear()
    print(f" \033[1;97m[\033[1;92m01\033[1;97m] Show all tools.")
    print(f" \033[1;97m[\033[1;92m02\033[1;97m] Tools Category.")
    print(f" \033[1;97m[\033[1;92m03\033[1;97m] Update Tool-Z.")
    print(f" \033[1;97m[\033[1;92m04\033[1;97m] About Us.")
    print(f" \033[1;97m[\033[1;92m x\033[1;97m] For Exit.")
    linex()
    home = input(f" \033[1;97m\033[1;92mTool-Z@space\033[1;97m $ ")
    
    if home in ['1','01']:
        alltool()
        
        
    elif home in ['2','02']:
        time.sleep(1)
        tools_ategory()
        

    
    elif home in ['x','X']:
    	os.system("exit");
    


    
    else:
        print(f"\n\033[1;91m Select valid option ....")
        time.sleep(3)
        menu()
        
        

    

###-------[DEF CLONING]-----------####
def alltool():
    clear()
    print(f" \033[1;97m[\033[1;92m01\033[1;97m] Show all tools.")
    print(f" \033[1;97m[\033[1;92m02\033[1;97m] Tools Category.")
    print(f" \033[1;97m[\033[1;92m03\033[1;97m] Update Tool-Z.")
    print(f" \033[1;97m[\033[1;92m04\033[1;97m] About Us.")
    print(" ")
    print(" ")
    print(f" \033[1;97m[\033[1;92m00\033[1;97m] Mane Manu.")
    linex()
    
    atool = input(f" \033[1;97m\033[1;92mTool-Z@space\033[1;97m $ ")
    
    
    
    ###-------[Tools Category]-----------####
def tools_ategory():
    clear()
    print(f" \033[1;97m[\033[1;92m01\033[1;97m] Information Gathering")
    print(f" \033[1;97m[\033[1;92m02\033[1;97m] Vulnerability Scanner")
    print(f" \033[1;97m[\033[1;92m03\033[1;97m] Exploitation Tools")
    print(f" \033[1;97m[\033[1;92m04\033[1;97m] Wireless Testing")
    print(f" \033[1;97m[\033[1;92m05\033[1;97m] Forensics Tools")
    print(f" \033[1;97m[\033[1;92m06\033[1;97m] Web Hacking")
    print(f" \033[1;97m[\033[1;92m07\033[1;97m] Stress Testing")
    print(f" \033[1;97m[\033[1;92m08\033[1;97m] Sniffing & Spoofing")
    print(f" \033[1;97m[\033[1;92m09\033[1;97m] Password Attacks")
    print(f" \033[1;97m[\033[1;92m10\033[1;97m] Maintaining Access")
    print(f" \033[1;97m[\033[1;92m11\033[1;97m] IP-Tracking tools")
    print(f" \033[1;97m[\033[1;92m12\033[1;97m] Programming Languages")
    print(f" \033[1;97m[\033[1;92m13\033[1;97m] DDOS Attacks")
    print(f" \033[1;97m[\033[1;92m14\033[1;97m] Web Server's")
    print(" ")
    print(" ")
    print(f" \033[1;97m[\033[1;92m00\033[1;97m] Back")
    linex()
    
    tools_ategory = input(f" \033[1;97m\033[1;92mTool-Z@space\033[1;97m $ ")
    

    if tools_ategory in ['1','01']:
        information_gathering()
        
        
        
    elif tools_ategory in ['2','02']:
        time.sleep(1)
        vulnerability_scanner()
        
        
        
        
    elif tools_ategory in ['00']:
        menu()
    	
    


    
    else:
        print(f"\n\033[1;91m Select valid option ....")
        tools_ategory()
        
            ###-------[Information Gathering]-----------####
def information_gathering():
    clear()
    print(f" \033[1;97m[\033[1;92m01\033[1;97m] Information Gathering 2004")
    print(f" \033[1;97m[\033[1;92m02\033[1;97m] Vulnerability Scanner")
    print(f" \033[1;97m[\033[1;92m03\033[1;97m] Exploitation Tools")
    print(f" \033[1;97m[\033[1;92m04\033[1;97m] Wireless Testing")
    print(f" \033[1;97m[\033[1;92m05\033[1;97m] Forensics Tools")
    print(f" \033[1;97m[\033[1;92m06\033[1;97m] Web Hacking")
    print(f" \033[1;97m[\033[1;92m07\033[1;97m] Stress Testing")
    print(f" \033[1;97m[\033[1;92m08\033[1;97m] Sniffing & Spoofing")
    print(f" \033[1;97m[\033[1;92m09\033[1;97m] Password Attacks")
    print(f" \033[1;97m[\033[1;92m10\033[1;97m] Maintaining Access")
    print(f" \033[1;97m[\033[1;92m11\033[1;97m] IP-Tracking tools")
    print(f" \033[1;97m[\033[1;92m12\033[1;97m] Programming Languages")
    print(f" \033[1;97m[\033[1;92m13\033[1;97m] DDOS Attacks")
    print(f" \033[1;97m[\033[1;92m14\033[1;97m] Web Server's")
    print(" ")
    print(" ")
    print(f" \033[1;97m[\033[1;92m00\033[1;97m] Back")
    linex()
    
    tools_ategory = input(f" \033[1;97m\033[1;92mTool-Z@space\033[1;97m $ ")
    

    if tools_ategory in ['1','01']:
        alltool()
        
    elif tools_ategory in ['2','02']:
        time.sleep(1)
        tools_ategory()
        
        
    elif tools_ategory in ['00']:
        menu()
    	
    


    
    else:
        print(f"\n\033[1;91m Select valid option ....")
        tools_ategory()
        
        
        
        
            ###-------[Vulnerability Scanner]-----------####
def vulnerability_scanner():
    clear()
    print(f" \033[1;97m[\033[1;92m01\033[1;97m] Information Gathering")
    print(f" \033[1;97m[\033[1;92m02\033[1;97m] Vulnerability Scanner")
    print(f" \033[1;97m[\033[1;92m03\033[1;97m] Exploitation Tools")
    print(f" \033[1;97m[\033[1;92m04\033[1;97m] Wireless Testing")
    print(f" \033[1;97m[\033[1;92m05\033[1;97m] Forensics Tools")
    print(f" \033[1;97m[\033[1;92m06\033[1;97m] Web Hacking")
    print(f" \033[1;97m[\033[1;92m07\033[1;97m] Stress Testing")
    print(f" \033[1;97m[\033[1;92m08\033[1;97m] Sniffing & Spoofing")
    print(f" \033[1;97m[\033[1;92m09\033[1;97m] Password Attacks")
    print(f" \033[1;97m[\033[1;92m10\033[1;97m] Maintaining Access")
    print(f" \033[1;97m[\033[1;92m11\033[1;97m] IP-Tracking tools")
    print(f" \033[1;97m[\033[1;92m12\033[1;97m] Programming Languages")
    print(f" \033[1;97m[\033[1;92m13\033[1;97m] DDOS Attacks")
    print(f" \033[1;97m[\033[1;92m14\033[1;97m] Web Server's")
    print(" ")
    print(" ")
    print(f" \033[1;97m[\033[1;92m00\033[1;97m] Back")
    linex()
    
    tools_ategory = input(f" \033[1;97m\033[1;92mTool-Z@space\033[1;97m $ ")
    

    if tools_ategory in ['1','01']:
        alltool()
        
    elif tools_ategory in ['2','02']:
        time.sleep(1)
        tools_ategory()
        
        
    elif tools_ategory in ['00']:
        menu()
    	
    


    
    else:
        print(f"\n\033[1;91m Select valid option ....")
        tools_ategory()
        
        
        
        
               ###-------[Exploitation Tools]-----------####
def exploitation_tools():
    clear()
    print(f" \033[1;97m[\033[1;92m01\033[1;97m]  exploitation_tools")
    print(f" \033[1;97m[\033[1;92m02\033[1;97m] Vulnerability Scanner")
    print(f" \033[1;97m[\033[1;92m03\033[1;97m] Exploitation Tools")
    print(f" \033[1;97m[\033[1;92m04\033[1;97m] Wireless Testing")
    print(f" \033[1;97m[\033[1;92m05\033[1;97m] Forensics Tools")
    print(f" \033[1;97m[\033[1;92m06\033[1;97m] Web Hacking")
    print(f" \033[1;97m[\033[1;92m07\033[1;97m] Stress Testing")
    print(f" \033[1;97m[\033[1;92m08\033[1;97m] Sniffing & Spoofing")
    print(f" \033[1;97m[\033[1;92m09\033[1;97m] Password Attacks")
    print(f" \033[1;97m[\033[1;92m10\033[1;97m] Maintaining Access")
    print(f" \033[1;97m[\033[1;92m11\033[1;97m] IP-Tracking tools")
    print(f" \033[1;97m[\033[1;92m12\033[1;97m] Programming Languages")
    print(f" \033[1;97m[\033[1;92m13\033[1;97m] DDOS Attacks")
    print(f" \033[1;97m[\033[1;92m14\033[1;97m] Web Server's")
    print(" ")
    print(" ")
    print(f" \033[1;97m[\033[1;92m00\033[1;97m] Back")
    linex()
    
    tools_ategory = input(f" \033[1;97m\033[1;92mTool-Z@space\033[1;97m $ ")
    

    if tools_ategory in ['1','01']:
        alltool()
        
    elif tools_ategory in ['2','02']:
        time.sleep(1)
        tools_ategory()
        
        
    elif tools_ategory in ['00']:
        menu()
    	
    


    
    else:
        print(f"\n\033[1;91m Select valid option ....")
        tools_ategory()
        
        
        
        
        
        
        
 




menu()
