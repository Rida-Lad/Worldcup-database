# 🏆 World Cup Database (PostgreSQL)

A complete database solution for World Cup tournament data, featuring:
- PostgreSQL database setup (`worldcup.sql`)
- Bash scripts for data insertion (`insert_data.sh`) and queries (`queries.sh`)
- Created for freeCodeCamp's Relational Database Certification

## 📂 Project Files
| File | Purpose |
|------|---------|
| `worldcup.sql` | Database dump with all schema and data |
| `insert_data.sh` | Bash script to insert match data |
| `queries.sh` | Bash script to run tournament queries |

## 🚀 Quick Start
```bash
# 1. Clone repository
git clone https://github.com/Rida-Lad/world-cup-database.git
cd world-cup-database

# 2. Import database (PostgreSQL required)
psql -U postgres -f worldcup.sql

# 3. Make scripts executable
chmod +x insert_data.sh queries.sh

# 4. Run scripts
./insert_data.sh   # Insert data
./queries.sh      # Get statistics
```
## 📜 Certification
Part of freeCodeCamp's Relational Database Course
