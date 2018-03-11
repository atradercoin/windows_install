
Create a directory C:\atradercoin
Copy the files/unzip into atradercoin with the exception of atradercoin.conf
Create a directory C:\users\"your login username"\appdata\roaming\atradercoin
Copy the file atradercoin.conf to the directory (production settings)
Copy the file atradercoin_tn.conf to the directory  (testnet settings)

Create Shortcuts as below
Create a shortcut to atradercoin-production
Target C:\atradercoin\atradercoin-qt.exe -conf=atradercoin.conf
Start in directory C:\users\"your login username"\appdata\roaming\atradercoin

Create a shortcut to atradercoin-testnet
Target C:\atradercoin\atradercoin-qt.exe -testnet -conf=atradercoin_tn.conf
Start in c:\atradercoin\atradercoin-qt.exe, Working/start in directory C:\users\"your login username"\appdata\roaming\atradercoin

You can mine to the pool details are at 
http://www.atrader.org or
http://atradercoin.ddns.net:8082
