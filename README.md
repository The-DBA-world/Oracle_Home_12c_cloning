# Oracle_Home_12c_cloning

Purpose:
The Purpose of this document is to Clone Oracle Database home.

Description:
We may have requirement to clone an Oracle Home, you have all your databases on a single server but run from different Oracle Home for Development and Test. By this we can apply the patches on different env. Separately Or you might wish to have 2 Oracle Homes, so you can patch one and then switch all databases to the patched Oracle Home for minimal downtime.

Procedure:
1) Create the new directory structure for new oracle home
   
![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/019e80bf-2477-45d7-8741-d74e9be0985b)

2) As root user copy the existing oracle home to new location.

![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/41087795-3718-4c38-ac5e-886c0ac95a53)

3) See the cloned home is of same size with current home

![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/6e735c7e-0d92-488b-a10f-743764b1c97a)

4) Clone the oracle home

![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/0c580a32-1b0e-481a-9dfe-d2defdf56029)
![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/3220e944-c799-4ad3-a841-4add73523fcc)

Run root.sh script as root user

![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/e08826c0-7375-4b1f-8a84-1ff53360eeb6)

5) Verify the new home in oracle inventory

![image](https://github.com/The-DBA-world/Oracle_Home_12c_cloning/assets/116766530/a3a1c4b3-b13b-41d1-a0a4-ea95fe0b2891)
