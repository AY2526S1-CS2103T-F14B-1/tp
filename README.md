[![CI Status](https://github.com/se-edu/addressbook-level3/workflows/Java%20CI/badge.svg)](https://github.com/se-edu/addressbook-level3/actions)

# _LittleLogBook Project_

![Ui](docs/images/Ui.png)

This is **a project for Software Engineering (SE) Module**.<br>

The AddressBook is named LittleLogBook. LittleLogBook helps Kindergarten
teachers track details about their students, parents and colleagues.


## Background Information:
 
* The project simulates an ongoing software project for a desktop application (called _AddressBook_) used for managing 
contact details.
  * It is **written in OOP fashion**. It provides a **reasonably well-written** code base **bigger** (around 6 KLoC) 
  than what students usually write in beginner-level SE modules, without being overwhelmingly big.
  * It comes with a **reasonable level of user and developer documentation**.
* It is named `AddressBook Level 3` (`AB3` for short) because it was initially created as a part of a series of 
`AddressBook` projects (`Level 1`, `Level 2`, `Level 3` ...).
* For the detailed documentation of this project, see the **[Address Book Product Website](https://se-education.org/addressbook-level3)**.
* This project is a **part of the se-education.org** initiative. 
If you would like to contribute code to this project, see [se-education.org](https://se-education.org/#contributing-to-se-edu) for more info.

## Setting up in Intellij
Prerequisites: JDK 17, and the latest version of Intellij IDEA.
1. Open Intellij IDE.
2. Open this project in Intellij.
3. Configure the project to use JDK 17 and set Project Language level to the default 
SDK option.

## Running LittleLogBook
1. In Intellij, expand the tp module in the project explorer sidebar.
2. Navigate into src/main/java/seedu.address/ui/Main.java.
3. Click on the run current file to launch LittleLogBook.

Example Interaction:
Here's what using LittleLogBook looks like in the GUI:

`add n/ Yeo p/82923242  e/ Yeo@gmail.com a/Geylang Avenue 4  r/allergic to peanuts t/colleague`

`New person added: Yeo; Phone: 82923242; Email: Yeo@gmail.com; Address: Geylang Avenue 4  r/allergic to peanuts; Tags: 
[colleague]`

LittleLogBook will save the contacts you have added and
you can edit or delete them later. 

## Supported Commands:

### Add Command
**Purpose:** Allows teachers to create a new contact entry (student, colleague).

**Command format:** `add n/NAME p/PHONE e/EMAIL c/CATEGORY`

**Example commands:**
- `add n/John Doe p/98765432 e/john.doe@gmail.com c/student`
- `add n/Mary Tan p/91234567 e/marytan@e.nut.edu c/colleague`

### Other Commands:
`delete` `view` `search` `note`
