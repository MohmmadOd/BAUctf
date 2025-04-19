The challenge give me the docm file first , I did the research about how can I extract data from it 
I should have to install  olevba tool to extract data.
![Q2ins](https://github.com/MohmmadOd/BAUctf/assets/170467994/e2a53502-03b3-4d4c-a3cc-37f99d9dd92c)
![Q2ins2](https://github.com/MohmmadOd/BAUctf/assets/170467994/3db91d8e-bd73-4aa5-83d8-893a5ce69bb9)
The tools were installed without errors . then  , I used olevba  [path docm file ] , so he gave me a type AES (Encryption algorithm) , vi and key . so, I  had to find cypher text .
![Q2ole](https://github.com/MohmmadOd/BAUctf/assets/170467994/21129d2e-3a66-48c3-8a41-23e3a807c03c)
I opened the docm file in the Microsoft word  then i didn't find it 
![Q2cyphernotfound](https://github.com/MohmmadOd/BAUctf/assets/170467994/516aee88-1cd8-4356-aa0c-153a15a05a01)
 then , I thought mabey have a hidden text to see it clicked on file  option Display  hidden text.
 ![Q2cyphertext](https://github.com/MohmmadOd/BAUctf/assets/170467994/c1a3016b-bf0e-40c3-aa4b-5d785907447b)
 Here I used the I used Python code to decrypt the algorithm
 ![code](https://github.com/MohmmadOd/BAUctf/assets/170467994/1ad67c5c-671f-4767-8da1-509a40eddee7)
Run the python code and I found the flag 
![run](https://github.com/MohmmadOd/BAUctf/assets/170467994/68d48061-44dc-4999-95bb-e575b47bc6e7)

