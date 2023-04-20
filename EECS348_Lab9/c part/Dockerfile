#Set the base image to use
FROM gcc:latest

#Copy the C program into the container
COPY Program2_NayyirAhmed.c .

#Compile the C program
RUN gcc -o Program2_NayyirAhmed Program2_NayyirAhmed.c

#Set the command to run when the container starts
CMD ["./Program2_NayyirAhmed"]