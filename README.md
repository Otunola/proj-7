#  implementation a web solution for a DevOps team using LAMP stack with remote Database and NFS servers
In this project, we shall implement a solution that consist of component as shown in the diagram below
![Screenshot 2022-09-29 at 11 24 12](https://user-images.githubusercontent.com/112595648/193007336-75ba8cd5-c163-4f10-87c1-53aa3b9e3bf2.png)

as shown in the diagram above and as instructed in the manual, 
we have 3 webservers (rhel-8) 1 NFS-server(Rhel-8) and a DB-server (ubuntu20.4)
<img width="566" alt="Screenshot 2022-10-11 at 08 24 32" src="https://user-images.githubusercontent.com/112595648/195022737-037525b4-6abc-4b04-be27-ee19cc9e7bba.png">
<img width="560" alt="Screenshot 2022-10-11 at 08 25 12" src="https://user-images.githubusercontent.com/112595648/195022849-b4058059-662f-485b-90fe-a232700e873e.png">
<img width="560" alt="Screenshot 2022-10-11 at 08 26 27" src="https://user-images.githubusercontent.com/112595648/195023112-e1da4cf9-e658-4305-aa79-3cbff70ea4f2.png">
<img width="563" alt="Screenshot 2022-10-11 at 08 26 52" src="https://user-images.githubusercontent.com/112595648/195023222-d204a2c0-8665-4f1b-b560-0cd52c674639.png">
<img width="563" alt="Screenshot 2022-10-11 at 09 09 59" src="https://user-images.githubusercontent.com/112595648/195034846-4dc7d6fb-07f3-402a-bce5-a6997978b3eb.png">
<img width="570" alt="Screenshot 2022-10-11 at 09 21 13" src="https://user-images.githubusercontent.com/112595648/195037520-fc565d85-666b-49c9-b58c-286bf1cd4d1c.png">
![Screenshot 2022-10-11 at 09 22 00](https://user-images.githubusercontent.com/112595648/195037665-c0e0776a-3566-4bf7-8cd0-3e9fdd47fbcd.png)
<img width="570" alt="Screenshot 2022-10-11 at 09 52 25" src="https://user-images.githubusercontent.com/112595648/195044877-233d4c4b-a67c-4204-a41a-a0441e8dd186.png">
![Screenshot 2022-10-11 at 09 53 26](https://user-images.githubusercontent.com/112595648/195045027-7383c7f2-c387-4837-af8b-f68132093d59.png)
![Screenshot 2022-10-11 at 12 04 24](https://user-images.githubusercontent.com/112595648/195074076-bfb68638-1825-406d-9b2e-b1d90b4042f1.png)
<img width="714" alt="Screenshot 2022-10-12 at 14 02 00" src="https://user-images.githubusercontent.com/112595648/195349789-3c037780-a57b-413c-8487-122092ad3731.png">
<img width="710" alt="Screenshot 2022-10-12 at 14 01 11" src="https://user-images.githubusercontent.com/112595648/195349838-8aac9e9b-5a01-4ee8-a09f-eac2e8255598.png">
<img width="709" alt="Screenshot 2022-10-12 at 14 41 57" src="https://user-images.githubusercontent.com/112595648/195358801-3e60600f-a043-48a1-ac19-5c7c053a225d.png">
<img width="570" alt="Screenshot 2022-10-12 at 14 42 08" src="https://user-images.githubusercontent.com/112595648/195358876-5fab6be3-e7aa-4bdc-8e03-87263026ed70.png">
<img width="710" alt="Screenshot 2022-10-12 at 14 54 51" src="https://user-images.githubusercontent.com/112595648/195362110-2027eca4-a17d-447c-a6b4-e0a4202a739d.png">
<img width="713" alt="Screenshot 2022-10-12 at 15 13 15" src="https://user-images.githubusercontent.com/112595648/195366705-377153db-f158-491d-ac5b-78d4aa9c65ba.png">
<img width="708" alt="Screenshot 2022-10-12 at 15 12 47" src="https://user-images.githubusercontent.com/112595648/195366757-c6ee448e-b190-4770-9682-3d360d122202.png">
<img width="712" alt="Screenshot 2022-10-12 at 15 21 45" src="https://user-images.githubusercontent.com/112595648/195368731-d1576668-1351-4ecd-b7ae-25a5493ec81b.png">
<img width="711" alt="Screenshot 2022-10-12 at 15 39 01" src="https://user-images.githubusercontent.com/112595648/195372977-5393c394-7cc1-42b5-a02b-d838e5ffe235.png">
![Screenshot 2022-10-12 at 15 42 22](https://user-images.githubusercontent.com/112595648/195373904-0dcc796a-b5d1-400a-bbdd-2db0a718741a.png)
<img width="717" alt="Screenshot 2022-10-12 at 15 58 16" src="https://user-images.githubusercontent.com/112595648/195377688-4d77bc06-6640-4d23-96fe-b8452dcc0dd6.png">
![Screenshot 2022-10-12 at 16 17 21](https://user-images.githubusercontent.com/112595648/195382183-c69462e5-e038-4bda-a45e-956c51b1e265.png)
<img width="591" alt="Screenshot 2022-10-12 at 17 17 46" src="https://user-images.githubusercontent.com/112595648/195395784-2bc57e85-6e73-4a81-98ee-7a0848c4937e.png">
<img width="587" alt="Screenshot 2022-10-12 at 17 31 28" src="https://user-images.githubusercontent.com/112595648/195398577-3f914def-0241-4db5-8151-c65614679a82.png">
<img width="584" alt="Screenshot 2022-10-12 at 19 45 22" src="https://user-images.githubusercontent.com/112595648/195423375-2f097e16-6db5-42a7-99b4-28d1a84a2750.png">
<img width="560" alt="Screenshot 2022-10-12 at 20 24 41" src="https://user-images.githubusercontent.com/112595648/195430358-19bb834a-a621-48b4-99c6-5dbfec47bbfc.png">
<img width="548" alt="Screenshot 2022-10-12 at 20 25 21" src="https://user-images.githubusercontent.com/112595648/195430486-658044de-a0b1-4874-8b75-69b48fd2d5cb.png">


