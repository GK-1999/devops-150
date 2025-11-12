# DAY 1: Production Network Foundation

## Infrastructure
- **VPC**: `dark-vpc` | `10.0.0.0/16`
- **Subnets**:
  - `dark-subnet-a` → `10.0.1.0/24` → `ap-south-1a`
  - `dark-subnet-b` → `10.0.2.0/24` → `ap-south-1b`
- **Internet Gateway**: `dark-igw` → Attached
- **Route Table**: `dark-route-table` → `0.0.0.0/0 → igw`
- **Associations**: Both subnets

## Proof
- Screenshots in `/screenshots`