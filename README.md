
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


## 🚀 Notes  
- Osquery uses **SQL-like syntax** to query system data.  
- Helpful commands:  
  ```bash
  osqueryi        # Start interactive shell
  .tables         # List available tables
  .schema users   # View schema for 'users' table
  SELECT * FROM users;  # Example query
