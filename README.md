Banking Data Management System using Hash Functions 🏦

A high-performance banking records management system built in C++ that leverages advanced hashing techniques to enable constant-time data retrieval for millions of customer records. Designed with multiple collision resolution strategies (chaining, linear probing, quadratic probing, cubic probing) and file persistence for durability.

💡 Problem Statement
In large-scale banking systems, retrieving customer data from traditional databases can become a bottleneck when datasets scale. This project demonstrates how custom-built hash tables can drastically improve lookup efficiency in such scenarios.

🔧 Features
Add, delete, and search for customer records
Multiple collision resolution strategies: chaining, linear probing, quadratic probing, cubic probing
File-based persistence for secure data storage
Performance benchmarking between collision strategies
CLI interface for quick testing and debugging

🛠️ Tech Stack
Language: C++

Concepts: Hash Tables, File Handling, Collision Resolution, O(1) Average Lookup

📊 Performance Example
Dataset Size	Linear Probing	Quadratic Probing	Chaining
1M records	0.42s	0.38s	0.55s

🚀 How to Run
# Clone the repository
git clone https://github.com/yourusername/banking-data-management-hashing.git
cd banking-data-management-hashing

# Compile
g++ tester.cpp Chaining.cpp LinearProbing.cpp QuadraticProbing.cpp CubicProbing.cpp -o banking_system

# Run
./banking_system
📝 Sample Output
mathematica
1. Add Customer
2. Search Customer
3. Delete Customer
4. Exit

Enter choice: 1
Enter Account Number: 10234
Enter Name: John Doe
Customer added successfully!
📌 Note
This project is for educational purposes only. All customer data in the repository is fictional.
