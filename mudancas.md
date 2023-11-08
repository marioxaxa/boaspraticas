FlawFinder:
FINAL RESULTS:

kanccp/include/utils/Menu.hpp:214:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:305:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:363:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:370:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:386:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:436:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:441:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:491:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:495:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:500:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:511:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:558:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:581:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:598:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/include/utils/Menu.hpp:608:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/src/main.cpp:14:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/src/main.cpp:59:  [4] (shell) system:
  This causes a new program to execute and is difficult to use safely
  (CWE-78). try using a library call that implements the same functionality
  if available.
kanccp/src/Board.cpp:59:  [2] (buffer) char:
  Statically-sized arrays can be improperly restricted, leading to potential
  overflows or other issues (CWE-119!/CWE-120). Perform bounds checking, use
  functions that limit length, or ensure that the size is larger than the
  maximum possible length.
kanccp/src/Board.cpp:209:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Board.cpp:211:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Board.cpp:213:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Board.cpp:215:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Board.cpp:217:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/BugTask.cpp:70:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:212:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:214:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:221:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:223:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:225:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:227:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:229:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:232:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Column.cpp:239:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/FeatureTask.cpp:70:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/FeatureTask.cpp:72:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:165:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:167:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:175:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:177:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:180:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:182:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:184:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:185:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:186:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:189:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/Task.cpp:191:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).
kanccp/src/TestTask.cpp:82:  [1] (buffer) read:
  Check buffer boundaries if used in a loop including recursive loops
  (CWE-120, CWE-20).

ANALYSIS SUMMARY:

Hits = 47
Lines analyzed = 3378 in approximately 0.06 seconds (60639 lines/second)
Physical Source Lines of Code (SLOC) = 2084
Hits@level = [0]   0 [1]  29 [2]   1 [3]   0 [4]  17 [5]   0
Hits@level+ = [0+]  47 [1+]  47 [2+]  18 [3+]  17 [4+]  17 [5+]   0
Hits/KSLOC@level+ = [0+] 22.5528 [1+] 22.5528 [2+] 8.63724 [3+] 8.15739 [4+] 8.15739 [5+]   0
Dot directories skipped = 2 (--followdotdir overrides)
Minimum risk level = 1

Not every hit is necessarily a security vulnerability.
You can inhibit a report by adding a comment in this form:
// flawfinder: ignore
Make *sure* it's a false positive!
You can use the option --neverignore to show these.

