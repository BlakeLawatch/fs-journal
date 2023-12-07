# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | Creates cleaner code and limits redundancy |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | Member inheritance brings in all of the information from one class and injects it into another. Yes, a class inherits all members |

3. How does ***accessibility*** affect inheritance?

  > | Public makes functions accessible to all classes that inherit it, private makes it only accessible in that page. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is a unique key on each row of data. A foreign key is a way to create a virtual between two tables |

5. What is an ***alias***?

  > | It's a way to target a table with an abbreviation or a shorter word. Cleans up code and speeds up coding |

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | Select
  *
  FROM patients
  JOIN patient_doctors ON patients.id = patient_doctors.patientsId
 |
