# Upload largest database via cpanel terminal

### Step 1: Upload sql file inside public_html/any_folder 

### Step 2: Verify file via terminal
```bash
cd public_html/any_folder
ls
```

### Step 3: Run Sql import code via terminal
```bash
mysql -u database_user_name -p database_name < /home/user_name/public_html/any_folder/database.sql
```

### Step 4: Verify the database import
```bash
mysql -u database_username -p
USE database_name;
```

### Step 5: Finally Show Tables in terminal
```bash
SHOW TABLES;
```


