# Osquery: The Basics – TryHackMe  

This repository contains my notes and screenshots from the [TryHackMe room: Osquery - The Basics](https://tryhackme.com/room/osquerythebasics).  

## 📝 Room Overview  
- Learn how to use **Osquery** to query system information  
- Understand the basic commands and SQL-style queries  
- Practice monitoring processes, users, and network activity  

## ✅ Tasks Completed  
1. **Introduction to Osquery**  
   - Installed and launched `osqueryi` interactive shell  
   - Checked available tables with `.tables`  
   - Viewed schema with `.schema`  

2. **System Information**  
   - Queried OS version  
   - Gathered system uptime and hostname  

3. **Users & Processes**  
   - Listed all logged-in users  
   - Displayed running processes  
   - Monitored active services  

4. **Networking**  
   - Queried open network connections  
   - Checked listening ports  

5. **Filesystem**  
   - Found executable binaries  
   - Checked file integrity metadata  

## 📸 Screenshots  
<img width="1900" height="972" alt="Screenshot 2025-09-09 at 8 58 23 PM" src="https://github.com/user-attachments/assets/bd9e998f-2141-4fc4-a817-d745f5a1b9db" />
<img width="1900" height="972" alt="Screenshot 2025-09-09 at 9 00 06 PM" src="https://github.com/user-attachments/assets/be54aa05-0ffa-420b-8636-d714f1c9c804" />
<img width="1853" height="963" alt="Screenshot 2025-09-11 at 8 55 16 PM" src="https://github.com/user-attachments/assets/e85ae0df-0e27-42fd-a461-f58eb46f34a9" />
<img width="1853" height="963" alt="Screenshot 2025-09-11 at 8 53 52 PM" src="https://github.com/user-attachments/assets/0739b073-41ff-4381-b289-725662be01e1" />
<img width="1853" height="963" alt="Screenshot 2025-09-11 at 8 51 33 PM" src="https://github.com/user-attachments/assets/052c2890-eca4-429b-9e92-aaf45d1f3f44" />
<img width="1853" height="963" alt="Screenshot 2025-09-11 at 8 51 15 PM" src="https://github.com/user-attachments/assets/f29fb544-7aee-4b96-87de-cf07af06550a" />

<img width="1865" height="932" alt="Screenshot 2025-09-12 at 4 04 39 PM" src="https://github.com/user-attachments/assets/ed8a93fe-e983-455d-92d6-4e7e827e9bee" />
<img width="1865" height="932" alt="Screenshot 2025-09-12 at 4 12 39 PM" src="https://github.com/user-attachments/assets/626139e5-d20a-48ca-a4ca-af045b17bd10" />
<img width="1865" height="932" alt="Screenshot 2025-09-12 at 4 15 18 PM" src="https://github.com/user-attachments/assets/5d69d7e6-c079-4a9a-a8bc-a354cff0e28c" />
<img width="1865" height="932" alt="Screenshot 2025-09-12 at 4 16 30 PM" src="https://github.com/user-attachments/assets/e1543b8d-7a4f-4a72-88d0-3b988e980c9e" />
<img width="1865" height="932" alt="Screenshot 2025-09-12 at 4 18 34 PM" src="https://github.com/user-attachments/assets/a2997837-8684-4d9f-9a17-dbf08aca59d3" />

<img width="1745" height="966" alt="Screenshot 2025-09-13 at 9 56 47 PM" src="https://github.com/user-attachments/assets/bf5f93a7-97ef-4d78-915e-441e82e0790f" />

<img width="1745" height="966" alt="Screenshot 2025-09-13 at 9 57 02 PM" src="https://github.com/user-attachments/assets/2fd4d918-cf76-4d98-957f-664482b96e62" />

<img width="1745" height="966" alt="Screenshot 2025-09-13 at 9 58 57 PM" src="https://github.com/user-attachments/assets/59ca6b79-9836-414d-a03d-fd0364c8475d" />
<img width="1745" height="966" alt="Screenshot 2025-09-13 at 10 00 09 PM" src="https://github.com/user-attachments/assets/dbdd8251-1dd9-48c6-a128-c08ab98ce403" />

<img width="1745" height="966" alt="Screenshot 2025-09-13 at 10 03 05 PM" src="https://github.com/user-attachments/assets/59d0b70a-cea2-43c6-aec0-4f562a4c19fa" />

<img width="1745" height="966" alt="Screenshot 2025-09-13 at 10 05 29 PM" src="https://github.com/user-attachments/assets/e1758971-fc97-4315-8f04-74298dc177cd" />







## 🚀 Notes  
- Osquery uses **SQL-like syntax** to query system data.  
- Helpful commands:  
  ```bash
  osqueryi        # Start interactive shell
  .tables         # List available tables
  .schema users   # View schema for 'users' table
  SELECT * FROM users;  # Example query
  select gid, uid, description, username, directory from users;
