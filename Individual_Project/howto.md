# Requirement #1: Appropriate Data Structures:
Solution: Just use array lists for things that need lists. These are arbitrary length, changing lists.
# Requirement #2: Family Relationship Consistency:
Simply create a FamilyRelation object and store it in both persons familyConnections.
# Requirement #3: Supply Consistency:
We need a method to remove supply from location. We need to show that DisasterVictim uses that method
# Requirement #4: Use Database:
We'll just create an SQL file.
# Requirement #5: Multiple Interactions with Inquirer:
Inquirer should have a private static variable called numInteractions which updates each time there is an inquiry. We should make an arrayList<>
# Requirement #6: Interface to enter DisasterVictim:
For Requirement #6 and 7, we should use an interface to avoid repeating method names.
# Requirement #7: Interface to log inquirer queries:
Same as above. This will beimplemented as a gui.
# Requirement #8: Age or Birthdate:
Create age/birthdate as seperate attributes for DisasterVictim (maybe as attributes for Person instead)
# Requirement #9: Gender Options from a File:
List Gender Options as an additional attribute for DisasterVictim. Create getGender/setGender methods.
# Requirement # 10: Dietary Restrictions:
Solution: Implement enums in DisasterVictim class.
# Other Requirements for UML
Look at older solutions and see where attribute names are repeated and where we could turn them into subclasses (maybe create class Person for DisasterVictim and Inquirer?)
