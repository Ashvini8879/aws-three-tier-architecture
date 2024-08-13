# aws-three-tier-architecture
A public ALB routes traffic to web tier EC2 instances running Nginx and React.js, which forward API requests to an internal ALB. This internal ALB directs traffic to Node.js app instances that interact with a multi-AZ Aurora MySQL database. Auto-scaling and load balancing ensure high availability.
