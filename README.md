# day-6-task
a “person” class to hold all the details in javascript

In this class, we have a constructor method that takes in four arguments: name, age, gender, and occupation. These are used to initialize the corresponding properties of the Person object.

class Person {
  constructor(name, age, gender, occupation) {
    this.name = name;
    this.age = age;
    this.gender = gender;
    this.occupation = occupation;
  }
  
  getName() {
    return this.name;
  }
  
  getAge() {
    return this.age;
  }
  
  getGender() {
    return this.gender;
  }
  
  getOccupation() {
    return this.occupation;
  }
  
  setName(name) {
    this.name = name;
  }
  
  setAge(age) {
    this.age = age;
  }
  
  setGender(gender) {
    this.gender = gender;
  }
  
  setOccupation(occupation) {
    this.occupation = occupation;
  }
}

let person1 = new Person("Alice", 30, "Female", "Engineer");

console.log(person1.getName())
console.log(person1.getAge());
console.log(person1.getGender())
console.log(person1.getOccupation());


// Output: "Alice"
// Output: 30
// Output: "Female"
// Output: "Engineer"
