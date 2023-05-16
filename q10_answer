#!/bin/bash

# Create directories
mkdir -p final/src
mkdir -p final/data/main
mkdir -p final/data/backup
mkdir -p final/config

# Move files to the appropriate directories
mv main.cpp final/src/
mv header.h final/src/
mv mainDB.db final/data/main/
mv backupDB.db final/data/backup/
mv config.yml final/config/
mv README.MD final/

# Print tree structure before and after
echo "Tree structure before running the script:"
tree

echo "Tree structure after running the script:"
tree final
