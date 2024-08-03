<div align="center">
  
# LLM Inference Service Deployment - Ollama

![image](https://github.com/user-attachments/assets/4deab5fb-e31c-4da4-ab15-481803c9fab2)

</div>
In this project, I developed a scalable LLM inference service using Ollama and deployed it on AWS EKS. I started by creating a Dockerfile and Flask API wrapper, resolved issues with Docker build by using a `start.sh` script, and successfully ran the container. For deployment, I used AWS EKS for its managed services and integrated it with a CI/CD pipeline for continuous updates. I performed load testing with K6, optimized performance by upgrading EC2 instance types, and implemented Horizontal Pod Autoscaler (HPA) to dynamically adjust resources based on traffic. This approach significantly improved system performance and scalability, ensuring reliable handling of varying loads.

## Development
- Docker Container: Created a Dockerfile and Flask API wrapper for the LLM inference service.
- Script for Docker Build: Implemented a start.sh script to address Docker build issues and ensure successful container execution.

## Deployment
- AWS EKS: Deployed the Docker container to AWS EKS for its managed services and scalability.
- CI/CD Integration: Set up a CI/CD pipeline to automate continuous updates and deployments.

## Performance Optimization
- Load Testing: Conducted load testing using K6 to assess performance and identify bottlenecks.
- Resource Optimization: Upgraded EC2 instance types to enhance performance.
- Horizontal Pod Autoscaler (HPA): Implemented HPA to dynamically adjust resources based on traffic, improving scalability and reliability.

## Results
- The deployment approach significantly enhanced system performance and scalability, ensuring robust handling of varying loads and maintaining high availability.
