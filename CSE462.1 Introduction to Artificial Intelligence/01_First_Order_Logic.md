# FIRST ORDER LOGIC

First Order Logic (FOL) is an important branch of mathematical logic. It allows mathematical representation and inference of objects, relationships between these objects, and properties that apply to objects.

Its basic components are as follows;

- **Variables:** They are expressed with letters such as x, y, z. They can express anything.
- **Functions:** They give another object depending on the given object. For example: FatherOf(x) returns the father of the object x.
- **Relations (Predicates):** They determine the relationship between two objects. For example: LargerThan(x,y) indicates that x is greater than seven.
- **Conjunctions:** ∧ (and), ∨ (or), ¬ (not), → (if), ↔ (if and only if).
- **Universal Quantifier (∀):** It means everyone or everything.
- **Existence Quantifier (∃):** It means at least one.

  **SAMPLES**

* ∀x Human(x) → Mortal(x)
  * All humans are mortal.

* ∀x Student(x) → MakeHomeWork(x)
  * Every student does homework.

* ∀x Cat(x) → LikesMilk(x)
  * Every cat likes milk.

* ∃x Dog(x) ∧ BarksLoudly(x)
  * There exists a dog that barks loudly.

* ∀x Student(x) ∧ Passed(x) → Graduated(x)
  * Every student who passed has graduated.

* ∃x Person(x) ∧ HasCar(x)
  * There exists a person who has a car.

* ∃x Person(x) ∧ SpeaksEnglish(x)
  * There exists a person who speaks English.

* ∀x Car(x) → CanDrive(x)
  * Every car can be driven.

* ∃x Tree(x) ∧ ProducesFruit(x)
  * There exists a tree that produces fruit.

* ∀x Plant(x) → NeedsWater(x)
  * Every plant needs water.

* ∃x Animal(x) ∧ HasTail(x)
  * There exists an animal that has a tail.

* ∀x Human(x) → HasBrain(x)
  * Every human has a brain.

* ∀x Student(x) → MustStudy(x)
  * Every student must study.

* ∀x (Human(x) ∧ IsAlive(x)) → ∃y (Animal(y) ∧ LivesWith(x, y))
  * Every human who is alive has an animal that lives with them.

* ∃x (Student(x) ∧ ∀y (Course(y) → Completed(x, y)))
  * There exists a student who has completed every course.

* ∀x (Teacher(x) ∧ Teaches(x)) → ∃y (Student(y) ∧ LearnsFrom(y, x))
  * Every teacher who teaches has at least one student who learns from them.

* ∃x (Car(x) ∧ IsElectric(x)) ∧ ∀y (Road(y) → CanDriveOn(x, y))
  * There exists an electric car that can drive on every road.

* ∀x (Person(x) ∧ HasJob(x)) → ∃y (Employer(y) ∧ Hires(y, x))
  * Every person with a job has an employer who hires them.

* ∃x (Bird(x) ∧ CanFly(x)) ∧ ∀y (Tree(y) → NestsIn(x, y))
  * There exists a bird that can fly and nests in every tree.

* ∀x (Human(x) ∧ Loves(x, Animal)) → ∃y (Animal(y) ∧ Loves(y, x))
  * Every human who loves an animal has an animal that loves them.

* ∃x (Student(x) ∧ HasScholarship(x)) ∧ ∀y (Course(y) → EnrolledIn(x, y))
  * There exists a student with a scholarship who is enrolled in every course.

* ∀x (Student(x) → ∃y (Course(y) ∧ EnrolledIn(x, y)))
  * Every student is enrolled in at least one course.

* ∃x (Animal(x) ∧ CanSwim(x)) ∧ ∀y (WaterBody(y) → LivesIn(x, y))
  * There exists an animal that can swim and lives in every water body.
 
*  ∀x [∀y Animal(y) → Loves(x, y)] → ∃y Loves(y,x)
    * For every x, if y is an animal and x loves y, there exists an animal that loves the person.
      
 * ∀x [∃y (Person(y) ∧ Likes(x, y))] → ∃z Likes(z,x)
    * For every x, if y is a person and x likes y, there exists a person who likes x

**P(x) ↔ Q(x)**
This means "P(x) if and only if Q(x)", that is:
* "If P(x) is true, then Q(x) must also be true."
* "If Q(x) is true, then P(x) must also be true."


  

  
