def get_host () {
    list_val = "${envn}"
    return (list_val)   
    
}
def val = get_host()
properties([
    parameters([
       choice(choices: ['gws', 'gwsmob', 'gwsmol', 'gwstest'], description: "Increase version's number: MAJOR.MINOR.FIX", name: "app"),
       choice(choices: ['ci', 'cd'], description: "Increase version's number: MAJOR.MINOR.FIX", name: "envn"),
        choice(choices: ["${val}"], description: "Increase version's number: MAJOR.MINOR.FIX", name: "VERSIONING")
       
    ])
 ])