There may be other security vulnerabilities; review your code!
See 'Secure Programming HOWTO'
(https://dwheeler.com/secure-programs) for more information.






CppCheck:
Checking kanccp/src/Board.cpp ...
kanccp/include/utils/Sort.hpp:47:21: style: Array index 'i' is used before limits check. [arrayIndexThenCheck]
    	while (array[i] < pivot && j >= i)
                	^
kanccp/src/Board.cpp:19:8: warning: Member variable 'Board::columns' is not initialized in the constructor. [uninitMemberVar]
Board::Board(string name)
   	^
kanccp/src/Board.cpp:14:9: warning: Class 'Board' does not have a copy constructor which is recommended since it has dynamic memory/resource allocation(s). [noCopyConstructor]
  this->columns = new DoublyLinkedList<Column>();
    	^
kanccp/src/Board.cpp:14:9: warning: Class 'Board' does not have a operator= which is recommended since it has dynamic memory/resource allocation(s). [noOperatorEq]
  this->columns = new DoublyLinkedList<Column>();
    	^
kanccp/include/BugTask.h:24:5: style: Class 'BugTask' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	BugTask(int priority);
	^
kanccp/include/FeatureTask.h:21:5: style: Class 'FeatureTask' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	FeatureTask(std::string project);
	^
kanccp/include/TestTask.h:45:5: style: Class 'TestTask' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	TestTask(std::string title);
	^
kanccp/include/TestTask.h:51:5: style: Class 'TestTask' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	TestTask(FeatureTask *feature);
	^
kanccp/include/Column.h:59:5: style: Class 'Column' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	Column(const string &name);
	^
kanccp/include/utils/DoublyLinkedList/Node.hpp:32:5: style: Class 'Node' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	Node(T *value);
	^
kanccp/include/Board.h:43:5: style: Class 'Board' has a constructor with 1 argument that is not explicit. [noExplicitConstructor]
	Board(string name);
	^
kanccp/include/BugTask.h:70:10: style: The function 'print' overrides a function in a base class but is not marked with a 'override' specifier. [missingOverride]
	void print();
     	^
kanccp/include/Task.h:134:18: note: Virtual function in base class
	virtual void print() = 0;
             	^
kanccp/include/BugTask.h:70:10: note: Function in derived class
	void print();
     	^
kanccp/include/TestTask.h:91:10: style: The function 'print' overrides a function in a base class but is not marked with a 'override' specifier. [missingOverride]
	void print();
     	^
kanccp/include/Task.h:134:18: note: Virtual function in base class
	virtual void print() = 0;
             	^
kanccp/include/TestTask.h:91:10: note: Function in derived class
	void print();
     	^
kanccp/include/Column.h:46:25: performance: Function parameter 'name' should be passed by const reference. [passedByValue]
	Column(const string name, const string description, const int order);
                    	^
kanccp/include/Column.h:46:44: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
	Column(const string name, const string description, const int order);
                                       	^
kanccp/src/Board.cpp:10:21: performance: Function parameter 'name' should be passed by const reference. [passedByValue]
Board::Board(string name, string description)
                	^
kanccp/src/Board.cpp:10:34: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
Board::Board(string name, string description)
                             	^
kanccp/src/Board.cpp:19:21: performance: Function parameter 'name' should be passed by const reference. [passedByValue]
Board::Board(string name)
                	^
kanccp/src/Board.cpp:121:37: performance: Function parameter 'id' should be passed by const reference. [passedByValue]
Column *Board::getColumnById(string id)
                                	^
kanccp/src/Board.cpp:151:36: performance: Function parameter 'id' should be passed by const reference. [passedByValue]
Task *Board::searchTaskById(string id)
                               	^
kanccp/include/utils/Sort.hpp:120:18: warning: Using 'sizeof' on array given as function argument returns size of a pointer. [sizeofwithsilentarraypointer]
	int length = sizeof(array) / sizeof(array[0]);
             	^
1/8 files checked 19% done
Checking kanccp/src/BugTask.cpp ...
kanccp/src/BugTask.cpp:15:25: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
BugTask::BugTask(string title, int priority) : Task(title, "BUG")
                    	^
kanccp/src/BugTask.cpp:20:25: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
BugTask::BugTask(string title, string description, int priority) : Task(title, description, "BUG")
                    	^
kanccp/src/BugTask.cpp:20:39: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
BugTask::BugTask(string title, string description, int priority) : Task(title, description, "BUG")
                                  	^
kanccp/src/BugTask.cpp:25:25: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
BugTask::BugTask(string title, string description, tm deadline, int priority) : Task(title, description, deadline, "BUG")
                    	^
kanccp/src/BugTask.cpp:25:39: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
BugTask::BugTask(string title, string description, tm deadline, int priority) : Task(title, description, deadline, "BUG")
                                  	^
2/8 files checked 26% done
Checking kanccp/src/Column.cpp ...
kanccp/src/Column.cpp:10:29: performance: Function parameter 'name' should be passed by const reference. [passedByValue]
Column::Column(const string name, const string description, const int order)
                        	^
kanccp/src/Column.cpp:10:48: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
Column::Column(const string name, const string description, const int order)
                                           	^
kanccp/src/Column.cpp:67:29: performance: Function parameter 'name' should be passed by const reference. [passedByValue]
void Column::setName(string name)
                        	^
kanccp/src/Column.cpp:87:36: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
void Column::setDescription(string description)
                               	^
kanccp/src/Column.cpp:278:33: performance: Function parameter 'property' should be passed by const reference. [passedByValue]
void Column::sortTasksBy(string property)
                            	^
kanccp/src/Column.cpp:119:31: style: Parameter 'task' can be declared with const [constParameter]
bool Column::removeTask(Task *task)
                          	^
kanccp/src/Column.cpp:286:9: style: Consider using std::any_of algorithm instead of a raw loop. [useStlAlgorithm]
    	{
    	^
3/8 files checked 55% done
Checking kanccp/src/FeatureTask.cpp ...
kanccp/src/FeatureTask.cpp:7:5: performance: Variable 'project' is assigned in constructor body. Consider performing initialization in initialization list. [useInitializationList]
	project = "";
	^
kanccp/src/FeatureTask.cpp:14:38: performance: Function parameter 'project' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string project) : Task("FEATURE")
                                 	^
kanccp/src/FeatureTask.cpp:19:38: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string project) : Task(title, "FEATURE")
                                 	^
