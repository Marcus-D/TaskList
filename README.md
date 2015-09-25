# TaskList
Creates a task list file reader that sets priorities to tasks and organizes them accordingly

/****************************************************
 * Program: TaskList.java							*
 * Author: Kevin Shelley							*
 * Date started: 09/24/2015							*
 * Last Edit: 09/25/2015							*
 * Brief Description: Implements a list of priorit- *
 * 	ies by using both the LinkedList list and Task  *
 * 	objects											*
 ****************************************************/

import LinkedTaskList.Task;

public class TaskList {
	public static void main(String[] args) {
		
		/****************************************************
		 * Assume file read has the following format:		*
		 * 1. Task 1										*
		 * 2. Task 2										*
		 * 	...												*
		 * This way, we can read the index of the array and *
		 * use that index to create the delimiter			*
		 ****************************************************/
		
		//size will be determined by file
		//10 is a temporary size
		Task[] task = new Task[10];
	}
}
