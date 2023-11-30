# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | It declares a scope and contains all of the objects within |

02. What is the difference between a `class` and an `interface`?

  > | Class has a definition and can be used. Interface only has a definition |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | Delete method? |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | public|

06. In the Car example what is `string` an indication of?

  > | It is the data type |

07. In the Car example what is `abstract` preventing?

  > | It prevents it from being instantiated on it's own |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | The row is the information for an object, a row is the properties for all of the objects |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE IF NOT EXISTS characters(
    id INT NOT NULL PRIMARY KEY AUTO-INCREMENT,
    name CHAR(225) NOT NULL,
    age CHAR(225) NOT NULL,
    description CHAR (225) NOT NULL
  ) |

10. In SQL how can you query more than a single table? Provide an example.

  > | SELECT *
  FROM table
  JOIN other_table ON table.id = other_table.id |