kanccp/src/FeatureTask.cpp:19:57: performance: Function parameter 'project' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string project) : Task(title, "FEATURE")
                                                    	^
kanccp/src/FeatureTask.cpp:24:38: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string description, std::string project) : Task(title, description, "FEATURE")
                                 	^
kanccp/src/FeatureTask.cpp:24:57: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string description, std::string project) : Task(title, description, "FEATURE")
                                                    	^
kanccp/src/FeatureTask.cpp:24:82: performance: Function parameter 'project' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string description, std::string project) : Task(title, description, "FEATURE")
                                                                             	^
kanccp/src/FeatureTask.cpp:29:38: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string description, tm deadline, std::string project) : Task(title, description, deadline, "FEATURE")
                                 	^
kanccp/src/FeatureTask.cpp:29:57: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string description, tm deadline, std::string project) : Task(title, description, deadline, "FEATURE")
                                                    	^
kanccp/src/FeatureTask.cpp:29:95: performance: Function parameter 'project' should be passed by const reference. [passedByValue]
FeatureTask::FeatureTask(std::string title, std::string description, tm deadline, std::string project) : Task(title, description, deadline, "FEATURE")
                                                                                          	^
4/8 files checked 64% done
Checking kanccp/src/Task.cpp ...
kanccp/src/Task.cpp:7:7: warning: Member variable 'Task::deadline' is not initialized in the constructor. [uninitMemberVar]
Task::Task(string type)
  	^
kanccp/src/Task.cpp:7:19: performance: Function parameter 'type' should be passed by const reference. [passedByValue]
Task::Task(string type)
              	^
kanccp/src/Task.cpp:19:19: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
Task::Task(string title, string type)
              	^
kanccp/src/Task.cpp:19:33: performance: Function parameter 'type' should be passed by const reference. [passedByValue]
Task::Task(string title, string type)
                            	^
kanccp/src/Task.cpp:39:19: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
Task::Task(string title, string description, string type)
              	^
kanccp/src/Task.cpp:39:33: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
Task::Task(string title, string description, string type)
                            	^
kanccp/src/Task.cpp:39:53: performance: Function parameter 'type' should be passed by const reference. [passedByValue]
Task::Task(string title, string description, string type)
                                                	^
kanccp/src/Task.cpp:59:19: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
Task::Task(string title, string description, tm deadline, string type)
              	^
kanccp/src/Task.cpp:59:33: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
Task::Task(string title, string description, tm deadline, string type)
                            	^
kanccp/src/Task.cpp:59:66: performance: Function parameter 'type' should be passed by const reference. [passedByValue]
Task::Task(string title, string description, tm deadline, string type)
                                                             	^
kanccp/src/Task.cpp:89:28: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
void Task::setTitle(string title)
                       	^
kanccp/src/Task.cpp:119:34: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
void Task::setDescription(string description)
                             	^
5/8 files checked 81% done
Checking kanccp/src/TestTask.cpp ...
kanccp/src/TestTask.cpp:6:11: warning: Member variable 'TestTask::feature' is not initialized in the constructor. [uninitMemberVar]
TestTask::TestTask() : Task("TEST") {}
      	^
kanccp/src/TestTask.cpp:8:11: warning: Member variable 'TestTask::feature' is not initialized in the constructor. [uninitMemberVar]
TestTask::TestTask(std::string title, std::string description, tm deadline) : Task(title, description, deadline, "TEST") {}
      	^
kanccp/src/TestTask.cpp:10:11: warning: Member variable 'TestTask::feature' is not initialized in the constructor. [uninitMemberVar]
TestTask::TestTask(std::string title, std::string description) : Task(title, description, "TEST") {}
      	^
kanccp/src/TestTask.cpp:12:11: warning: Member variable 'TestTask::feature' is not initialized in the constructor. [uninitMemberVar]
TestTask::TestTask(std::string title) : Task(title, "TEST") {}
      	^
