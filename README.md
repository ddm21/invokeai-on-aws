# AWS Instance Setup for Stable Disunion Project

This guide provides instructions on setting up an AWS instance for hosting Invokeai Project. We'll use the **g4dn.xlarge** instance type.

## Instance Type
- **Instance Type:** G4dn.xlarge
- **GPU:** NVIDIA Tesla T4
- **GPU Memory:** 16GB
- **RAM:** 16GB

## Configuration Steps

### Step 1: Launch the G4dn.xlarge Instance
1. Log in to your AWS Management Console.
2. Navigate to the EC2 service.
3. Click "Launch Instance."

### Step 2: Choose an Amazon Machine Image (AMI)
1. Search for an AMI that supports Python 3.10.6 and meets your project requirements.

### Step 3: Choose an Instance Type
1. Select "g4dn.xlarge."

### Step 4: Add Sufficient Storage
1. Configure the instance with at least 100GB of storage to accommodate your project files and models.

### Step 5: Add Tags (Optional)
1. You can add tags for better organization.

### Step 6: Configure Security Group
1. Create or select a security group that allows the necessary inbound traffic to your instance.

### Step 7: Review and Launch
1. Review your instance configuration to ensure it meets your project's requirements.
2. Click "Launch."

### Step 8: Key Pair
1. Choose an existing key pair or create a new one for secure instance access.

### Step 9: Launch Instances
1. Click "Launch Instances" to initiate the instance setup.

Once your instance is running, you can connect to it and install Python 3.10.6 as specified for your project.

Best of luck with your AWS setup and experimentation!
