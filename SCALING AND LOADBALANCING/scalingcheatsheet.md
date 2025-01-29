# Exam Preparation Cheat Sheet for Horizontal Scaling, Vertical Scaling, ELB, and Load Balancing Algorithms

---

### 1. Horizontal Scaling

- **Definition**:  
  Adding more servers (instances) to handle increased load.

- **Purpose**:  
  Distributes traffic across multiple servers to improve performance and availability.

- **Real-World Example**:  
  Adding more cash registers in a store during a sale to handle more customers.

- **Similar Analogy**:  
  Like hiring more workers to serve more customers in a restaurant.

---

### 2. Vertical Scaling

- **Definition**:  
  Increasing the resources (CPU, RAM, etc.) of an existing server.

- **Purpose**:  
  Enhances the server’s performance to handle more load without adding new servers.

- **Real-World Example**:  
  Upgrading your computer with more RAM or a better processor to run faster.

- **Analogy**:  
  Like upgrading your car's engine to make it faster instead of buying a new car.

---

### 3. ELB (Elastic Load Balancer)

- **Definition**:  
  ELB is an AWS service that automatically distributes incoming traffic across multiple targets (e.g., EC2 instances).

- **Purpose**:  
  It ensures no single server gets overloaded, improving availability and fault tolerance.

- **Real-World Example**:  
  ELB is like a traffic cop directing cars to different lanes to avoid congestion.

- **Analogy**:  
  Like a chef distributing tasks to different cooks in a kitchen to ensure efficient service.

---

### 4. Load Balancing Algorithms

- **Definition**:  
  Algorithms used by load balancers to decide how to distribute traffic among servers.

- **Purpose**:  
  To optimize performance and prevent overloading any single server.

- **Types**:

  - **Round Robin**:
    - **Definition**: Distributes requests evenly across all servers in a circular order.
    - **Real-World Example**:  
      In a cafeteria, a worker serves each customer in turn, without prioritizing anyone.
    - **Analogy**:  
      Like a relay race where each runner takes a turn, passing the baton evenly to the next runner.

  - **Least Connections**:
    - **Definition**: Routes traffic to the server with the fewest active connections.
    - **Real-World Example**:  
      A bus station assigns passengers to buses that aren’t crowded yet.
    - **Analogy**:  
      Like a manager assigning tasks to employees with the least amount of work left.

  - **IP Hash**:
    - **Definition**: Routes requests based on the client’s IP address, ensuring the same client is routed to the same server.
    - **Real-World Example**:  
      A restaurant assigns specific tables to regular customers based on their reservation history, ensuring consistency.
    - **Analogy**:  
      Like a library card system where a specific customer always gets their favorite librarian.

  - **Weighted Round Robin**:
    - **Definition**: Similar to round robin, but some servers are given more traffic based on their capacity or weight.
    - **Real-World Example**:  
      In a relay race, faster runners (heavier weights) run more laps than slower ones.
    - **Analogy**:  
      Like a work team where more experienced workers are assigned more tasks than those just starting out.

  - **Least Response Time**:
    - **Definition**: Routes traffic to the server with the fastest response time.
    - **Real-World Example**:  
      A call center routes calls to the employee with the fastest response rate.
    - **Analogy**:  
      Like choosing a cashier with the shortest line to save time.

---
