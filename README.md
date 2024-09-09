+-------------------+
|    Comment        |
+-------------------+
| id (AutoField)    |
| post (ForeignKey) | --> Many-to-One with Post
| author (ForeignKey) | --> Many-to-One with User
| body (TextField)  |
| approved (BooleanField) |
| created_on (DateTimeField) |
+-------------------+