kanccp/src/TestTask.cpp:8:32: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description, tm deadline) : Task(title, description, deadline, "TEST") {}
                           	^
kanccp/src/TestTask.cpp:8:51: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description, tm deadline) : Task(title, description, deadline, "TEST") {}
                                              	^
kanccp/src/TestTask.cpp:10:32: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description) : Task(title, description, "TEST") {}
                           	^
kanccp/src/TestTask.cpp:10:51: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description) : Task(title, description, "TEST") {}
                                              	^
kanccp/src/TestTask.cpp:12:32: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title) : Task(title, "TEST") {}
                           	^
kanccp/src/TestTask.cpp:19:32: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description, tm deadline, FeatureTask *feature) : Task(title, description, deadline, "TEST")
                           	^
kanccp/src/TestTask.cpp:19:51: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description, tm deadline, FeatureTask *feature) : Task(title, description, deadline, "TEST")
                                              	^
kanccp/src/TestTask.cpp:24:32: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description, FeatureTask *feature) : Task(title, description, "TEST")
                           	^
kanccp/src/TestTask.cpp:24:51: performance: Function parameter 'description' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, std::string description, FeatureTask *feature) : Task(title, description, "TEST")
                                              	^
kanccp/src/TestTask.cpp:29:32: performance: Function parameter 'title' should be passed by const reference. [passedByValue]
TestTask::TestTask(std::string title, FeatureTask *feature) : Task(title, "TEST")
                           	^
6/8 files checked 91% done
Checking kanccp/src/formatters/Date.cpp ...
7/8 files checked 92% done
Checking kanccp/src/main.cpp ...
kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:147:5: warning: Class 'DoublyLinkedList < Column >' does not have a copy constructor which is recommended since it has dynamic memory/resource allocation(s). [noCopyConstructor]
	head = new Node<T>();
	^
kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:147:5: warning: Class 'DoublyLinkedList < Column >' does not have a operator= which is recommended since it has dynamic memory/resource allocation(s). [noOperatorEq]
	head = new Node<T>();
	^
kanccp/include/utils/Menu.hpp:619:27: warning: Logical conjunction always evaluates to false: option < 1 && option > 3. [incorrectLogicOperator]
    	while (option < 1 && option > 3)
                      	^
kanccp/include/utils/Menu.hpp:450:17: style: The scope of the variable 'order' can be reduced. [variableScope]
        	int order;
            	^
Function parameter 'x' should be passed by const reference: 

kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:190:35: performance: Function parameter 'element' should be passed by const reference. [passedByValue]
int DoublyLinkedList<T>::search(T element)
                              	^
kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:205:42: performance: Function parameter 'element' should be passed by const reference. [passedByValue]
bool DoublyLinkedList<T>::insertSorted(T element)
                                     	^
kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:228:42: performance: Function parameter 'element' should be passed by const reference. [passedByValue]
bool DoublyLinkedList<T>::insertAtHead(T element)
                                     	^
kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:260:49: performance: Function parameter 'element' should be passed by const reference. [passedByValue]
bool DoublyLinkedList<T>::insertAt(int index, T element)
                                            	^
kanccp/include/utils/DoublyLinkedList/DoublyLinkedList.hpp:351:36: performance: Function parameter 'element' should be passed by const reference. [passedByValue]
bool DoublyLinkedList<T>::remove(T element)
                               	^
8/8 files checked 100% done

# The function ‘Foo()’ is never used: Todos os erros abaixo podem ser evitados excluindo as funções do código, visto que essas não possuem uso.

kanccp/src/Board.cpp:90:0: style: The function 'addTaskToBacklog' is never used. [unusedFunction]

^
kanccp/src/Board.cpp:57:0: style: The function 'displayCreatedAt' is never used. [unusedFunction]

^
kanccp/src/Board.cpp:95:0: style: The function 'removeTaskFromBacklog' is never used. [unusedFunction]

^
kanccp/src/Column.cpp:67:0: style: The function 'setName' is never used. [unusedFunction]

^
kanccp/src/BugTask.cpp:39:0: style: The function 'setPriority' is never used. [unusedFunction]

^
nofile:0:0: information: Cppcheck cannot find all the include files (use --check-config for details) [missingIncludeSystem]

