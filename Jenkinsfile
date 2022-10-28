dev val = "1,2,3,4,5,6"
properties([
    parameters([
       choice(choices: ['gws', 'gwsmob', 'gwsmol', 'gwstest'], description: "Increase version's number: MAJOR.MINOR.FIX", name: "VERSIONING"),
       choice(choices: ['ci', 'cd'], description: "Increase version's number: MAJOR.MINOR.FIX", name: "VERSIONING"),
        choice(choices: ["${val}"], description: "Increase version's number: MAJOR.MINOR.FIX", name: "VERSIONING")
       
    ])
 ])
