
/*******************************************************************************************

File Name       :   CSLAB_THREAD_METHOD_SETNAME_V1
Purpose 	:   A Program for Thread SetName Method in Scala
Author		:   Durga Prasad
Reviewer 	:   Jothi Periasamy
Date and Time	:   13/02/2019 21:17 hrs
Version		:   1.0	
Change History 	: 

____________________________________________________________________________________________

	Who				   When 			  Why
____________________________________________________________________________________________


	DP				13/02/2019		    Initital Release 

____________________________________________________________________________________________


/*******************************************************************************************

## Program Description : A Program for Thread SetName Method in Scala

## Scala Development Environment & Runtime - Eclipse IDE, Anaconda, Jupyter

class ThreadExample() extends Thread{  
    
override def run(){  
    
for(vAR_CSLAB_i<- 0 to 5){  
    
println(this.getName()+" - "+vAR_CSLAB_i)  
    
Thread.sleep(500)  

}  

}  

}  
  
object MainObject{  
    
def main(args:Array[String]){  
    
var vAR_CSLAB_t1 = new ThreadExample()  
    
var vAR_CSLAB_t2 = new ThreadExample()  
    
var vAR_CSLAB_t3 = new ThreadExample()  
    
vAR_CSLAB_t1.setName("First Thread")  
    
vAR_CSLAB_t2.setName("Second Thread")  
    
vAR_CSLAB_t1.start()  
    
vAR_CSLAB_t2.start()  
    
}  

}  


MainObject.main(Array(""))


/*******************************************************************************************
  Disclaimer.

      We are providing this code block strictly for learning and researching, this is not a 
production ready code. We have no liability on this particular code under any circumstances; 
users should use this code on their own risk. All software, hardware and othr products that 
are referenced in these materials belong to the respective vendor who developed or who owns 
this product.

/*******************************************************************************************
  
