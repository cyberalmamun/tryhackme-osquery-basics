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
*(Proof of completion will be added here)*  

- Task 1: [screenshot]  
- Task 2: [screenshot]  
- Task 3: [screenshot]  
- Task 4: [screenshot]  
- Task 5: [screenshot]  

## 🚀 Notes  
- Osquery uses **SQL-like syntax** to query system data.  
- Helpful commands:  
  ```bash
  osqueryi        # Start interactive shell
  .tables         # List available tables
  .schema users   # View schema for 'users' table
  SELECT * FROM users;  # Example query
