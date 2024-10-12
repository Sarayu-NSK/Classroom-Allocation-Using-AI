# Classroom-Allocation-Using-AI

There has been extensive research done on the Classroom Allocation to Sections using
constraint satisfaction problem. It entails adjusting to a variety of constraints, such as
the quantity of lectures, subjects, classrooms, working hours, and other elements. The
issue consists of a collection of topics that need to be scheduled in timeslots, a set of
rooms where time can occur, a set of students who attend the subjects, and a set of
subjects that can be accommodated in the rooms and needed in the timeslots. The
restrictions that are laws inside and between each resource are what are at the core of
the issue. The issue demonstrates the combinatorial explosion's undesirable character.
The Classroom Allocation to Sections Constraint Satisfaction Problem can be solved
in several ways. The topic is addressed in this study using a constraint satisfaction
programming methodology. Numerous scheduling issues have been effectively
resolved using the artificial intelligence paradigm of constraint satisfaction problem.
A set of variables, a range of values for each variable, and a set of constraints between
each pair of variables make up the Constraint Satisfaction Problem (CSP). A
consistent assignment of all variables to values in a CSP's solution ensures that all
constraints are met. The foundation of the search technique for applying constraint
propagation is backtracking with arc consistency. The effectiveness of the solution is
significantly impacted by variable and value ordering techniques.

The project is based on Allocation of classrooms to different sections and creating a
schedule specifying the day and the time of the classes to be taught in a particular
classroom for a particular section. This project is done using the constraint satisfaction
technique, by the name, it is understood that constraint satisfaction means solving a
problem under certain constraints or rules. The set of constraints for this project is
given as:-
1. The classroom’s requirements should be consistently addressed for five
weekdays and for the given time slots.
2. All classrooms should be uniformly utilized by the sections.
3. Different sections may get the same classroom, but the same classroom should
not be allocated to more than one section within the same time slot, i.e. conflicts
must be addressed.
The method used in this project is Graph coloring with the help of a backtracking
approach. Constraint satisfaction problems on finite domains are typically solved
using a form of search. The most used techniques are variants of backtracking,
constraint propagation, and local search. Since the constraints of this project match
with the constraints usually stated with graph coloring, we have proceeded with this
approach.
