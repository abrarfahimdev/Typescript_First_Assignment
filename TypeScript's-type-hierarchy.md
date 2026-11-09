any, unknown, and never: Understanding TypeScript’s Type Hierarchy

TypeScript's type system has a hierarchy. They are unknown, any and never.
any is like an open box. anything goes in and comes out without any type of checking. And if a mistake is made, it only shows when the code runs.
unknown is like a close box. we can store anything in it. but we must have check what inside it before using it. and never is like a empty box which holds nothing. it is used for that functions which always throws error.

Why unknown Is Safer Than any in TypeScript

Unknown is always profred before any because unknown and any accepts same type of values but unknown checks the value first which make typescript more safer. and any do it without checking so it creates bugs. that's why always unknown is profred over any
