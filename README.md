//Teacher-Student-Problem-Using-Semaphores
//Simulation of Teacher Student Process synchronization in C using P threads specification.
 sem_t Pen_and_Paper;
sem_t Paper_and_questionPaper;//Semaphores can be used to remember the materials put on the table by the teacher
sem_t Pen_and_questionPaper;//and hence signal to the required student.
sem_t Done_Assignment;
