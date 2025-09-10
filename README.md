
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



## 🚀 Notes  
- Osquery uses **SQL-like syntax** to query system data.  
- Helpful commands:  
  ```bash
  osqueryi        # Start interactive shell
  .tables         # List available tables
  .schema users   # View schema for 'users' table
  SELECT * FROM users;  # Example query
  select gid, uid, description, username, directory from users;
