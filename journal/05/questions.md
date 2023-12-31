# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create, Read, Update, Delete |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | Create - Post
      Read - Get
      Update - Put
      Destroy - Delete |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | Object Relationship Mapping? |

04. Which two `HTTP` request types include a body?

  > | Put and Post |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | asynchronous, synchronous |

06. What are the three types of data relationships? Provide an example of each.

  > | one to one: An admin to a program
  one to many: A library holding books
  many to many: Coaches to players. Many coaches coaching many players  |

07. What is middleware?

  > | It's pre made programming software that acts as a defense system against inappropriate users |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | Request, respond |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | const winter = await req.tag(winter) |

10. What is a ***virtual property***?

  > | They are defined values of a model that can be combined together using specific methods or functions. |
