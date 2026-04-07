## What is Docker?
- Open-source container runtime
- Support Mac, Window & Linux
- Dockerfile file format for building container images
- Windows let you run Windows and Linux containers

## Management Commands

![alt text](image.png)

## Running & Stopping Commands
![alt text](image-1.png)

```!Notes:```
1. Command Notes

    | Command  | Note     |
    |----------|----------|
    |``docker run -d [imageName]``    | Run containers in the background   | 
    |``docker stop [containerName]``    | Stop containers (They are still in memory)   | 
    |``docker kill [containerName]``    | Kill containers (If they might be stucked in the memory)   | 


2. Image Name vs Container Name
![alt text](image-2.png)

## Limits Commands
![alt text](image-3.png)

## Running Containers
![alt text](image-4.png)

## Attach Shell Commands
![alt text](image-5.png)

## Cleaning Up Commands
![alt text](image-6.png)

```!Notes:```
1. Command Notes

    | Command  | Note     |
    |----------|----------|
    |``docker rm [containerName]``    | Remove containers in mem (containers must be stopped state)   | 

## Building Containers Commands
![alt text](image-7.png)

```!Notes:```

![alt text](image-10.png)
[name:tag]: tag usually used to specify version number

### Example
1. Dockerfile -static HTML site
![alt text](image-8.png)

2. Dockerfile - Node Site
![alt text](image-9.png)