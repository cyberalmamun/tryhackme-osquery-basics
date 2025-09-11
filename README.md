
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




## 🚀 Notes  
- Osquery uses **SQL-like syntax** to query system data.  
- Helpful commands:  
  ```bash
  osqueryi        # Start interactive shell
  .tables         # List available tables
  .schema users   # View schema for 'users' table
  SELECT * FROM users;  # Example query
  select gid, uid, description, username, directory from users;
