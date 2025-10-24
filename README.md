VPC (10.0.0.0/16)
│
├── Public Subnet (10.0.1.0/24)   → EC2 Instance + Internet Access
│
├── Private Subnet (10.0.2.0/24)  → Internal Resources (No direct Internet access)
│
└── Internet Gateway (IGW) → Connected to Route Table
