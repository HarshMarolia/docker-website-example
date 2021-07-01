# Learning to Dockerize 

<div align="center"><img src="./res/doc.gif"></div>

## Execution
1. Clone the repository on your system.
   
2. Open terminal inside your cloned project folder and paste the following commands:
   
3. ```bash
   docker build -t smoke_effect .
   ```
   ```bash
   docker run -p 5000:80 -d smoke_effect
   ```
4. The application runs on http://localhost:5000.