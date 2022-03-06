# assignment.js
class Student {
    constructor (name, ranking) {
        this.name = name;
        this.ranking = ranking;
    }
}
describe() {
    return `${this.name} achieves ${this.ranking}.`;
}
}

class Cohort {
    constructor (name) {
        this.name = name;
        this.classrom = [];
    }
}

add student (student) {
    if (student instance of student){
        this.studnets.push (student);
    }
}
 else {
     throw new Error(`You can only add an instance of Student.Argument is not a student: ${student}`);

 }

 describe(){
     return `{this.name} has ${this.students.length} students.`;

 }

 class Menu {
     constructor() {
         this.cohorts = []
         this.selectedCohort = null;
     }
 }
Start() {
    let selection = this.showMainMenuOptions();
    while (selection (selection != 0)) {
        switch (selection) {
            case "1" :
                this.createCohort();
                break;
                case "2" :
                    this.viewCohort();
                    break;
                    case "3" :
                        this.deleteCohort();
                        break;
                        case "4" :
                            this.displayCohort();
                            break;
                            default:
                                selection = 0;
        }
    }

}
selection = this.showMainMenuOptions
}
alert ("Goodbye.");

showMainMenuOptions() {
    return prompt (`
   0) exit
   1) create new cohort
   2) view cohort
   3) delete cohort
   4) display all cohorts
    `);
}
