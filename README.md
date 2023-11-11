# ML-end-to-end-project-
End to end machine learning project with Docker Github actions and deployment


- Creating a new environment
'''
- conda create -p env python==3.7 -y

'''
#  useful Docker commands 
'''
1. docker build -f Dockerfile -t <docker_image_name> .

2. docker images

3. docker run -p 8080:8080 <docker_image_name>
4. docker run -d -p 8080:8080 <docker_image_name> 

'''

